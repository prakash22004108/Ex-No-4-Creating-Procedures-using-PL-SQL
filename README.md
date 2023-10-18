# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```
mysql> delimiter //
mysql> create procedure Insert_employee()
    -> begin
    -> declare empid int;
    ->  declare empname varchar(10);
    -> declare dept varchar(10);
    -> declare salary int;
    -> insert into employee1(empid,empname,dept,salary)values(1,'arun','HR',1000000);    -> insert into employee1(empid,empname,dept,salary)values(1,'varun','glad',500000);
    -> insert into employee1(empid,empname,dept,salary)values(3,'aisha','sales',600000);
    -> end;
    -> delimiter//
```

### Output:
![Screenshot 2023-10-05 160646](https://github.com/paulsamson18/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119405794/2935b19e-3f38-4d55-a288-466fe2509520)

![Screenshot 2023-10-05 160609](https://github.com/paulsamson18/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119405794/05c18421-338d-4bf6-a82a-72ccb0d1dd3f)


### Result:
Thus procedure using PL/SQL has created successfully.
