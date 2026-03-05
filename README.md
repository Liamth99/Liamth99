## Hi, I'm Liam Thompson
![C#](https://img.shields.io/badge/C%23-Modern-239120?logo=csharp)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-Backend-512BD4?logo=dotnet)
![Roslyn](https://img.shields.io/badge/Roslyn-Analyzers%20%7C%20Generators-8A2BE2)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker)
![Azure](https://img.shields.io/badge/Azure-Cloud-0078D4?logo=microsoftazure)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?logo=githubactions)
![Entity Framework](https://img.shields.io/badge/EF%20Core-ORM-512BD4)

I'm a backend focused C# developer specializing in high performance and reusable libraries, API design, and compile time tooling.

Self taught and have been programming since 2020 with professional experience building production systems using .NET.

I focus on writing software that is explicit, maintainable, and validated at compile time wherever possible.

## Core Focus
 - Designing reusable libraries
 - API architecture & abstractions
 - Compile time tooling with Roslyn
 - Eliminating runtime errors via static analysis

## Current Project: AotObjectMapper
[![Github Repo](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/Liamth99/AotObjectMapper)
[![Documentation](https://img.shields.io/badge/documentation-grey?logo=readthedocs)](https://liamth99.github.io/AotObjectMapper/)
[![NuGet Version](https://img.shields.io/nuget/v/AotObjectMapper.Mapper.svg)](https://www.nuget.org/packages/AotObjectMapper.Mapper/)
[![Last commit](https://img.shields.io/github/last-commit/liamth99/AOTObjectMapper)](https://github.com/Liamth99/AotObjectMapper/commit/master)

A C# Roslyn source generator for compile time object mapping. With the goal of a having a feature set similar to that of AutoMapper but with the performance benefits of Source generation.

As of Feb 2026, this project already supports:
 - Mapping contexts (with thread safe options)
 - Nested object mapping
 - Polymorphic mapping
 - Pre/Post mapping hooks
 - Diagnostics + Code Fixes for improved developer experience
 - IConvertible support with optional format providers
 - Enum Mapping options
 - And more

## Tech Stack
**Backend:** ASP.NET Core • Minimal APIs • EF Core • Dapper

**Frontend:** Razor Pages • SSR • PWA • REST integration • JavaScript

**Tooling:** Roslyn Analyzers • Source Generators

**DevOps:** Docker • GitHub Actions • Azure • OpenTelemetry

## Software Experience

<details>
<summary><strong>Software Developer - ZoneRV</strong></summary>
I initially worked on the production floor for 4 years working in commissioning inspection. During that time, I identified that workers and team leaders were spending hours manually searching across systems to gather vehicle data every day.

To solve this, I independently designed and built a server side webapp after hours that provided real time access to relevant van information through a centralized system.

That internal tool led directly to my transition into a software development role.

Once in the developer position, I:
 - Redesigned the server web app into a standalone progressive web app with separate central API.
 - Designed and implemented a central API integrating multiple external services to:
   - Generate complex operational reports with multiple sources
   - Automate cross system workflows
   - Replace manual data aggregation processes
 - Expanded the PWA into a production grade internal tool
 - Implemented centralized structured logging (Seq + Serilog)
 - Added distributed tracing with OpenTelemetry
 - Wrote automated tests using xUnit/NUnit
 - Built full CI/CD pipelines with GitHub Actions With publishing to Azure

The system significantly reduced manual lookup time and improved operational visibility across multiple teams and provided new reporting options not posible before.

</details>
