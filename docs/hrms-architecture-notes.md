# 🗺️ My Office HRMS — Architecture Notes (Week 1)

> Write these in **your own words**. Do NOT paste company code here.
> This document becomes your answer to: *"Explain your current project."*

## 1. Project Overview
- What does the HRMS do? Who uses it (HR, employees, managers)? How many users approx.?
- Modules:

## 2. Tech Stack
| Layer | Technology |
|---|---|
| Web front-end | Razor / MVC |
| Mobile | Flutter |
| Backend | ASP.NET Core (version: ?) |
| Data access | ADO.NET + Stored Procedures, EF Core |
| Database | SQL Server (version: ?) |
| Hosting | IIS (Windows Server version: ?) |
| Authentication | ? (Cookie? JWT? Identity?) |
| Main NuGet packages | ? |

## 3. Folder / Project Structure
```
(write the solution structure here)
```

## 4. Request Flow — "Apply Leave" (Web)
1. Razor view:
2. Controller / action:
3. Service / business logic:
4. Data access (ADO.NET or EF Core?):
5. Stored procedure / table:
6. Response back to user:

## 5. Request Flow — One Mobile API (Flutter)
1. Flutter screen calls:
2. API controller / endpoint:
3. Authentication used:
4. Data access:
5. JSON response:

## 6. Architecture Diagram
```
Browser (Razor) ─┐
                 ├──> IIS ──> ASP.NET Core ──> ADO.NET / EF Core ──> SQL Server
Flutter App ─────┘
(refine this with your real layers)
```

## 7. My Role & Contributions
- Requirements, development, testing, deployment, implementation:
- Challenges I solved:
- Decisions I made (and why):

## 8. 2-Minute English Explanation (practice script)
> "I am currently working on an HRMS product that ..."
