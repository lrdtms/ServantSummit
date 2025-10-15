# Servant Summit Church Website

A modern, responsive church website with an administrative dashboard for managing members, events, messages, and donations.

## Files

- **index.html** - Main public website with pages for Home, About, Events, Register, Donate, and Contact
- **dashboard.html** - Admin dashboard for church staff to manage all data

## Features

### Public Website (index.html)
- Home page with church information
- About page with mission and values
- Events page showing upcoming church events
- Registration form for new members
- Donation page for online giving
- Contact form for inquiries and prayer requests

### Admin Dashboard (dashboard.html)
- Secure login system (demo credentials: admin / password)
- **Members Management**: View, search, and remove registered members
- **Events Management**: Add, edit, and delete church events
- **Messages**: View and manage contact form submissions
- **Donations**: Track and monitor all donations with financial summaries
- Real-time statistics dashboard

## How to Use

### For Church Members/Visitors:
1. Open `index.html` in a web browser
2. Navigate through the different pages using the navigation menu
3. Register as a member, make donations, or send messages through the contact form

### For Church Staff:
1. Open `dashboard.html` in a web browser
2. Login with credentials:
   - **Username**: admin
   - **Password**: password
3. Navigate between different sections using the tabs
4. Manage members, events, messages, and view donation records

## Data Storage

Currently, all data is stored locally in the browser's localStorage. This means:
- Data persists between page refreshes
- Data is specific to each browser
- For production use, you'll want to integrate with a backend database

## Future Enhancements

- Backend database integration (MySQL, PostgreSQL, etc.)
- Email notifications for new registrations and messages
- Payment processing integration for donations
- Export data to CSV/Excel
- Multi-user authentication with role-based access
- Email receipts for donations
- Calendar integration for events

## Security Note

⚠️ The current authentication is for demonstration purposes only. In production:
- Implement secure backend authentication
- Use HTTPS for all connections
- Hash passwords properly
- Implement CSRF protection
- Add input validation and sanitization
- Use environment variables for sensitive data

This is a simple static website for Servant Summit Church.

Files
- `index.html` — main site built with Tailwind via CDN.

Quick start (serve locally)

Run a minimal HTTP server and open http://127.0.0.1:8000 in your browser:

```bash
cd /home/lrdtms/ServantSummitWebsite/Website
python3 -m http.server 8000
```

Notes
- The site uses the Tailwind CDN; no build step required.
- To integrate with a build pipeline or deploy, add your preferred tools (Netlify, Vercel, GitHub Pages, etc.).
