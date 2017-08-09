# Beginning Application Development with ASP.NET Core

While .NET has long been popular in the enterprise, it was traditionally for Windows environments only. The new .NET Core is open-source, cross-platform and optimized for applications that live in the cloud and communicate with mobile devices. Because of this, the .NET platform is now applicable to more scenarios and a broader base of developers who utilize open source in their web stacks. This makes a need for training in this area, even if you are experienced with ASP.NET.

This is a starter class on Microsoft's new cross-platform development platform - ASP.NET Core.  We will build something functional using production-grade practices, covering all the basics in order to get an application ready for deployment, including building a skeleton application, adding needed configuration, adding some features, and getting it deployed.

You can use any platform, since the development experience in ASP.NET Core is about the same on Windows, Mac or Linux. You can also use Docker, which is highly recommended since ASP.NET Core works seamlessly with it and it's fast becoming common for development and deployment.

You should come away from this course with a solid foundation in ASP.NET Core development, ready to dive in deeper, with a base understanding of the architecture, lifecycle and caveats of this exciting new open-source platform. You should also be able to provide your organization with insights on when and if you should upgrade or use ASP.NET Core on your next project. [I THINK THIS IS AMBITIOUS FOR 1 DAY]

## Objectives

* Gain an understanding of web applications built in ASP.NET Core
* Gain an understanding of the new application lifecycle and what's under the hood
* Learn the CLI-oriented development process that works the same on Windows, Mac or Linux
* Build an application from scratch, learning about each aspect of the infrastructure, from the internal Kestrel server to middleware to the DI containers used internally.
* Access databases using Entity Framework Core
* Create RESTful Web API services to be consumed by a front-end
* Set up a simple front-end to work with our ASP.NET Web API backend
* Basics of MVC & server-side rendering (lecture only, demos, no coding)
* Understand the basic deployment options and operations for an ASP.NET Core application * (demo)
* Getting started with automated testing (demo with dotnet test)

## Who Should Attend

ASP.NET developers who haven't built anything in ASP.NET Core will learn the new architecture, lifecycle and key APIs to be productive and get an application production-ready.

You don't need ASP.NET experience since we'll be starting from the beginning of the ASP.NET Core subject matter, however we will not cover C# concepts, so familiarity with those is recommended but should not be required if you are proficient with another statically-typed programming language such as Java.

# Curriculum

## Day 1

* Intro
  * What is ASP.NET, Core? History of .NET Core. (30m)
  * New Features, Benefits & Risks (15m)
  * MVC & Web API (10m)
  * Selling to management (10m)
* Architecture of ASP.NET Core (30m)
  * Stacks
  * Components of ASP.NET Core
  * Kestrel
  * LAB 1: Building the scaffolding for an application (30m)
* The ASP.NET Core lifecycle and core components
  * Intro (5m)
  * VS & VS Code (10m)
  * LAB 2: Wiring up the basics via Program.cs -> Startup (30m)
  * Middleware (30m)
  * LAB 3: Wiring up the middleware (45m)
  * Dependency Injection (10m)
  * Error Handling (10m)
* Part 2: Add configuration, security, logging, and dependency injection
  * LAB 4: Adding key configuration to your app (1h)
* Part 3: Add database access
  * Entity Framework Core
    * Choices
    * Production or not?
  * Code first
  * LAB 5: Wire up database & use Code First (45m)
  * Create repositories for data access

## Day 2: Intermediate topics, MVC & Deployment Concerns

* Testing
* Security
  * Authentication & Authorization
  * HTTPS
  * Data protection
  * Storing secrets
* Custom Middleware
* Caching
* Authentication and Authorization
* Web API
  * Routing
  * Client-Side Development
  * Single Page Applications
  * TBD
* ASP.NET MVC
  * Razor Pages
  * Model Binding
  * Views
  * Controllers
  * Tag Helpers
  * Advanced - Application model, filters, areas, application parts, custom model binding, custom formatters, formatting response data
  * TBD
* Deploying the application
  * Hosting with IIS
  * Hosting on Linux with Nginx, etc
  * TBD
* Containers (TBD)
  * Host in Docker
* Migrating from ASP.NET

## About Your Trainers

Wyn is currently a managing consultant & senior developer with Excella Consulting.  He has extensive experience with the analysis, design and implementation of software, largely with web-based applications on the .NET stack. He strives to be a good software craftsman using TDD, continuous integration, and Scrum. Lately, Wyn has been working in ASP.NET Core, Docker and AWS.

## Price, Date and Location

TBD