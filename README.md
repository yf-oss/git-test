# gittest
git测试学习

1、先pull，再commit,然后push上传
#第一次提交前需要先pull
(1)、git pull origin master:master
#origin是配置远程仓库地址的别名，第一个master是远程分支，第二个是本地分支
(2)、git commit -m "提交信息"
(3)、git push origin master:master

2、出现的问题：
error: failed to push some refs to 'https://github.com/yf-oss/gittest.git'
解决:先git push origin master -f（会覆盖原来的内容），然后再git push origin master:master


