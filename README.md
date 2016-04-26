# MySQL Playground

This Unit is not a teaching Unit. It's main purpose is to allow students to add and run their own `mysql` code.

You or your teacher may want to create some of your own challenge or test code. Just add some files and run!

## Contributing

See [CONTRIBUTING.md](https://github.com/codio-content/MySQL_Playground/blob/master/CONTRIBUTING.md) for instructions on how to contribute to this project.

## Using the `mysql` client
Open up a terminal window from the **Tools->Terminal** menu.

Once the terminal window is open, just type `mysql -u root -p` into the command line, press `<enter>` when prompted for a password and a new `mysql>` client will start. 

## Running `mysql` statements
The `mysql` client is enabled with all the database and table editing and reading privileges so you can experiment as much as you want.

### Example DML statements:

Data manipulation commands (CRUD) include: 

```sql
SELECT * FROM db_name.table_name;
```

```sql
INSERT INTO table_name (column1,column2,column3,...)
VALUES (value1,value2,value3,...);
```

```sql
UPDATE table_name
SET column1=value1,column2=value2,...
WHERE some_column=some_value;
```

```sql
DELETE FROM table_name
WHERE some_column=some_value;
```

## Sourcing `*.sql` files
The file tree is enabled as well, here, you can edit the `source.sql` file to add SQL statements and `source` it like this: 

```
mysql> source source.sql
```

Or you can create as many `*.sql` files as you want and `source` them as well.

## Creating a new SQL file
To create a new SQL file, please follow these steps.

1. Select the 'File' menu item at the top of this page.
1. Select 'New File' from the drop down menu.
1. In the dialog that appears, locate the 'File Name' field.
1. Enter 'filename.sql' in this field, where 'filename' is a name you choose for your file. 
1. Press 'OK' and a new window will appear where you can start coding.

## Advanced
If you want to have multiple panels open, you can add and close coding panels from the **View->Panels** menu. 
