Introduction
---------------

> **ASP.NET Core is a new open-source and cross-platform framework for building modern cloud based internet connected applications, such as web apps, IoT apps and mobile backends.** 

> ASP.NET Core apps can run on .NET Core or on the full .NET Framework. It was architected to provide an optimized development framework for apps that are deployed to the cloud or run on-premises. It consists of modular components with minimal overhead, so you retain flexibility while constructing your solutions. You can develop and run your ASP.NET Core apps cross-platform on Windows, Mac and Linux. ASP.NET Core is open source at GitHub.

> The best way to understand what ASP.NET Core is and why it was built is the [Official ASP .NET Core Documentation](https://docs.asp.net/en/latest/intro.html).

ASP .NET Core is a complete re-write of the 4.6 framework that came out last year and comes with a completely new architecture based on .NET Core.

ASP .NET Core is no longer based on`System.Web`. Instead, everything in the framework is modular and comes as NuGet packages which allows you to only include in your application the packages that you will use, resulting in a smaller application footprint and better performance.

It comes with integrated [dependency injection](https://docs.asp.net/en/latest/fundamentals/dependency-injection.html), a new request pipeline middleware and the ability to plug in your own web server (IIS - Windows only or Kestrel inside your own process in Windows, macOS and Linux) and run across operating systems with very similar development processes and tools.

Together with [TypeScript](https://www.typescriptlang.org/), the client-side framework of your choice (Angular 2, React, Aurelia etc), familiar tools for web developers (that didn't have very good support on Windows until very recently) like Grunt, Gulp or Bower and with a superior performance compared to Node, for example, Microsoft bets on ASP .NET Core to become one of the preferred frameworks when building modern web and cloud applications.

> For the complete section on client-side development with ASP .NET Core see [the Official ASP .NET Core Documentation](https://docs.asp.net/en/latest/client-side/index.html).

The ASP .NET Core team made a priority building a great development experience for client-side frameworks and you can see the work-in-progress on the [JavaScriptServices repository on GitHub](https://github.com/aspnet/JavaScriptServices/).


Tutorials and courses
----------------------

- [ASP .NET Core Fundamentals](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/)
- [Introduction to ASP .NET Core MVC with Visual Studio](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/index)
- [Introduction to ASP.NET Core MVC on Mac or Linux](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app-xplat/index)

- [Getting started with ASP.NET Core and Entity Framework Core using Visual Studio](https://docs.microsoft.com/en-us/aspnet/core/data/ef-mvc/index)

- [ASP.NET Core with EF Core - new database](https://docs.microsoft.com/ef/core/get-started/aspnetcore/new-db)
- [ASP.NET Core with EF Core - existing database](https://docs.microsoft.com/ef/core/get-started/aspnetcore/existing-db)

- [Deploy an ASP.NET Core web app to Azure using Visual Studio](https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-azure-webapp-using-vs)
- [Publishing to an Azure Web App with Continuous Deployment](https://docs.microsoft.com/en-us/aspnet/core/publishing/azure-continuous-deployment)
- [Use VSTS to Build and Publish to an Azure Web App with Continuous Deployment](https://docs.microsoft.com/en-us/aspnet/core/publishing/vsts-continuous-deployment)
