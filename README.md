# ASP.NET Core, Web API, IdentityServer4 .NET 5.0 Quick Start

This solution contains three projects that allow you to quickly get up and running with an ASP.NET Core, Web API, IdentityServer4 solution in .NET 5.0.

The solution was created using the IdentityServer4 QuickStarts guide

https://identityserver4.readthedocs.io/en/latest/quickstarts/0_overview.html


## Solution Structure

The three projects are as follows:

Api - this will be your Web API

Client - this is your ASP.NET Web App

IdentityServer - an IdentityServer4 built as per the ID4 QuickStart guide with a local SQL Server using Entity Framework


## To Start

In IdentityServer project StartUp.cs edit the SQL Server connection string if necessary:

```
const string connectionString = @"Data Source=(LocalDb)\MSSQLLocalDB;database=IdentityServer4.Quickstart.EntityFramework-4.0.0;trusted_connection=yes;";
```

Edit test user details in the file QuickStart\TestUsers.cs

And you should be good to start coding.


