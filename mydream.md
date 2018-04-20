一些常用的git命令
1. git add (filename)    把需要提交的文件放入缓存区
2. git add .             将当前分支下面所有的文件放入缓存区
3. git branch            查看有多少分支
   git reset HEAD        取消已经缓存的内容
4. git branch -d +分支名 删除本地git仓库某个分支
   git diff 分支1 分支2  比较两个分支内容的区别
5. git checkout master   切换到master分支
6. git checkout -b xxx   创建新的分支xxx，并且切换到这个分支
   git commit -m ‘xx’  将add命令上传到虚拟区的代码提交到本地git仓库
   ‘xx’                表示备注为什么提交这个代码，做了什么修改很重要
   git commit -am ‘’   合并add和commit的操作
7. git init              初始化git仓库
   git log               查看所有commit的diam版本
   git mv                移动或者重命名一个文件，目录，软连接
   git rm  filename      删除某个文件
   git rm -f filename    如果删除前以经修改并且已经放入缓存区域，要使用强制删除-f
   
9. git tag               查看所有的版本号
   git tag -a v1.0.1 -m ‘版本号’    创建版本号并且添加注释
   git tag -d v1.0.1 删除本地分支
   
