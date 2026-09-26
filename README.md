# Grid Matrix — Commission Grid Viewer

Static site (viewer + admin) for Ideal Insurance Brokers.

- `index.html` — public viewer (no login)
- `admin/index.html` — admin portal, served at `/admin`
- Data: Firebase Firestore (loaded from CDN in-browser; no server/build needed)

## Deploy (Vercel)
1. Push this folder to a GitHub repo.
2. In Vercel: New Project → Import this repo.
3. Framework Preset: **Other**. Build Command: **(leave empty)**. Output Directory: **(leave empty / root)**.
4. Deploy. Viewer = `/`, Admin = `/admin`.

No environment variables required (Firebase config is embedded client-side).
