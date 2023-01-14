# pru_expanse_tracker
To start this project basic need is microsoft visual studio code 2022

in their when user open stdio option of clone this project is seen that you need by select by clicking clone a repository which offen is 1st option.

moving ahead install reqiured package by clicking on tools ->NuGet Package Manager -> Package Manager Console

then enter command line as " NuGet\Install-Package Microsoft.EntityFrameworkCore.SqlServer " for sql server

and then " NuGet\Install-Package Microsoft.EntityFrameworkCore.Tools " for tools

moving forward to generate datadet use cmd line as "add-migration ExpenseMigration "

in the ExpenseDBContext.cs , there is function name UseSqlServer Change the path of your database from getting it after u create data base .

that path will be found in Server Explorer , clicking right click on name of database table and selecting properties

at right side corner properties will be seen and over their the path that need to copied is in connection string .

that will build connection establishment between databse.

# Screen Shorts
# Expense Report
(https://user-images.githubusercontent.com/102210349/212492209-960376e0-9b8f-4519-9e69-473fc0260b51.png)
# Connection String
(https://user-images.githubusercontent.com/102210349/212492265-5b4ee2b5-9a7c-4e8f-b3cc-ecab380af142.png)
# Migration
(https://user-images.githubusercontent.com/102210349/212492295-019c8d22-7327-4c5f-b4f4-988a134087fe.png)
# Add Expense
![add_expense](https://user-images.githubusercontent.com/102210349/212492338-50dd6d04-0c1f-4cf2-a517-35dae0b4d193.png)
# Index Of Expense Tracker
![expense](https://user-images.githubusercontent.com/102210349/212492366-b8989b23-cc9b-48f5-86e5-7d902d73dde3.jpeg)
