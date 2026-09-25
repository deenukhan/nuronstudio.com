# Nuron Studio — Coming Soon

Luxury "coming soon" page for [nuronstudio.com](https://nuronstudio.com).

- Single static file: `index.html` (no build step). Light theme by default, with a light/dark toggle remembered per browser.
- `netlify.toml` sets a Content-Security-Policy that only permits the page's own inline scripts, which also blocks the injected "Powered by Netlify" badge. Recompute the hashes if the inline scripts change.
- Hosted on Netlify; email invitations are captured with Netlify Forms (form name: `invitation`)
- Deploy: push to `main`, or run `netlify deploy --prod --dir .`
