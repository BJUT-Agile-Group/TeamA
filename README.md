Wiki
====

各小组代码仓库名称：

| 组长 |  代码仓库名称|
|:-:|---|
|闫琦  | Pos-Team1 |
| 陈全保 | Pos-Team2 |
| 洪鑫 | Pos-Team3 |
| 张立波 |  Pos-Team4|
| 沈思源 | Pos-Team5 |
| 徐恒远 | Pos-Team6 |
| 刘鑫 | Pos-Team7  |


Git使用说明：
===

## 准备工作

### 1. 删除Remote源 Origin

	git remote rm origin
	
### 2. 添加每个小组对应的代码仓库


	git remote add https://github.com/BJUT-Agile-Group/<代码仓库名称>.git
	
以第一小组为例：  
**代码仓库名称**为： `Pos-Team1`


## 代码提交

### 1. 提交本地代码修改

	git add -A
	git commit -am '本次代码修改概述'
	
### 2. 推送代码至Github

	git pull --reb origin master
	
	# 这个步骤需要输入Github的用户名和密码
	git push origin master
	
	
### 3. 到 Github查看所属代码仓库的修改
