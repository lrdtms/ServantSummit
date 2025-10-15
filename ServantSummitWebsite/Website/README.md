Servant Summit Website

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
