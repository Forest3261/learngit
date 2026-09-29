Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.

提交本地至github命令行：
git push origin master

查看分支：
git branch
创建：git branch 
切换：git switch 或 git checkout


创建并切换分支：
git switch -c dev
或
git checkout -b <name>


合并分支到当前分支：
git merge <name>

删除分支：
git branch -d <name>
