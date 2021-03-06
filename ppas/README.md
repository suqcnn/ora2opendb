### 迁移Oracle到PPAS/PG（EDB_Postgres_Advanced_Server）的兼容性分析
目前仅支持PPAS/PG9.6,PPAS/PG10，PPAS/PG11版本，后续会支持PPAS12

**文章汇总：**

+ **2019年度**
---
20191010_01.md [《Oracle PPAS 兼容性分析 之 NULL值》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20191010/20191010_01.md)

20190909_01.md [《Oracle PPAS 兼容性分析 之 CAST(MULTISET(subquery) AS type_name) 特性》](https://github.com/oomdb/ora2opendb/tree/master/ppas/20190909/20190909_01.md)

20190806_01.md [《Oracle PPAS 兼容性分析 之 外部表（EXTERNAL TABLE）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190806/20190806_01.md )

20190805_02.md [《Oracle PPAS 兼容性分析 之 BFILE数据类型》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190805/20190805_02.md)

20190805_01.md [《Oracle PPAS 兼容性分析 之 索引组织表（IOT）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190805/20190805_01.md)

20190323_01.md [《Oracle PPAS 兼容性分析 之 时区函数：TZ_OFFSET 和 FROM_TZ》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190323/201903023_01.md)

20190322_01.md [《Oracle PPAS 兼容性分析 之 TABLE列数据类型是UDT：集合类型（Collection Types）Varrays》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190322/20190322_01.md)

20190320_01.md [《Oracle PPAS 兼容性分析 之 隐式数据类型转换》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190320/20190320_01.md)

20190317_05.md [《Oracle PPAS 兼容性分析 之 TRIGGER：RETURN; 语法》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190317/20190317_05.md)

20190317_04.md [《Oracle PPAS 兼容性分析 之 TRIGGER：DELETE & WHEN(new)》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190317/20190317_04.md)

20190317_03.md [《Oracle PPAS 兼容性分析 之 UPDAET (subquery) SET 语法》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190317/20190317_03.md)

20190317_02.md [《Oracle PPAS 兼容性分析 之 PL/SQL事务：ROLLBACK TO SAVEPOINT》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190317/20190317_02.md)

20190317_01.md [《Oracle PPAS 兼容性分析 之 Hierarchical Queries 层次查询《1》：CONNECT BY ROWNUM - Row Generator Techniques》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190317/20190317_01.md)

20190315_01.md [《Oracle PPAS 兼容性分析 之 PL/SQL labels、 GOTO Statement 以及 NULL Statement》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190315/20190315_01.md)

20190314_01.md  [《Oracle PPAS 兼容性分析 之 分区表普通全局索引（NORMAL GLOBAL INDEX）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190314/20190314_01.md)

20190306_01.md  [《Oracle PPAS 兼容性分析 之 BITAND 函数》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190306/20190306_01.md)

20190228_01.md  [《Oracle PPAS 兼容性分析 之 聚合函数（PARALLEL_ENABLE AGGREGATE）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190228/20190228_01.md)

20190227_03.md  [《Oracle PPAS 兼容性分析 之 DBMS_UTILITY包（如：FORMAT_ERROR_STACK 函数）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190227/20190227_03.md)

20190227_02.md  [《Oracle PPAS 兼容性分析 之 DBMS_APPLICATION_INFO包（如：READ_CLIENT_INFO 方法）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190227/20190227_02.md)

20190227_01.md  [《Oracle PPAS 兼容性分析 之 VARRAY 二维集合类型（PL/SQL）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190227/20190227_01.md)

20190226_03.md  [《Oracle PPAS 兼容性分析 之 CHR(0) 用法》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190226/20190226_03.md)

20190226_02.md  [《Oracle PPAS 兼容性分析 之 FORALL STATEMENT》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190226/20190226_02.md)
 
20190226_01.md  [《Oracle PPAS 兼容性分析 之 伪列（ROWID）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190226/20190226_01.md)

20190225_03.md  [《Oracle PPAS 兼容性分析 之 TRIGGER ENABLE/DISABLE（触发器启用/禁用）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190225/20190225_03.md)

20190225_02.md  [《Oracle PPAS 兼容性分析 之 REGEXP_LIKE 正则匹配函数》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190225/20190225_02.md)

20190225_01.md  [《Oracle PPAS 兼容性分析 之 AT TIME ZONE DBTIMEZONE 用法》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190225/20190225_01.md)

20190223_02.md  [《Oracle PPAS 兼容性分析 之 SYS_CONTEXT 用法》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190223/20190223_02.md)

20190223_01.md  [《Oracle PPAS 兼容性分析 之 间隔分区（Interval Partitioning）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190223/20190223_01.md)

20190222.md     [《Oracle PPAS 兼容性分析 之 系统列（oid、tableoid、xmin、cmin、xmax、xmax、ctid）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20190222/20190222.md)

---
+ **2018年度**

20181122_01.md  [《Oracle PPAS 兼容性分析 之 管道函数（Pipelined Table Function）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20181122/20181122_01.md)

20181121_01.md  [《Oracle PPAS 兼容性分析 之 全局临时表（GLOBAL TEMPORARY TABLE）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20181121/20181121_01.md)

20181120_01.md  [《Oracle PPAS 兼容性分析 之 虚拟列（Virtual columns）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20181120/20181120_01.md)

20181119_01.md  [《Oracle PPAS 兼容性分析 之 数据类型》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20181119/20181119_01.md)

20180920_01.md  [《Oracle PPAS 兼容性分析 之 表分区（约束和索引问题）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20180920/20180920_01.md)

20180716_01.md  [《Oracle PPAS 兼容性分析 之 标示符命名（特殊字符、中文、带聚合函数等）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20180716/20180716_01.md)

20180628_02.md  [《Oracle PPAS 兼容性分析 之 数据库对象同名》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20180628/20180628_02.md)

20180628_01.md  [《Oracle PPAS 兼容性分析 之 SQL关键字(SQL Key Words) 》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20180628/20180628_01.md)

20180622_01.md  [《Oracle PPAS 兼容性分析 之 序列（SEQUENCE）》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20180622/20180622_01.md)

20180305_01.md  [《Oracle PPAS 兼容性分析 之 SUBPARTITION TEMPLATE》](https://github.com/oomdb/ora2opendb/blob/master/ppas/20180305/20180305_01.md)
