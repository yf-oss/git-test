# git-test
git测试学习

1、先pull，再commit,然后push上传
#每一次提交前需要先pull，origin是配置远程仓库地址的别名
(1)、git pull origin master:master 注：第一个master是远程分支，第二个是本地分支
(2)、添加文件到暂存区：git add .
(3)、git commit -m "提交信息"
(4)、git push origin master:master 注：第一个master是本地分支，第二个是远程分支git

2、出现的问题：
（1）error: failed to push some refs to 'https://github.com/yf-oss/gittest.git'
解决:先git push origin master -f（会覆盖原来的内容），然后再git push origin master:master
（2）命令git branch出现* (no branch, rebasing master)或git push origin master出现 
Everything up-to-date
解决：(1)、git add .
(2)、git commit -m "提交信息"
(3)、git rebase --continue
(4)、再git commit -m "提交信息"
(5)、git push origin master



