# FARMAWORLD Website

## Overview

The **FARMAWORLD Website** is a full-stack **ASP.NET Core Razor Pages** web application developed during my **Web Development Internship at FARMAWORLD**. The system is designed to manage company operations, employees, products, financial records, and internal requests through a secure, structured, and scalable web platform.

The project follows a clean separation of concerns using **Razor Pages**, **C# models**, and database integration, focusing on reliability, maintainability, and real-world business workflows.

---

## Key Features

* User authentication and role-based access
* Employee management and personal information handling
* Product and sales management
* Financial records and transaction tracking
* Internal requests (forms, day-off requests, job applications)
* Statistical dashboards and data visualization (Chart.js integration)
* Secure CRUD operations with database connectivity

---

## Tech Stack

* **Framework:** ASP.NET Core (Razor Pages)
* **Language:** C#
* **Front-end:** Razor (.cshtml), HTML, CSS, JavaScript
* **Back-end:** ASP.NET Core Page Models
* **Database:** SQL-based database (via custom DB.cs)
* **Visualization:** Chart.js
* **Configuration:** appsettings.json
* **Dependency Management:** LibMan
* **Version Control:** Git & GitHub

---

## Project Structure

```text
FARMAWORLD/
│── Pages/
│   ├── Models/            # C# data models and helpers
│   │   ├── Client.cs
│   │   ├── Employee.cs
│   │   ├── Product.cs
│   │   ├── USER.cs
│   │   ├── DB.cs
│   │   ├── ChartJs.cs
│   │   └── ...
│   ├── Shared/            # Shared layout components
│   ├── Index.cshtml       # Main dashboard
│   ├── employee.cshtml    # Employee management
│   ├── product.cshtml     # Product management
│   ├── transactions.cshtml
│   ├── fin.cshtml         # Financial records
│   ├── Formrequest.cshtml # Internal requests
│   ├── requestdayoff.cshtml
│   ├── Stat.cshtml        # Statistics & charts
│   ├── Login2.cshtml      # Authentication
│   └── Error.cshtml
│── wwwroot/               # Static assets
│── appsettings.json       # Configuration
│── Program.cs             # Application entry point
│── libman.json            # Client-side libraries
│── README.md
```

---

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Hagar633/PHARMAWORLD-Company-website 
   ```
2. Open the project in **Visual Studio**.
3. Restore dependencies (NuGet & LibMan).
4. Configure the database connection in `appsettings.json`.
5. Run the project using **IIS Express** or **Kestrel**.

---

## Usage

* Log in using authorized credentials
* Navigate through dashboards and management pages
* Perform CRUD operations on employees, products, and financial data
* Submit and manage internal company requests
* View statistics and charts for business insights

---

## Security & Reliability

* Server-side validation using Razor Page Models
* Structured database access via centralized DB class
* Error handling with dedicated error pages
* Controlled access to sensitive operations

---

## Internship Context

This project was developed as part of my **Web Development Internship at FARMAWORLD (Dec 2024 – Feb 2025)**. I collaborated with clients and stakeholders to gather requirements, implement business logic, and ensure secure and reliable data storage.

---

## Author

**Hagar Alsherbiny Atallah**

* GitHub: (https://github.com/Hagar633)
* Email:(mailto:S-hagar.atallah@zewailcity.edu.eg)

---



