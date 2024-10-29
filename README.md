## 项目简介

这是一个基于Neo4j的旅游领域知识图谱系统，提供图片展示、问题解答等功能。系统自带旅游领域数据节点3700，关系3800+，可以直接用过接口初始化数据进入neo4j，不用过多操作。

## 主要功能

* **图片展示查询系统:**使用py2neo和echarts做图谱展示，可以按照节点名称查询，默认展示100个节点和关系。
* **问题解答系统:**采用模板方式，提问语句进行切词做npl识别，识别后，去关系图谱查询到对应答案，可以支持多重问题类型。

## 技术架构

系统主要由以下部分组成：

* 前端：HTML、CSS、JavaScript
* 后端：Python（py2neo）、Neo4j
* 图谱展示：eCharts
* NLP：spaCy

## 使用说明

1. 下载项目包并解压缩。
2. 启动python backend服务。
3. 在浏览器中访问系统地址。
4. 使用用户名和密码登录系统。
5. 使用图片展示查询系统查询相关节点和关系。
6. 使用问题解答系统提交问题，系统将提供答案。


## 联系方式

微信号：zt745324325