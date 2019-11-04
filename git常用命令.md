## git基本配置
* git config --list 获取git配置信息  
* git config --global user.name "yangqh521" 设置名字
* git config --global user.email "yangqh521@qq.com" 设置邮箱

## git仓库操作
* git init 把当前的目录变成可以管理的git仓库，生成隐藏.git文件
* git clone URL 从远程库中克隆
* git remote add origin URL 关联一个远程库
* git remote rm origin 删除现有远程仓库 
* git remote set-url origin URL 更换远程库，URL为新地址

## git分支操作
* git branch 查看当前所有的分支
* git branch –d dev 删除dev分支
* git branch name 创建分支
* git branch -a 查看当前和远程所有的分支
* git checkout master 切换回master分支
* git checkout –b dev  创建dev分支 并切换到dev分支上
* git checkout -b 本地分支名x origin/远程分支名x 拉取远程分支并创建本地分支

## git提交操作
* git status 查看仓库状态
* git diff  XX 查看XX文件修改了那些内容
* git add XX 把xx文件添加到暂存区去
* git commit –m “XX” 提交文件 –m 后面的是注释
* git push origin master 把master分支推送到远程库对应的远程分支上

## git拉取合并
* git fetch orgin master 是从远程获取最新到本地，不会自动merge
* git pull origin master 从远程获取最新版本并merge到本地
* git merge dev 在当前的分支上合并dev分支


## git文件操作
* git rm XX 删除XX文件
* git checkout -- XX 把XX文件在工作区的修改全部撤销
* git checkout -- . 将多个文件一次性撤销

## git版本回滚
* git log	查看历史记录
* git reset  --hard HEAD^ 或者 git reset --hard HEAD~ 回退到上一个版本(如果想回退到100个版本，使用git reset –hard HEAD~100 ) 
* git reset --hard 目标版本号 回退到指定版本号
* git push -f origin master 强制提交远程代码 
* git revert -n 目标版本号 本地反做，解决冲突

## git初始推项目
1. 在gitlab上创建好对应的project
2. git init 初始化本地项目
3. git remote add origin git@xxx.xxx.xxx:xxx/xxx.git 关联远程仓库
4. git add . 添加文件到本地
5. git commit -m "init project" 本地提交
6. git push -u origin master -f 推送，-f强推


