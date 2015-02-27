# Git-In-Project
Summarize some experience while using git in our project.

总结使用git开发项目时的一些常用命令和一些自己的常见问题

下面的例子均以[Git-Example](https://github.com/angeliaz/Git-Example)为例


## Git开发流程

### 开发流程
	
下面的顺序仅供参考,具体以实际项目为准

顺序 | git步骤 | git命令 | 说明
------------ | ------------- | ------------ | ------------
1  | ``克隆代码`` | ``git clone 远程代码`` | ````  
2  | ``创建分支`` | ``git checkout -b branch_name`` | ``这是两个命令：git branch branch_name(创建分支) 和 git checkout branch_name(切换到某分支)``
3  | ``分支中开发`` | ```` | ````
4  | ``review代码`` | ```` | ````
5  | ``第一轮测试`` | ```` | ````
6  | ``添加代码到分支的暂存区`` | ``git add somefile`` | ````
7  | ``提交代码到分支`` | ``git commit -m "本次提交注释"`` | ````
8  | ``切换到主分支master`` | ``git checkout master`` | ````
9  | ``获取远程最新代码`` | ``git pull origin master`` | ````
10 | ``合并某分支到master`` | ``git merge branch_name`` | ````


### 各命令demo

#### 1. git clone 远程代码
	~~~ sh
	git clone https://github.com/angeliaz/Git-Example
	~~~

#### 2. git checkout -b branch_name
	~~~ sh
	git checkout -b dev
	~~~

## Git branch

## Git comment

## Git pull

## Git push

## 搭建自己的Git服务器