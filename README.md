# ServePoint – Volunteer Hours Tracker  
**by ShadowWorx Systems**

ServePoint is a web application designed to help JROTC cadets and high school students in Lee County, Florida track community service hours toward the 100-hour graduation requirement.

**Developer**: Matthew D. Barker (ShadowWorx Systems, CEO)  
**Course**: BYU-Idaho .NET/Blazor Semester Project (solo development)

## Purpose
This application supports students in meeting Lee County's community service graduation milestone by providing secure tracking of volunteer hours, progress visualization, and printable reports.  
Upon successful completion of the course, ShadowWorx Systems plans to donate ServePoint to the Lee County School District for use by students and organizers.

## Key Features
- Secure user authentication with role-based access (Cadet & Organizer)
- Organizers (admin role) create, edit, and delete volunteer opportunities with fixed hours (anti-cheat design)
- Cadets browse opportunities, sign up, mark completion, and automatically earn predefined hours
- Dashboard with prominent progress bar showing current hours / 100 + remaining
- Personal volunteer history list
- Exportable / printable hours report for school submission
- User-specific data (only view and manage your own records)

## Tech Stack
- Blazor WebAssembly (.NET 9)
- ASP.NET Core Identity (authentication & roles)
- MudBlazor (UI components, responsive design, progress bars)
- Entity Framework Core + SQLite (development database)
- Git for version control
- Azure Static Web Apps (deployment)

## Ownership & Licensing
ServePoint is developed and owned by ShadowWorx Systems (Matthew).  
This project is submitted as a requirement for the BYU-Idaho .NET/Blazor course.  
The university is granted a non-exclusive license to view and evaluate the code solely for grading purposes.  
ShadowWorx Systems retains full ownership and reserves the right to donate, license, or commercialize the application after course completion.

## Status
In development – Week 02 setup phase

## Getting Started (Local Development)
1. Clone the repository  
