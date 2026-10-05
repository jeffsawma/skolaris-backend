# Skolaris — Backend

Skolaris is a school management platform developed as the final team project of my AEC in Web Technologies Programming (Programmation en technologies Web) at Cégep Gérald-Godin.

This repository is an independent portfolio copy of the backend project and preserves the original team Git history and contributors.

**Project type:** AEC final team project  
**Backend:** ASP.NET Core / C# / Entity Framework Core / SQL Server  
**Frontend:** Blazor  
**Original team repository:** https://github.com/bouchelaghemmohammed/skolaris

---

## Project Overview

Skolaris was designed as a centralized school management system supporting administrative staff, teachers, and students.

The backend includes APIs and services for:

- User and role management
- Authentication
- Students and teachers
- Programs and academic levels
- Groups
- Courses and offered courses
- Registrations
- Grades and evaluation grids
- Report cards
- Absences
- Academic records
- School years and academic sessions
- Class schedules
- Messaging
- Notifications
- Audit logs
- Email integration
- SMS integration

---

## Technology Stack

- C#
- .NET 9
- ASP.NET Core Web API
- Entity Framework Core
- Microsoft SQL Server
- REST APIs
- Swagger / OpenAPI
- ASP.NET Core password hashing
- Twilio integration
- SMTP email integration

---

## Architecture

The backend follows a service-oriented ASP.NET Core structure:

Controllers → Services → Entity Framework Core → SQL Server

Main project areas include:

- Controllers
- Data
- DTOs
- Enums
- Migrations
- Models
- Services
- ViewModels

---

## My Contributions

This was a collaborative team project. My backend contributions included:

- Implementing CRUD operations for groups
- Implementing CRUD operations for academic levels
- Adding teacher assignment support for offered courses
- Adding group-related support to offered courses
- Improving the registrations API and filtering
- Fixing data seeding behavior
- Adding program description support
- Adding the notifications database migration

The preserved Git history includes my development branch and the original team commits, allowing the collaboration and contribution history to remain visible.

---

## Portfolio Copy

The original application was developed collaboratively in another team member's GitHub repository.

This repository was created as an independent portfolio copy after completion of the project. The original commit history, authorship, merges, and development branches have been preserved.

Configuration values and runtime-generated files were sanitized before this portfolio copy was published.

---

## Local Development

### Prerequisites

- .NET 9 SDK
- Microsoft SQL Server

The default development configuration uses a local SQL Server instance with Windows authentication.

### Build

Run:

dotnet build

### Run

Run:

dotnet run

Swagger is available when the application runs in the Development environment.

---

## Configuration

External-service credentials are intentionally left blank in the repository.

The application supports configuration for:

- SMTP email
- Twilio SMS
- SQL Server
- Frontend URL

For real deployments, credentials should be supplied using environment-specific configuration or environment variables rather than committed to source control.

---

## Demo Data

Database creation and demonstration-data seeding are restricted to the Development environment in this portfolio copy.

The seeded users are intended solely for local development and demonstration.

---

## Related Repository

The corresponding Blazor frontend portfolio repository is:

https://github.com/jeffsawma/skolaris-frontend

---

## Academic Context

Skolaris was developed as the final project of the AEC in Web Technologies Programming at Cégep Gérald-Godin.

The project provided practical experience with:

- Team-based Git and GitHub workflows
- Feature branches
- Pull requests and merges
- ASP.NET Core API development
- Entity Framework Core
- SQL Server
- Full-stack integration
- Collaborative software development
