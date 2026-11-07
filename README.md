# RLW First-Timer Check-in

First-timer welcome form for RCCG Rivers of Living Water Parish.

- `/` visitor form (the QR code at the door opens this)
- `/team` follow-up team page (password protected)
- `/poster` printable A4 QR poster. The QR always points to whatever domain the site is opened on.

Static site. Form data is saved by the backend at rlw-first-timers.sites.tab.bot; `vercel.json` forwards `/api/*` there, so the Vercel domain and the tab.bot address share the same list.

Deploy: import this repo on Vercel (no build step, framework "Other"), then add your domain.
