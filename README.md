COEST Portal — Backend scaffold

Quick start

1. Install dependencies:

```bash
npm install
```

2. Start server (serves `COEST.html` and exposes API):

```bash
npm start
```

By default the server runs on http://localhost:3000

API

- `GET /api/status` — health check
- `POST /api/contact` — accepts JSON `{ name, email, message }` and echoes it back (placeholder handler)

Notes

- This is a minimal scaffold (Express + CORS). If you want a database, authentication, or email integration, tell me which DB/service and I'll add it.
