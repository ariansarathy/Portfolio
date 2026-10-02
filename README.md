# Arian Sarathy — Portfolio

A personal portfolio styled like a code editor. It's a single static `index.html` with no build step.

- **Explorer and tabs**: each "file" is a section (`README.md`, `experience.ts`, `projects.json`, …). Each one is linkable, e.g. `/#projects`.
- **Live typing editor** on the home view: it types a greeting, "runs" it in a terminal, then cycles through short code snippets from real projects.
- **⌘K / Ctrl K** opens a command palette to jump between files.
- **Light/dark toggle** in the status bar. Dark is the default, and the choice is remembered.
- Respects `prefers-reduced-motion` and works on phones.

## Files
| File | Purpose |
|---|---|
| `index.html` | The whole site |
| `profile.webp` | Profile photo |
| `resume.pdf` | Linked from the site. Replace it after updating your résumé. |
| `RESUME_BULLETS.md` | Rewritten résumé bullets, not published by the site |

## Run locally
Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy
Push this folder to GitHub and import it on [Vercel](https://vercel.com/new) or turn on GitHub Pages. No configuration is needed.
