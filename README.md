# PROGPart2
ST10112350 - PROG 3A Part 2
Visual studios 2022 
ASP.NET Core Web App (Razor page)
.Net 8.0
NuGet Packages:
- Microsoft.AspNetCore.Authentication.Cookies
- Microsoft.AspNetCore.Mvc.Razor.RuntimeCompilation
- Microsoft.AspNetCore.Mvc.RazorPages
- Microsoft.EntityFrameworkCore
- Microsoft.EntityFrameworkCore.SqlServer
- Microsoft.EntityFrameworkCore.Tools

Database: "AgriEnegy"
connectionString: Data Source=(localdb)\MSSQLLocalDB;Initial Catalog=AgriEnergy;Integrated Security=True;Connect Timeout=30;Encrypt=False;Trust Server Certificate=False;Application Intent=ReadWrite;Multi Subnet Failover=False
Tables :
- Roles
- Users
- Farmers
- Products

  Web application starts with an option to register or login
  once successful, the user has access to either the Farmer pr Employee page
on the farmer page they can add new products 
on the employees page , they have access to edit the farmer profiles
