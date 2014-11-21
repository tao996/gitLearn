### Git 学习笔记

#### Git Gui 上那些常用的命令，因为通常是在command line 下操作的，这样就不用经常打开界面啦

<img src='./pic/1.start.png' />

<img src='./pic/2.sshkey.png' />

<img src='./pic/3.common.png' />

<img src='./pic/4.branch.png' />

<img src='./pic/5.commit.png' />

<img src='./pic/6.merge.png' />

<img src='./pic/7.remote.png' />

<img src='./pic/8.repository.png' />


#### 其它常用功能：

##### 查看文件修改记录

* 查看简单提交记录 git log --pretty=oneline fileName
* 查看详细提交记录 git log -p fileName
* 查看每一行提交	git blame fileName

##### git diff

1. 不同分支上的不同文件
> git diff <branchA>:<fileA> <branchB>:<fileB>
2. 不同分支上的相同文件
> git diff <branchA> <branchB> -- <file>

<img src='./pic/9.diff.png' />