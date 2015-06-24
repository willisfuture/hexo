title: 建立hexo个人博客
date: 2015-06-08 08:40:46
categories: 工具
tags: [写作,hexo]
---

###安装hexo
---
###上传到github
---
* git的基本操作

>**如何实现不同机子的同步？**

1. 建立一个项目的仓库，将hexo原文件上传
2. 然后建立一个git进行跟踪管理

	```
	git init //建立.git
    git add -a //跟踪所有文件
	git commit -a //提交所有跟踪文件的修改
	git push origin master //提交至远程仓库
	```
3、生成静态文件并上传
	
	```
	hexo g //生成静态文件
	hexo d //上传静态文件到远程仓库或服务器
    ```
