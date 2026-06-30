# dibs ✶ — the dorm-to-dorm campus marketplace

Buy and sell with verified students on your own campus — everything within a
10-minute walk. This is the complete project: the phone app, the backend API,
the database, and the mobile-store wrapper.

```
dibs/
├── README.md                     ← you are here (how to run)
├── frontend/
│   ├── index.html                ← the phone app (open this to see it)
│   └── dibs-api.js               ← client that talks to the backend
├── backend/                      ← Node + Express + PostgreSQL API
│   ├── migrations/001_init.sql   ← the database schema
│   ├── scripts/                  ← migrate + seed
│   ├── src/                      ← routes · middleware · services
│   ├── .env.example              ← copy to .env and fill in
│   └── Dockerfile
└── mobile/
    └── capacitor.config.ts       ← wraps the web app into iOS / Android
```

There are two ways to run this. **Option A** shows you the app in 30 seconds with
no setup. **Option B** runs the real backend + database underneath it.

---

