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

## API

### Endpoints

<img src="/pictures/endpoints.png" title="endpoints"  width="900">

### Start Endpoint

<img src="/pictures/api.png" title="start endpoint"  width="900">

### Status Endpoint

<img src="/pictures/api2.png" title="status endpoint"  width="900">

### Final Endpoint

<img src="/pictures/api3.png" title="final endpoint"  width="900">

