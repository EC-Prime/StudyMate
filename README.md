# StudyMate

StudyMate is an accessible university planner that helps students organise assignments, classes, activities, shared resources, and catch-up support in one calm workspace.

## Why it exists

University work is spread across lecture slides, learning platforms, group chats, calendars, and email. StudyMate brings the most important actions into a simple, student-friendly dashboard—particularly for students who miss class or need extra support catching up.

## Features

- Dashboard with priorities, progress, schedule, and catch-up prompts
- Planner tasks with due dates, notes, filters, and completion states
- Class organisation for subjects, lecturers, codes, and schedules
- Catch-up support requests with typed explanations and screenshot/file selection
- Shared materials interface for notes, PDFs, audio, video, and links
- View-only planner link generation for sharing with classmates or lecturers
- Login and sign-up presentation flow for the MVP
- Persistent dark mode
- Olive visual theme with subtle animated background particles
- Responsive layouts for desktop, tablet, and mobile
- Keyboard-friendly controls and reduced-motion support

## Technology

StudyMate is a dependency-free static web app:

- HTML5
- CSS3
- Modern browser JavaScript
- `localStorage` for local persistence

## Run locally

Open `index.html` directly, or use a local static server:

```bash
npx serve .
```

Then open the local URL shown by the server.

## Deploy

The project can be deployed to GitHub Pages, Vercel, Netlify, or another static host. No environment variables are required for the current MVP.

## Data and security note

This version is intentionally backend-free. Planner data, profile details, and catch-up requests stay in the user's browser. The login and sign-up screens are a prototype interaction, not secure account authentication. Do not use real passwords or upload sensitive student records to this version.

For production use, add a secure authentication provider, encrypted server-side storage, role-based lecturer access, secure file uploads, moderation, audit logs, backups, and institution-specific privacy review.

## Suggested next steps

1. Connect Supabase, Firebase, or another managed backend.
2. Replace demo authentication with secure email or university SSO.
3. Add lecturer dashboards for class materials and support responses.
4. Add real notifications and calendar integrations.
5. Conduct WCAG 2.2 AA, privacy, and usability testing with university students.
