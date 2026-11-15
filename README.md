# Task Manager

A simple task manager built with Next.js, ready to deploy on Vercel.

## Features
- Add tasks with notes, priority, due date and a reminder time
- Track progress per task (0–100% slider and To do / In progress / Done status)
- Close and reopen tasks
- Reminders: desktop notification, sound and in-app popup with snooze
- Overview: totals, overdue count and overall progress bar
- Filters: Open, Overdue, Done, All

Tasks are saved in your browser (localStorage), so no database is needed.

## Run locally
```bash
npm install
npm run dev
```
Open http://localhost:3000

## Deploy
1. Push this folder to a new GitHub repository.
2. In Vercel, click **Add New → Project**, import the repo, and click **Deploy** (no settings to change).
3. Every push to `main` redeploys automatically.

## Limitations
- Reminders fire while the app is open in a browser tab (it can be in the background).
- Tasks live in one browser; they don't sync across devices.
