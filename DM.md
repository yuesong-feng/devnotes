# 达梦数据库相关

查询名为xxx的对象：  
select * from sysobjects where name = 'xxx'；

查询父对象为xxx的对象：  
select * from sysobjects where pid = xxx;

查询id为xxx的索引：  
select * from sysindexes where id = xxx；

## dmdata_cmp工具

打印页
dmdata_cmp TYPE=5 READ_PATH=MAIN.dbf PAGE_NO=1234 PAGE_SIZE=8 N_PAGES=1 DEST_PATH=page.txt