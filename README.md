# Mini-HRMS

A hand-built Human Resource Management System, created to learn and demonstrate
**C#, ASP.NET Core MVC, Web API, ADO.NET (Stored Procedures), EF Core and SQL Server**.

> Every line of code in this repository is written by me. AI is used only as a tutor.

## Planned Modules
| Module | Features | Status |
|---|---|---|
| Employee | Add / Edit / List / Delete employees, departments | ⬜ Not started |
| Leave | Apply leave, approve/reject (role-based), leave balance | ⬜ Not started |
| Attendance | Check-in / check-out, monthly report | ⬜ Not started |
| Auth | Login, roles (Admin / HR / Employee), cookie auth (web) + JWT (API) | ⬜ Not started |

## Tech Stack
- .NET 8 · ASP.NET Core MVC (Razor) · ASP.NET Core Web API
- ADO.NET + Stored Procedures · EF Core
- SQL Server
- xUnit + Moq

## Planned Structure (built step by step)
```
MiniHRMS/
├── src/
│   ├── MiniHRMS.Web/            # ASP.NET Core MVC (Razor views)        — Week 5
│   ├── MiniHRMS.Api/            # ASP.NET Core Web API (for mobile)      — Week 7
│   ├── MiniHRMS.Core/           # Entities, interfaces, business logic  — Week 8
│   └── MiniHRMS.Infrastructure/ # ADO.NET, EF Core, repositories         — Week 6/8
├── database/                    # SQL scripts: tables, stored procedures — Week 6
├── tests/
│   └── MiniHRMS.Tests/          # xUnit tests                            — Week 9
├── practice/                    # C# console practice (Weeks 1–4)
└── docs/                        # Learning log & notes
```

## Getting Started (do these yourself — typing commands is part of learning!)
```powershell
# Week 1–4: C# practice console app
dotnet new console -n CSharpPractice -o practice/CSharpPractice -f net8.0
dotnet run --project practice/CSharpPractice
```

## Learning Log
See [docs/learning-log.md](docs/learning-log.md).
