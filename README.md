# Asynchronous APIs with .NET

In this project we build a .NET API solution around the Asynchronous Request Reply pattern. This allows is to decouple our APIs from long running processes. In addition we look at some competing approaches to achieve the same outcome, specifically: call backs (by using webhooks) and persistent connections using websockets / SignalR.

## Settings

### Add Packages
```
Microsoft.EntityFrameworkCore.SqlServer
Microsoft.EntityFrameworkCore.SqlServer.Design
Microsoft.EntityFrameworkCore.Tools
```

### Migrations
```
Add-Migration InitialCreate
Update-Database
```




<img src="/pictures/api.png" title="superhero api"  width="900">

