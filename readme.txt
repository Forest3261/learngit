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


###分支管理策略
#禁用Fast forward

###Bug分支
每个bug都可以通过一个新的临时分支来修复，修复后，合并分支，然后将临时分支删除。
但位于dev上的工作还没提交
使用stash保存工作环境快照
git stash


查看
git stash list

恢复
1. git stash apply
   但stash没删除，还需要git stash drop
2. git stash pop恢复并且删除stash内容








