# Official AC Wala – Nagpur — Full-stack app

Included:
- Customer service booking
- Persistent SQLite database
- Admin login with bcrypt password hash + JWT
- Job dashboard
- Technician assignment
- Job status updates
- Invoice storage
- WhatsApp request
- Google Maps review link
- PWA manifest

## Run
1. Install Node.js 18+.
2. Copy `.env.example` to `.env`.
3. Set a strong `JWT_SECRET` and `ADMIN_PASSWORD`.
4. Run `npm install`
5. Run `npm start`
6. Open `http://localhost:3000`

For public/production deployment, use HTTPS, a managed database/backups, secure environment variables, rate limiting, and a proper domain. The app intentionally does not hard-code a production admin password.
