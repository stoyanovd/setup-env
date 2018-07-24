Task to install MS SQL Serever, SSIS (Integration Service), SSMS (Studio) and so on

It's important to install in right order.

---------------------
1. Install MS SQL Server
---------------------

Download and install free version of MS SQL Server
https://www.microsoft.com/en-us/sql-server/sql-server-downloads
SQLServer2017-SSEI-Dev.exe

// you can check running server with `sqlcmd`

---------------------
2. Install features
---------------------

run Installation Center, "new SQL server installation", pick 
C:\SQLServer2017Media\Developer_ENU
as Media Folder
Now, you can pick Features: SSIS, SSAS (analytical services)

---------------------
3. Install features: Reporting services
---------------------

Reporting services must be downloaded and installed separately, after this installation finish
link: https://www.microsoft.com/ru-ru/download/confirmation.aspx?id=55252

---------------------
4. Install Studio
---------------------

Download and install studio
https://docs.microsoft.com/ru-ru/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017
