# Lizzis Retail Manager


I'm building this management system for my future business custom makeover and styling studio - InHerElement. The purpose of this project is to build a reusable management software using best practices and clean code besides revisiting/learning advanced ASP.NET, and C# topics in depth. I'm primarily following Mr. Tim Corey's Retail Manager course, and customizing on top of it to fit my business's requirements.

## Table of Contents

- [Background and Goals](#background-and-goals)
- [Phase 1 Documentation](#phase-1-documentation)
- [TODOs](#todos)
- [Credits](#credits)

  
## Background and Goals


**Phase 1** - Design and set up a desktop app in legacy .NET Framework(4.7.2), WPF UI in MVVM architecture pattern, a database, and a Web API with authentication. Then perform a transition of this app to .NET Core 3.1. I'm doing this to simulate the scenario of many businesses needing to migrate their existing legacy applications to a modern platform.    


**Phase 2** - Add Xamarin, Blazor, transfer the application into the Azure cloud, CI/CD, and Reporting(TBD).

**Phase 3** - Add microservices, Blazor WebAssembly PWA(TBD).


## Phase 1 Documentation


**Documenting every step for future reference**


**Initial Project**


Build a desktop app that runs a cash register, handles inventory, and manages the entire studio. In order to allow it to grow(to sell online), add a WebAPI Layer. 


**Initial Plan**


Build an MVP that can be expanded to cover all the features we need over time. The first step is getting all of the major pieces set up, including:
- Git on Azure DevOps
- SQL Database (SSDT)
- WebAPI with authentication
- WPF application that can log into the API


**Technologies**


- ASP.NET MVC
- .NET Core
- WebAPI
- SSDT
- WPF
- JavaScript
- HTML/CSS
- Authentication
- Data Validation
- Azure DevOps
- Reporting
- Logging
- Dependency Injection
- Design Patterns
- Async
- Unit Testing
- Git
- SOLID, Autofac


**Create WebAPI with Authentication**


**Configure Swagger**
**Set up Database**


- SSDT
- Start building SQL Server Database

  
**Set up Frontend Project**


- WPF with MVVM framework 
- Using Caliburn Micro as the MVVM framework system


## TODOs

- [ ] Add Installation instructions 
- [ ] Add project architecture 
- [ ] Add screenshot/video of demo 
- [ ] Refine background and goal section (Add separate 1. non-technical 2. technical description) 
- [ ] Plan future Improvement 


## Credits


**Special Thanks**


Huge shoutout to one of my favorite instructors Tim Corey for making [TimCo Retail Manager Course](https://www.youtube.com/playlist?list=PLLWMQd6PeGY0bEMxObA6dtYXuJOGfxSPx) available on YouTube for free, which is the primary resource followed during building this system. 


**Additional Resources**
- [Windows Presentation Foundation documentation](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/?view=netdesktop-7.0&WT.mc_id=dotnet-35129-website)
- [A tour of the C# language](https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/)
- [Swagger For .NET MVC Web API]()
- [Learn X in Y minutes](https://learnxinyminutes.com/docs/csharp/)
