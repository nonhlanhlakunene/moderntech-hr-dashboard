# ModernTech HR Management System

A responsive HR management web app built for a fictional company, ModernTech Solutions. It covers the core things an HR team needs day to day: employee records, payroll, attendance, performance reviews, and a company calendar, all wrapped in a themeable dashboard with dark mode support.

Built with HTML5, CSS3, and vanilla JavaScript. Data is handled through JSON files and browser Local Storage, so there's no backend involved.

This was a group project completed as part of YouthCode Cohort 18 at Life Choices Academy, built by a team of five. This repo is my personal copy of our work, kept here to preserve the project and document my part in it.

Live demo: _[link coming soon]_

## My contribution

I built the Employee Data Management feature from the ground up: full CRUD (add, edit, delete, view employees), Local Storage persistence, search and filtering, a modal for editing records, and responsive layout work so it holds up on mobile and tablet. The files for this are `data.html` and `data.js`, on the `nonhlanhla-dev` branch of this repo. I also put together the presentation script and Figma wireframe we used to walk through this feature.

## What the app does

- **Authentication** – sign in, register, session handling, logout
- **Dashboard** – overview stats, task tracking, theme selector, dark mode
- **Employee Data** – view, search, and manage employee records (my contribution)
- **Payroll** – salary calculations, leave deductions, digital payslips
- **Attendance** – attendance and leave tracking
- **Calendar** – company scheduling
- **Performance Reviews** – star ratings and review summaries
- **Settings** – profile, company info, and theme preferences

## Tech stack

HTML5, CSS3, JavaScript (ES6), Remix Icons, Google Fonts. Data lives in JSON files (`employee_info.json`, `payroll_data.json`, `attendance.json`) and Local Storage.

## Project structure

```
ModernTech_Project
├── dashboard.html
├── login.html
├── attendance.html
├── payroll.html
├── data.html
├── calendar.html
├── reviews.html
├── settings.html
├── company-registration.html
├── style.css
├── main.js
├── attendance.json
├── employee_info.json
├── payroll_data.json
├── assets/
├── images/
└── README.md
```

## Running it locally

```bash
git clone https://github.com/nonhlanhlakunene/moderntech-hr-dashboard.git
cd moderntech-hr-dashboard
```

Open the folder in VS Code, install the Live Server extension, right-click `login.html`, and choose "Open with Live Server."

## Team

Nithaam, Nonhlanhla (Employee Data Management), Sisamila, Zanda.

## Notes

This was built for academic assessment, and there's plenty we'd improve with more time — a real backend and database, proper authentication, role-based permissions, and things like PDF payslip downloads or charts on the dashboard. For now it's a solid front-end demo of the core HR workflows.

---

**ModernTech HR Management System**
