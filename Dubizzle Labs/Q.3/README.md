## SQL Challenge

You were given a table schema, which I don't remember exactly as of now, but it contained two tables, one was for `Employees` which consisted of some basic details about employees, `ID` as primary key and `DeptID` as foreign key linking it to '`Departments` table which consisted of `DeptID` as foreign key and other details about the departments.

You needed to write a query which returns the `DeptID`, `DeptName` and `Count` which is the count of number of employees in each department. You needed to sort the results in decreasing order from top to bottom according to `Count` and if still two rows are equal, they needed to be sorted based on `DeptID` in increasing order from top to bottom.
