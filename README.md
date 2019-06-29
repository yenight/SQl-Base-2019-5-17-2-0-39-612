说明：
1. 学生表：
- 创建表create table student(....);
- 添加数据：insert into student (name, age, sex) values (...);
- 查看数据：select * from student;
- 主要是创建stduent时，需要定义primary key为id，设置每个title的类型，大小。

2. 课程表：
- 创建表create table subject(....);
- 添加数据：insert into subject (subject, teacher, description) values (...);
- 查看数据：select * from subject;
- 主要是创建stduent时，需要定义primary key为id，设置每个title的类型，大小。

3. 课程表：
- 创建表create table score(....);
- 添加数据：insert into subject (student_id, subject_id, score) values (...);
- 查看数据：select * from socre;
- 主要是创建stduent时，需要定义primary key为id，设置每个title的类型，大小,还有设置stduent_oid,subject_id为外键foreign key。
