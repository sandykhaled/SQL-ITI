# SQL
**ANSI SQL**
1. Microsoft => Transact-SQL
2. Oracle => PL-SQL
3. IBM => IBM-PL-SQL
4. Open Source => Mysql

   1. DDL => Data Denfination Language -> metadata,structure (create db,create table,view table, select into,Alter,create function)
   2. DML => Data Manipulation Language -> data (insert ,delete ,update ,merge)
   3. DCL => Data Control Language -> security(grant,invoke,deny)
   4. DQL => Data Query Language -> display(select,grouping,union,joins,subquery)
   5. TCL => Transaction Control  -> excutation (commit , rollback)
```
   create table emp
(
eid int primary key,
ename varchar(50) not null,
eage int ,
eadd varchar(20) default 'cairo',
hiredate date default getdate(),
dnum int
)
alter table emp add salary int;
alter table emp alter column salary bigint;
alter table emp drop column salary;
drop table emp;
```
    
`
