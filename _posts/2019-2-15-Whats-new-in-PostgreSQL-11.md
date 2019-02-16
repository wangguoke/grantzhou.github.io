---
layout: post
title: What’s new in PostgreSQL 11
---

[原文链接】（https://modern-sql.com/blog/2019-02/postgresql-11#footnote-0）

## PostgreSQL 11中的新功能
PostgreSQL 11在四个月前就发布，我的评论本应早就发出。 让我们现在开始！

除了标准SQL外，PostgreSQL 11中的特色是窗口函数（over）。 
近8年来，从2009年到2017年，PostgreSQL是唯一支持SQL窗口功能的免费开源产品。
仅仅一年之后，[到2018年9月，所有开源竞争对手都赶上来了](https://modern-sql.com/blog/2019-01/sqlite-in-2018#window-functions)......
[有些甚至超过了PostgreSQL](https://modern-sql.com/blog/2018-04/mysql-8.0#window-functions)。
PostgreSQL社区已经做好准备，[PostgreSQL 11于2018年刚刚发布](https://www.postgresql.org/about/news/1894/)，它已经恢复甚至扩大了其领导地位。<sup>[0](#myfootnote0)</sup>

## 关于作者
<img align="left" width="100" height="100" src="https://modern-sql.com/static/markuswinand.5Ot1gTRt.jpg">
Markus Winand教授高效的SQL - 现场或者在线课程。 他使用现代SQL来最小化开发时间，并通过智能索引优化运行效率。
他的名为SQL Performance Explained的书已成为标准阅读。







<a name="myfootnote0">0</a>: PostgreSQL现在已经成为over子句的领导者。
在考虑支持的窗口函数时，由于PostgreSQL缺乏支持窗口函数中的*respect|ignore nulls*子句，因此可能与Oracle数据库排名类似。
在考虑运行时行为时，Oracle数据库可能会获胜，因为它可以根据单调推进窗口函数的结果正确应用Top-N优化（与PostgreSQL不同）。

