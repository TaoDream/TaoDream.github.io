# Git 操作

## branch 操作 

Q 新建一个分支，名字为Hello

A git branch Hello

Q 切换到Hello分支上

A git checkout Hello

Q 如何删除本地分支Hello

A git branch -d Hello

Q 将Hello推送到master的Hello分支上

A git push origin Hello:Hello (origin 表示远程主机，如果master上没有Hello分支，将创建Hello分支)

Q 如何在gitlab中新建merge requests

A 1 本地分支push到远程的某个分支 2 创建merge request即可。


