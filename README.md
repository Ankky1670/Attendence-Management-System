# Vidyalaya AMS — Attendance Management System

A single-file, browser-only Attendance Management System with three roles: Admin, Faculty, and Student. All data is stored in the browser's `localStorage` — no backend needed.

## Run it
Just open `index.html` in a browser, or enable **GitHub Pages** for this repo (Settings → Pages → Deploy from branch → `main` / root) and visit the generated URL.

## Demo logins
| Role     | Username | Password     |
|----------|----------|--------------|
| Admin    | admin    | admin123     |
| Faculty  | rao      | faculty123   |
| Faculty  | mehta    | faculty123   |
| Student  | aisha    | student123   |

## Features
- **Admin** — manage students, faculty, and subjects
- **Faculty** — open a session and mark Present/Absent per student
- **Student** — view subject-wise and overall attendance %, with a low-attendance warning under 75%
