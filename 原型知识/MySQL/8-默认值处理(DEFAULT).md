在MySQL中可以使用DEFAULT为列设定一个默认值。如果在插入数据时并未指定该列的值,那么MySQL会将默认值添加到该列中。

创建表时指定列的默认值
CREATE TABLE 表名(列名 类型 default 默认值, ...… );
示例:
创建emp3表,该表包含emp_id主键且自动增长,包含name,包含address该列默认值为”未知”。
`create table emp3(emp_id int primary key auto_increment, name varchar(10),address varchar(50) default 'Unknown');`

修改表添加新列并指定默认值
ALTER TABLE 表名 ADD COLUMN 列名 类型 DEFAULT 默认值;
示例:
修改emp3表,添加job_id该列默认值为0。
`alter table emp3 add column job_id int default 0;`

插入数据时的默认值处理
如果在插入数据时并未指定该列的值,那么MySQL会将默认值添加到该列中。如果是完全
项插入需要使用default 来占位。
示例:
向emp3 表中添加数据,要求address列与job_id列使用默认值作为该列的值。
法一：选择插入
`insert into emp3(name) values("admin");`
法二：完全插入
`insert into emp3 values(default,"oldlu",default,default);`
