# RestfulApiFreelancers
Restful API With Web Application
- This project is develop by visual studio 2019 with C#.

- This project is using Microsoft.EntityFrameworkCore , Microsoft.EntityFrameworkCore.SqlServer and Framework .NET5.0.
  
- This API is Connect with SQL Server.

- FreelancersAPI is the API to communicate with the database.

- WebFreelanceUI is the web application consume the FreelancersAPI.

Refernce by

-https://www.youtube.com/watch?v=pIlG3JVZy1Q&t=142s&ab_channel=CodeWithGopi

-https://www.youtube.com/watch?v=1WW6cEIbyqQ&ab_channel=RockNation

## Installation
  
- Way to install SQL Server
  
    -To download SQL Server , please go to https://www.microsoft.com/en-my/sql-server/sql-server-downloads

    -Once install SQL Server, please download SQL Server Management Studio (SSMS) https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16#download-ssms

    - Please open SQL Server Management Studio (SSMS) to setup the connection with localhost and Windows Authentication access.
 
    - Create the database Name as "demodb".
 
    - Create the datatable as:

```bash
CREATE TABLE [dbo].[tbFreelancers](
	[Id] [int] IDENTITY(1,1) NOT NULL,
	[username] [varchar](50) NULL,
	[mail] [varchar](50) NULL,
	[phone] [varchar](50) NULL,
	[skillsets] [varchar](max) NULL,
	[hobby] [varchar](max) NULL
) ON [PRIMARY] TEXTIMAGE_ON [PRIMARY]
GO
```
## License
License by Microsoft
