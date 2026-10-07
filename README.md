# STM Lab Manual Website

A single-file static website containing the STM lab experiments, questions, steps, code and expected outputs.

## Run locally

Open `index.html` directly in a browser, or use the VS Code Live Server extension.

## Deploy to Vercel

### Option 1 — Vercel dashboard
1. Create a GitHub repository.
2. Upload `index.html`.
3. Push the repository.
4. Import the repository into Vercel.
5. Framework preset: Other.
6. Build command: leave empty.
7. Output directory: leave empty.
8. Deploy.

### Option 2 — Vercel CLI
```bash
npm i -g vercel
vercel
```

No build step is required because this is a static HTML/CSS/JavaScript site.
