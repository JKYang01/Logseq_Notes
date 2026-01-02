class:: template
alias:: 日记模板
tags:: #000-📥inbox, #p1-🫐seed-种子, #s3-★★★☆☆ 
bok:: 
public:: false
iteration:: [[May 23rd, 2024]] [[Jul 22nd, 2024]] [[Sep 16th, 2024]] [[Jul 17th, 2025]]

- ## what
	- logseq 中的日记模板
- ## why
	-
- ## how
	- today journal 
	  template:: today journal 
	  template-including-parent:: false
		- period:: [[]]
		  public:: false
		- **ONE** thing
			-
		- **TODO** in today
			- {{query (and (task todo) (between -3d -1d))}}
			- **daily routine**
				- TODO 每天写 5 条新笔记，每条笔记 5 个链接（最少1个链接）；
					- {{query (page-property :created <%today%> )}}
				- TODO 每天迭代 5 条(本周内的)老笔记；
					- {{query (page-property :iteration <%today%> )}}
		- Today I **LEARNED**
			- TODO 每天发布一篇文章
				- [[公众号/发文记录]]
				- [[ai 写作大法]]
			- TODO [[notion 数据库/chatgpt 学习宝典]]：每天更新3条内容，至少；
			- TODO [[courses/deeplearning.ai]]：每天学习一节课，至少；
			- TODO [[claude skills]]：每天新建一个skill，每天拆解一个已有skill；
			- TODO [[ai 知识管理]]：每天使用mcp访问笔记；
		- One Day in the **LIFE**
			- **morning**
				-
			- **noon**
			- **evening**
				- TODO [[coding with 小树]]：C++ 解题；打字；
				- TODO [[math with 小树]]：数学；
- ## how good
- ## inbox
	- TODO 每天4次deep research
		- {{query (and (page-property :class "deep_research") (page-property :created <%today%> ))}}
	- TODO 每天都在熊圈子发帖；
- ## todo
- ## ref.
- ## related
- ## archive
	- ### 迭代记录
		- [[Sep 16th, 2024]]：用 query 筛选出今日新建的笔记，今日迭代的笔记；让每天的笔记工作清晰，一目了然；