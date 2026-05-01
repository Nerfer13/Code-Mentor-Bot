# CodeMentor Bot

Telegram-native MVP for coding mentorship:

- Telegram bot commands: `/start`, `/review`, `/challenge`, `/progress`, `/mentor`
- React Telegram Mini App with 6 screens
- SQLite for persistent data
- OpenAI-powered code review
- Webhook-ready deployment for Railway/Vercel-compatible setups

## Project layout

- `backend` - Express API + Telegram bot + SQLite
- `frontend` - React + Vite Telegram Mini App

## Quick start

```bash
npm install
npm run dev --workspace backend
npm run dev --workspace frontend
```

## Environment

Copy `backend/.env.example` to `backend/.env` and fill values.

## Deployment notes

- Backend: Railway/Fly/Render or any Node host with HTTPS
- Telegram bot: use webhook mode in production
- Frontend: Vercel static hosting
