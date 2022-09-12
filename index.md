
# Notes of studying SQL

- [Oracle SQL Developer](/SQL_Developer/Oracle_SQL_Developer.md)

- Syntax
    - [Syntax Error](/syntax/syntax_error.md)

- [Table Info](/Table_Info/table_ino.md)

- Select Statement
    - [Select From](/Select_Statement/select_from.md)
    - [Select Alias](/Select_Statement/select_alias.md)
    - [Select Distinct](/Select_Statement/select_distinct.md)
    - [Select Concatenation](/Select_Statement/select_concatenation.md)
    - [Select Arithmetic](/Select_Statement/select_arithmetic.md)

SQL 语法
- 大小写
    - **not case sensitive**大小写不敏感
    
    - **Keywords** are suggected to be entered in **uppercase**关键字：大写
    
    - **all other words**, such as table names and columns, are suggested to be entered in **lowercase**. 其他：小写

- 可读性
    - Statement can be entered on one or **many lines**.一个命令可以是多行
    
    - Clauses are usually placed on **separate lines** for readability and ease of editing分行书写命令，以获取可读性和易编辑性
    
    - Keywords cannot be split across lines or abbreviated保持关键字完整性,不能分行也不能缩简

    - **Tabs and indents** make code more readable缩进

- 分号semi-colon
    - SQL statements end with a **semi-colon ( ; )**以分号结束
    - a single command in SQL Developer can end with omission of the semi-colon.当只有一行代码时，可以忽略分号

- 逗号comma
    - to separate the column names分隔列名
    - a space is not necessary but is used to improve readability空格可提高可读性
    - 

- 双引号double quotation marks

    - Alias with spaces or special symbols别名含有空格或特别符号 

-  单引号single quotation marks

    - concatenation连接多列时



## 显示

- Alignment对齐
    - text / character fields: left-aligned;
    - date fields: left-aligned;
    - numeric data: right-aligned

- By default, Oracle does not display insignificant zeroes. i.e.: 54.50 -> 54.5



