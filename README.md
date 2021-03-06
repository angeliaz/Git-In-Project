# Git-In-Project
Summarize some experience while using git in our project.

总结使用git开发项目时的一些常用命令和一些自己的常见问题

下面的例子均以[Icons-css](https://github.com/angeliaz/Icons-css/tree/master)为例


## Git开发流程

### 开发流程
	
下面的顺序仅供参考,具体以实际项目为准

git步骤 | git命令 | 说明
------------- | ------------ | ------------
克隆代码 | ``git clone 远程代码`` |   
创建分支 | ``git checkout -b branch_name`` | 这是两个命令：git branch 和 git checkout
分支中开发 |  | 
review代码 |  | 
第一轮测试 |  | 
添加代码到分支的暂存区 | ``git add somefile`` | 
提交代码到分支 | ``git commit -m "本次提交注释"`` | 
切换到主分支master | ``git checkout master`` | 
获取远程最新代码 | ``git pull origin master`` | 
合并某分支到master | ``git merge branch_name`` | 


### 各命令demo

#### git clone 远程代码
~~~ sh
git clone https://github.com/angeliaz/Git-Example
~~~

#### git checkout -b branch_name(创建分支并切换到改分支)
~~~ sh
git checkout -b dev
~~~

#### git branch branch_name(创建分支)
~~~ sh
git branch dev
~~~

#### git checkout branch_name(切换到某分支)
~~~ sh
git checkout dev
~~~

#### git add somefile
~~~ sh
git add index.html
~~~

#### git commit -m "本次提交注释"
~~~ sh
git commit -m "first commit"
~~~


## Git comment

## Git pull

## Git push

## 搭建自己的Git服务器