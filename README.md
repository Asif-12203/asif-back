# LifeDrop – MERN Blood Donation Platform
## Run
1. MongoDB running locally (or use Atlas URI).
2. Server: `cd server && cp .env.example .env && npm i && npm start`  (port 5000)
3. Client: `cd client && npm i && npm run dev`  (port 5173, proxies /api)
Default admin is auto-created from ADMIN_EMAIL / ADMIN_PASSWORD in .env.
Email alerts need SMTP_* in .env (otherwise they are logged to console).
