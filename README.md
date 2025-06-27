# Rehearsal Scheduler App

## Overview
Schedules rehearsals for bands and ensembles. Tracks attendance, sends reminders, and suggests optimal rehearsal times based on group availability. Web & mobile responsive. Integrates with Google Calendar and Twilio/SendGrid for notifications.

## Features
- Group and member management
- Member availability input
- Automated scheduling
- Attendance tracking and analytics
- Messaging/notifications
- Calendar integration
- Venue/resource booking
- Admin dashboard

## Tech Stack
- Front-end: ReactJS, Tailwind CSS, Vite
- Back-end: Node.js (Express)
- Database: PostgreSQL
- Messaging: Twilio/SendGrid
- Calendar: Google API

## Setup
1. Clone this repo
2. Install Node.js, npm, and PostgreSQL
3. Configure environment variables (API keys, DB, messaging)
4. Install dependencies (`npm install`)
5. Run migrations (`npm run migrate`)
6. Start server (`npm run dev`)

## Deployment
Deploy front-end to Vercel/Netlify, back-end to Railway/Fly.io/Render or similar. Update env config for production and integrate secrets.

## Security
- Use strong passwords; all sensitive data encrypted
- JWT authentication
- Rate limiting
- 2FA for admins

## License
MIT
