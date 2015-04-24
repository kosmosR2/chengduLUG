title : 博客使用说明
date : 2015-4-25 13：35：00
author : kosmos
authorURL : http://github.com/kosmosR2/
tags :
- Hexo
---
#Hexo介绍
hexo是一款基于node.js的博客框架，具有一定的可扩展性，支持md格式的博客上传。可以随意切换主题风格。其最大的特点就在于假设方便，比较适合我们这种小博客。
#上传文章
hexo支持动态检查博客文件变化。所以只要在github上开个源，push或者commit开个hook让server把文章拖下来就行了。
##fork 文章源
首先，fork[当前文章源](https://github.com/kosmosR2/chengduLUG)，当然这个源以后可以改。然后把它clone到本地，就可以开始你的修改了。
##发起pull requests
完成修改之后先push到自己源上面，然后发起pull requests，待管理员审核通过后就能直接在页面上看到效果了。当然你push到自己的源上只有已经可以在github的page上做一定的预览了。
#格式说明
上传的博客应该遵循固定的格式：
	
	title : 博客使用说明
	date : 2015-4-25 13：35：00
	author : kosmos
	authorURL : http://github.com/kosmosR2/
	tags :
	- 标签1
	- 标签2
	---
	markdown 正文	
		
##title
title是必要属性，文章标题。
##date
发布日期，是博客排序的依据。
##author authorURL
作者和作者自己的链接。
##tags
标签，方便检索。目前主页上的检索还不能用，应该是主题的问题，我看能不能最近修复一下。
##markdown 正文
###小标题
小标题由#来实现，不要出现一级标题下面就是三级标题，可能会造成小标题格式错乱。
###图片引用
大家尽量引用比较安定的图片源就可以。或者看我们这个服务器上好不好存图片？
#待改进
##首页tags
这是主题的问题，我以前竟然没有发现。。。
##博主头像
敢不敢给个CDLUG的大图？
##博客的标签
目前只实现了title，date等5个，以后看情况是不是加点别的，比如贡献者之类的。然后就是目前author只能有一个，这个有时间再改进咯。
		
		
		
		
		
		
		
		
		
		
	
	
	
	
	
	
	
	
