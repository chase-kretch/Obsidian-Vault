
## Commands

- Creating a new project
	- dotnet new console --use-program-main --name [name]
- Creating a sqlite database
	- dotnet ef migrations add InititalCreate
	- dotnet ef database update
- Installing EntityFramework
	- dotnet add package Microsoft.EntityFrameworkCore.Sqlite
	- dotnet add package Microsoft.EntityFrameworkCore.Tools
	- dotnet add package Microsoft.EntityFrameworkCore.Design
- 
	