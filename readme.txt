$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
$ mkdir learngit //创建文件夹
$ cd learngit  //打开文件夹
$ pwd //显示当前目录
/Users/michael/learngit
git init //创建仓库

git add  readme.txt // 把 readme.txt文件添加到仓库

git add -A   // 添加所有改动

git add *     // 添加新建文件和修改，但是不包括删除

git add .    // 添加新建文件和修改，但是不包括删除

git add -u   // 添加修改和删除，但是不包括新建文件

git reset <file> // 撤销提交单独文件

git reset        // unstage all due changes

git commit -m '提交信息' //吧文件提交到仓库  -m 本次提交的说明

git status   //掌握当前仓库状态

git diff //比较差异

git log//日志 --pretty=oneline

git relog //记录你的每一次命令

git reset HEAD //返回版本库

git checkout 


git push -u origin master //提交远程

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>


用git log --graph  --pretty=oneline命令可以看到分支合并图。

git merge --no-ff -m 'merge with no-ff' dev //使用dev分支合拼,禁止使用fast wforward

