# ASP.NET Core و Web API

پرسش‌های این بخش دربارهٔ ساخت و نگه‌داری سرویس‌های وب با ASP.NET Core است.

## Pipeline، Middleware و Routing

1. What is middleware in ASP.NET Core, and in what order do middleware components execute?
2. How can you create custom middleware?
3. What is the difference between `IApplicationBuilder.Use()` and `Run()`?
4. What is the difference between middleware and an MVC filter?
5. How does routing work in ASP.NET Core?
6. What is the difference between conventional routing and attribute routing?
7. What are the differences between MVC controllers, Razor Pages, and Minimal APIs?
8. How would you structure Minimal API endpoints in a larger application?

## Dependency Injection و پیکربندی

9. What are the Singleton, Scoped, and Transient service lifetimes?
10. What problems can occur when a scoped service is injected into a singleton?
11. How would you safely use a scoped service from a background or singleton service?
12. What is the Options pattern, and how do you validate configuration?
13. How does configuration layering work across `appsettings.json`, environment-specific files, and environment variables?
14. What is the purpose of `IConfiguration`?

## API، امنیت و خطاها

15. What is model binding, and how do `[FromBody]`, `[FromQuery]`, `[FromRoute]`, and `[FromForm]` differ?
16. How do you implement JWT authentication and authorization in an ASP.NET Core API?
17. What are access tokens and refresh tokens, and how should they be handled?
18. How would you implement role-based or permission-based authorization?
19. How do you configure CORS, and what does it not protect an API from?
20. How would you handle exceptions globally for all API endpoints?
21. What is API versioning, and how can it be introduced without changing existing URLs?
22. What is rate limiting, and where would you apply it?
23. How do you prevent overposting in an MVC application or Web API?
24. What are health checks, and how would you use them to monitor dependencies?

## کارهای پس‌زمینه، لاگ و کارایی

25. When would you use `IHostedService` or `BackgroundService`?
26. How do you stop a background service gracefully?
27. What is structured logging, and how do you avoid logging sensitive data?
28. What is the difference between `IMemoryCache` and `IDistributedCache`?
29. What caching strategies do you know, and how do you handle cache invalidation?
30. How would you investigate high memory usage or a slow API response?
31. What is the difference between `PeriodicTimer` and `Task.Delay()` in a recurring background task?
32. How would you deploy an ASP.NET Core application and safely apply database migrations?

## منابع مرتبط

- [۱۰۰ پرسش مصاحبهٔ API](../api/README.md)
- [۱۰۰ پرسش Full Stack .NET](../../sources/dotnet/100_Full_Stack_NET_Developer_Interview_Questions_1760730856.pdf)
- [۱۵۰ پرسش .NET](../../sources/dotnet/net-interview-questions.pdf)
- [مجموعهٔ پرسش‌های Full Stack](../../sources/full-stack/Interview%20Questions.pdf)
- [پرسش‌های فارسی .NET](../../sources/dotnet/questionParsa.docx) و [مجموعهٔ فارسی استخدامی](../../sources/persian/SoalatEstekhdami_14040320.pdf)
