# 达梦数据库相关

查询名为xxx的对象：  
select * from sysobjects where name = 'xxx'；

查询父对象为xxx的对象：  
select * from sysobjects where pid = xxx;

查询id为xxx的索引：  
select * from sysindexes where id = xxx；

