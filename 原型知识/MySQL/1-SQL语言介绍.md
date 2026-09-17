SQL Language语言分为：  
DQL 数据查询语言：SELECT FORM WHERE  
DML 数据操作语言:INSERT UPDATE DELETE  
DDL 数据定义语言:CREATE ALTER DROP  
DCL 数据控制语言:GRANT REVOKE  
TCL 数据控制语言:COMMIT ROLLBACK SAVEPOINT  
SQL语言简介：  
结构化查询语言简称SQL，是一种数据库查询和程序设计语言，用于存取数据以及查询、更新和管理关系数据库系统  
SQL能做什么：  
面向数据库执行查询  
在数据库中插入新的记录  
更新数据库中的数据  
从数据库中删除记录  
创建新数据库  
在数据库中创建新表  
在数据库中创建存储过程  
在数据库中创建视图  
设置表、存储过程和视图的权限
 
数据查询语言 DQL：  
其语句也称为数据检索语句，用以从表中获得数是哪出据，确定数据怎样在应用程序中给出。  
SELECT FROM WHERE ORDER BY HAVING
 
数据操作语言DML：  
用于添加、修改和删除表中的行  
INSERT:添加数据  
UPDATE:更新数据  
DELETE:删除数据
 
数据定义语言DDL：  
定义数据库对象语言  
CREATE:创建数据库对象  
ALTER:修改数据库对象  
DROP:删除数据库对象
 
数据控制语言DCL：  
它的语句通过GRANT或REVOKE获得许可，确定用户对数据库对象的访问  
GRANT：授予用户某种权限  
REVOKE：回收授予的某种权限
 
事务控制语言TCL：  
它的语句能确保被DML语句影响的表的所有行及时得以更新  
COMMIT:提交事务  
ROLLBACK:回滚事务  
SAVEPOINT:设置回滚点
 
注意：数据操纵语言DML（insert、update、delete）针对表中的数据；  
而数据定义语言DDL(create、alter、drop)针对数据库对象，比如数据库datebase、表table、索引index、视图view、存储过程procedure、触发器trigger
 
SQL语言语法  
SQL语句不区分大小写，关键字建议大写  
SQL语句可以单行或多行书写，以分号结尾
   

ctrl＋s 保存