# AGENTS.md

## What it is
Super repository for the Medication Reminder System. It holds two git submodules: `app` (frontend, MehdiMamas/nodejs-assessment-app) and `server` (backend, MehdiMamas/nodejs-assessment-server). The repo itself has no code, only the README and `.gitmodules`.

## Setup
- Clone with submodules (`git clone --recurse-submodules`, or `git submodule update --init`), then follow `server/README.md` and `app/README.md`.
- Needs Node.js 16+, npm 7+ and Ngrok (to expose the local server to Twilio webhooks).
- The server needs its own `.env` with API keys (details in the server README).

## Run
- Frontend: `http://localhost:3000`. Backend API: `http://localhost:5000`.

## Notes
- Changes to app or server code go in their own repos; this repo only moves the submodule pointers.
- No CI is configured.
