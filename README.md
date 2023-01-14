# pru_expanse
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
