# Skillz

Skillz is a skill-based hiring platform prototype with recruiter, candidate, and admin views. It demonstrates assessment creation, candidate evaluation, timed test-taking, score reports, and dashboard workflows.

## Tech Stack

| Layer | Tools |
| --- | --- |
| Frontend | Next.js 16, React 19, TypeScript |
| UI | Tailwind CSS, shadcn/ui, Radix UI |
| Forms | React Hook Form, Zod |
| Charts | Recharts |
| UX | Role-based navigation, loading context, transitions |
| Backend | Placeholder folder for future FastAPI implementation |

## Project Structure

```text
skillz-main/
+-- frontend/
|   +-- app/
|   |   +-- admin/          # Admin dashboard, users, analytics, settings
|   |   +-- recruiter/      # Recruiter dashboard and assessments
|   |   +-- candidate/      # Candidate dashboard, assessment, results
|   |   +-- login/
|   |   +-- signup/
|   +-- components/         # Role navs, dashboard modules, UI system
|   +-- hooks/
|   +-- lib/
+-- backend/                # Reserved backend workspace
```

## Frontend Setup

```bash
cd skillz-main/frontend
npm install
npm run dev
```

## Main Product Areas

| Area | Purpose |
| --- | --- |
| Recruiter | Dashboard, assessments, candidates, results, analytics |
| Candidate | Assessment attempt, timer, answer capture, result breakdown |
| Admin | Users, monitoring, analytics, settings |
| Assessment | Objective, coding, and subjective sections |

## Current Data Mode

- The project uses local demo data for dashboards, assessments, and results.
- Backend planning notes are present in `backend/`.
- A future backend can connect auth, AI assessment generation, persistence, scoring, and anti-cheat telemetry.

## Notes

- Assessment attempts store answers locally in the demo flow.
- The UI already separates recruiter, candidate, and admin navigation patterns.

