# Prompt-Generator---TCL

## The Content Lab — Brand Intelligence Assistant

This project is now a TCL-exclusive internal assistant prototype that supports:

- Brand selection for multi-team workflows.
- Current affairs digest for each brand (updates, risks, opportunities).
- Brand-scoped Q&A (local intelligence mode by default, optional live model if a user provides their API key at runtime).
- Deck outline generation for stakeholder/client presentations.

## Deployment (Vercel)

This is a static app.

- `index.html` is the entrypoint.
- `vercel.json` forces static hosting with SPA fallback routing to `index.html`.

## Security note

No API keys are stored in the code. If a team member wants live model responses, they can paste a temporary key in the UI during that session.
