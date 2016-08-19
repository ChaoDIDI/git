vim  .gitignore
输入node_modules/   按下esc过滤文件
要点个i不然是不能输入的
过滤.Ds_store/
然后shit加:然后输入wq
git init

终端命令行
.gitignore//这个是git仓库过滤文件(过滤不需要提交的文件或者文件夹)
git init 初始化一个git仓库

git status  //查看当前仓库的状态

git add //把需要提价文件添加到本地缓存

git add . //可以把所有的提交文件缓存到本地中

git commit  - m '提交信息’ 把本地缓存中的文件提交到本地仓库

git branch  分支名  //创建一个新分支

git checkout 分支名  //切换到指定的分支

git branch -d 分支名 //删除一个分支

git log//查看日志
git log - -graph  —pretty =oneline   //加入一些美化和图形的命令

git reset logid --hard //回退到指定的一次提交

git tag tagName  为代码打标签.标签可以进行切换和直接发布

git log  --graph --pretty=oneline  --abbrev=commit
                         查询所有上传内容
nam init

add package.json

git status
//查看文件目录

git log  --graph --pretty=oneline  --abbrev=commit
查看 提交完成的git 请求

git reset logic  编码 --hard //回退到指定的一次提交

git tag tagName  为代码打标签.标签可以进行切换和直接发布

esc   wq 回车

** 远程服务器相关操作**
1. git clone [git链接](https://github.com/EdisonpLEE/-.git)
2. git pull origin master:master > //把远程分支代码拉取合并到本地的master分支
3. git push origin master:master  //把本地的Master分支推送到服务器的master分支
4. git clone 远程服务器地址  //把远程服务器的代码clone到本地
5. git branch  //查看当前分支名


