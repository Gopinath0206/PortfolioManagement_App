Portfolio Management System
A full‑stack .NET MVC + Web API application with Clean Architecture

Manage LinkedIn‑style professional profiles with role‑based access, JWT authentication, and a clean, maintainable codebase.

✨ Key Features
Area	Highlights
Authentication & Authorization	• JWT Bearer tokens • ASP.NET Core Identity
• Role‑based access (User, Admin)
Profile Management	• Create / update your own profile (details, skills, certificates, projects)
• Upload avatar & social links
Community	• View any other profile (read‑only)
• Endorse skills and leave comments
Admin Dashboard	• Review reports • Delete or restore profiles
Clean Architecture	• Domain → Application → Infrastructure → Presentation layers
• Mediator pattern (CQRS) • Repository + Unit‑of‑Work
Developer Friendly	• Swagger / OpenAPI docs
• EF Core migrations • Seed data script
• Docker‑ready SQL Server image

🏗️ Tech Stack
Layer	Tech
Presentation	ASP.NET Core MVC ( Razor Views )
API	ASP.NET Core Web API 8  (Swagger, FluentValidation)
Application	MediatR, AutoMapper
Infrastructure	EF Core 8, SQL Server / Docker, Serilog
Security	ASP.NET Core Identity, JWT Bearer, ASP.NET Authorization Policies
