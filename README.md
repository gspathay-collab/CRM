
# Gurdip — Referral CRM

A lightweight Next.js + Tailwind web app to manage partner outreach for accountants & property agents.

## Features
- Leads with stages (New → Contacted → Brochure Sent → Meeting Booked → Partner Signed / Closed)
- One‑click activity logging (LI connect, email, brochure, call, meeting, partner)
- Weekly dashboard with targets & progress bars
- Messaging templates (cover letter, emails, LinkedIn, call script)
- Import / Export JSON
- Data stored in your browser’s localStorage

## Quick Start (Local)
```bash
npm install
npm run dev
# open http://localhost:3000
```

## 1‑Click Deploy to Vercel
1. Create a free account at vercel.com and install the Vercel CLI (optional).
2. Click “New Project” → “Import” and select this folder (or push it to a GitHub repo and import).
3. Vercel auto-detects Next.js. Use defaults and deploy.
4. Your CRM will be live at a URL like https://your-project.vercel.app

## Notes
- The app saves data in the browser’s local storage. If you need multi-user access, consider adding a small backend later.
