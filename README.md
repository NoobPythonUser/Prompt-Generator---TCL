# Prompt-Generator---TCL

## Deployment notes (Vercel)

This project is plain static HTML/CSS/JS.

- `index.html` is the main entry file.
- `vercel.json` forces a static deployment (`@vercel/static`) and adds an SPA-style fallback route to `index.html`.

If you previously saw `500: FUNCTION_INVOCATION_FAILED`, redeploy after this commit so Vercel picks up the static config.
