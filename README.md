# Git  的常用命令

| 命令名称                               | 作用           |
| -------------------------------------- | -------------- |
| `git config --global user.name 用户名` | 设置用户签名   |
| `git config --global user.email 邮箱`  | 设置用户签名   |
| `git init`                             | 初始化本地库   |
| `git status`                           | 查看本地库状态 |
| `git add 文件名`                       | 添加到暂存区   |
| `git commit -m "日志信息" 文件名`      | 提交到本地库   |
| `git reflog`                           | 查看历史记录   |
| `git reset --hard 版本号`              | 版本穿梭       |

![](https://github.com/echo7s520/git/blob/main/images/git%E5%B1%82%E7%BA%A7.PNG)

------

# Git  分支命令

| 命令名称              | 作用                       |
| --------------------- | -------------------------- |
| `git branch 分支名`   | 创建分支                   |
| `git branch -v`       | 查看分支                   |
| `git checkout 分支名` | 切换分支                   |
| `git merge 分支名`    | 把指定分支合并到当前分支上 |

------

# Git 团队协作

pull 拉取：从代码托管中心拉取到本地库

push 上传：从本地库上传到代码托管中心

clone 克隆：==访问用户== 从代码托管中心下载到本地库

------

# Git 跨团队协作

远程库1 ------------------------> fork ------------------> 远程库2  （2获取1的代码内容）



远程库2 -----------> Pull request ---------> 审核 --------------> merge -----------> 远程库1



------

# Git Hub 远程库使用

| 命令名称                           | 作用                                                     |
| ---------------------------------- | -------------------------------------------------------- |
| `git remote -v`                    | 查看当前所有远程地址别名                                 |
| `git remote add 别名 远程地址`     | 起别名                                                   |
| `git push 别名 分支`               | 推送本地分支上的内容到远程仓库                           |
| `git clone 远程地址`               | 将远程仓库的内容克隆到本地                               |
| `git pull 远程地址别名 远程分支名` | 将远程仓库对于分支最新内容拉下来后和当前本地分支进行合并 |





# Git 集成 Idea 使用

* ## 1  初始化本地库

![](https://github.com/echo7s520/git/blob/main/images/git01.png)





* ## 2 添加到暂存区

![](https://github.com/echo7s520/git/blob/main/images/git02.png)

* ## 3 提交到本地库

![](https://github.com/echo7s520/git/blob/main/images/git03.png)

![](https://github.com/echo7s520/git/blob/main/images/git04.png)
