# sql
sql语句学习的一些整理

show databases;
*查询所有数据库名称*

create database 数据库名称；
*创建数据库

create database if not exists；

drop database (if exsits)；

select database();
查看当前数据库

use database；
使用数据库

show tables;
查看当前数据库下所有表名称

desc tabelname;
查询表结构

create table tablename(
       字段名1 数据类型1，
       字段名2 数据类型2，
       ..
       字段名n 数据类型n
）；
创建表
#注意创建表时至少应该有一个属性包含在内 column

drop table (if exists)tablename;
删除表；












 DDL 数据定义语言
 DML 数据操作语言：对表中的数据进行增删查改
 DQL 数据查询语言：查询数据库中表的记录
 DCL 数据控制语言



