# Issue/Bug Item Explanations 问题选项解释
@ Yuanwen Li

在Jira上创建Issue，这些问题可以是bug，可以是一些需求不明确的地方，功能请求(new feature)或者任何其他您想要跟踪的的任务；创建每一个问题的时候需要提供如下的信息：
* 问题类型（Issue Type）
* 摘要（summary）
* 问题描述（description）
* 问题所属的项目
* 问题关联的项目组件（component）
* 问题影响的项目版本（affect version）
* 问题将被解决的项目版本（resolved version）
* 问题发生的环境
* 问题的优先级（priority level）
* 问题的报告者
* 问题的指派处理人 （由Scrum master或者Team Leader指派）
* 问题的当前状态
* 问题相关的历史记录

## Issue Type 问题类型
* Bug  测试过程、维护过程发现影响系统运行的缺陷
* New Feature  对系统提出的新功能
* Task  需要完成的任务
* Improvement  对现有系统功能的改进

## 优先级
* Blocker  阻塞开发或测试的工作进度，或影响系统无法运行的错误
* Critical  系统崩溃，丢失数据或内存溢出等严重错误、或者必需完成的任务
* Major  主要的功能无效、新增功能建议
* Minor  功能部分无效或对现有系统的改进
* Trivial  拼写错误，文本未对齐等

## 状态
* Open  表示问题被提交等待有人处理。
* In Progress  问题在处理当中，尚未完成。
* Resolved  问题曾解决，但解决结论未获认可，需要重新分派解决。
* Reopened  问题解决，等待结果确认，确认的结果是“Reopened”或者“Closed”。
* Closed  问题处理结果确认后，置于关闭状态。

## 解决
-- 这是一个对task进行多次控制的办法，如果遇到问题比如，需求侧暂时没办法给出明确的需求，源头类资源信息不全，等等非计划类的问题，可以通过解决（Resolution）中的一些状态来标注状态，sprint之后可以和SM及需求方讨论是否再下个sprint中再开一个内容。

* Fixed  问题已经解决。
* Won’t Fix  问题未解决 - 将不会解决的问题。
* Duplicate  重复的问题。 需要link 到之前已经开过的问题上。
* Incomplete  问题描述得不够准确、完全。
* Cannot Reproduce  问题重现失败，或者无足够的信息重现问题。

## 项目版本
-- Scrum Master, PM, Team Leader 需要注意
在一个项目上，一般会有多个版本，如：1.0alpha、1.0beta、1.0、1.2、2.0。

JIRA系统中的问题涉及到两个版本字段：

-影响版本，如一个bug可能影响版本1.1和1.2。

-修复版本，如bug影响版本1.1和1.2，可能在2.0版本上被解决。

版本通常有三种状态：发布/released、未发布/unreleased和归档/archived。版本还有发布日期，在特定的报告中会显示。在JIRA系统中可以为项目创建版本。