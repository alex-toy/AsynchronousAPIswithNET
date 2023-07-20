# Asynchronous APIs with .NET

In this project we build a .NET API solution around the Asynchronous Request Reply pattern. This allows is to decouple our APIs from long running processes. In addition we look at some competing approaches to achieve the same outcome, specifically: call backs (by using webhooks) and persistent connections using websockets / SignalR.

- Install packages for the API
```
Microsoft.EntityFrameworkCore.Design
Microsoft.EntityFrameworkCore.SqlServer
```

- create an *App Registration* for the API
<img src="/pictures/app_registration1.png" title="app registration"  width="500">
