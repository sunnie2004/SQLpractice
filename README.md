# SQLpractice
## 50 questions to pass SQL<br>

### 1.Version:SQL5.6<br>
### 2.tool<br>
http://sqlfiddle.com/#!9/d4e25a
### 3.Table1  Student<br>
| stu_id |	name |	birthday |	sex |
| ------- | ------ | ------- | ------- |
|1	|ZHAOLEI|	1990-01-01|	MALE|
|2	|QIANDIAN|	1990-12-21|	MALE|
|3	|SUNFENG|	1990-05-20|	MALE|
|4|	LIYUN|	1990-08-06|	MALE|
|5|	ZHOUMEI|	1991-12-01|	FEMALE|
|6	|WULAN|	1992-03-01|	FEMALE|
|7|	ZHENGZHU|	1989-07-01|	FEMALE|
|8|	WANGJU|	1990-01-20|	FEMALE|

### Table2 Course<br>
| course_id |	name |teacher |
| ------- | ------ |------ |
|01|	CHINESE|	02|
|02|	MATH|	01|
|03	|ENGLISH	|03|

### Table3 Teacher<br>
| tea_id |	name |
| ------- | ------ |
|01	|ZHANGSAN|
|02	|LISI|
|03	|WANGWU|

### Table4 Score<br>
|stu_id|	course_id|	score|
| ------- | ------ |------ |
|1	|01	|80|
|1	|02	|90|
|1	|03	|99|
|2	|01	|70|
|2	|02	|60|
|2	|03	|80|
|3	|01	|80|
|3	|02	|80|
|3	|03	|80|
|4	|01	|50|
|4	|02	|30|
|4	|03	|20|
|5	|01	|76|
|5	|02	|87|
|6	|01	|31|
|6	|03	|34|
|7	|02	|89|
|7	|03	|98|
### 3.practice <br>
#### 3.1create table
CREATE TABLE table_name(create_definition,.....
);
set FOREIGN KEY:
> WHEN CREATING TABLE
FOREIGN KEY (column_name) REFERENCES table_name(column_name)<br>
>AFTER CREATING TABLE
ALTER TABLE table_name ADD FOREIGN KEY (column_name) 
REFERENCES table_name(column_name)
#### 3.2add content
INSERT INTO table_name[(column1,column2,....)] VALUES<br>
(),<br>
(),<br>....<br>
();<br>
#### 3.3update table
UPDATE table_name<br>
SET column1 = value1, column2 = value2, ...<br>
WHERE condition;
#### 3.4delete table
DELETE FROM table_name WHERE condition;<br>
#### 3.5query table
SELECT column_name(s)<br>
FROM table_name<br>
WHERE condition<br>
LIMIT number;<br>
