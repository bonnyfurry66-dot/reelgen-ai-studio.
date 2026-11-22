REELGEN BACKEND STATUS

The website frontend is ready to deploy, but these API routes still need a real backend:
- POST /api/signup
- POST /api/login
- POST /api/logout
- GET  /api/me
- POST /api/story
- POST /api/videos
- GET  /api/videos
- GET  /api/videos/:id

Do not put AI provider keys in index.html or any browser JavaScript.
Add them as Vercel Environment Variables after choosing providers.
A real deployment needs server-side authentication, a database, object storage,
and an AI video + text/voice provider integration.
