# CommonUtil
常用的工具类、命令、方法整理

1.将本地的一个分支推送到远程的一个新的分支上
git push origin localbranch:remotebranch

git push origin :remotebranch 删除远程分支

2.将远程分支映射到本地
git checkout -b localbranch origin/remotebranch
