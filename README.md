# Gregory Guilloth — Portfolio

Interactive terminal portfolio. Pure HTML/CSS/JS — no build step, no dependencies.

## Local preview

Open `index.html` directly in any browser, or run a local server:

```bash
cd gregory-portfolio
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy to Vercel

**Option 1 — Drag and drop (no CLI needed):**
1. Go to [vercel.com](https://vercel.com) → New Project → drag the `gregory-portfolio/` folder
2. Vercel detects it as a static site — click Deploy
3. Live in ~30 seconds at a `*.vercel.app` URL

**Option 2 — GitHub (auto-deploys on push):**
1. Push this folder to a GitHub repo
2. Go to vercel.com → New Project → Import from GitHub
3. Framework preset: "Other" (static) → Deploy
4. Every `git push` to `main` auto-deploys

## Add a custom domain later

In your Vercel project settings → Domains → add your domain → update DNS records as instructed.

## Commands available in the terminal

| Command     | What it shows                              |
|-------------|--------------------------------------------|
| `help`      | Full command list                          |
| `profile`   | Positioning, background, differentiators   |
| `stories`   | Index of 3 case studies                    |
| `stories 1` | HealthHero AI Evaluation Framework         |
| `stories 2` | Tink Developer Onboarding                  |
| `stories 3` | Tink Analytics — the feature I killed      |
| `skills`    | AI products, dev platforms, domain         |
| `contact`   | Email, LinkedIn, availability              |
| `whoami`    | Easter egg                                 |
| `clear`     | Clear the terminal                         |
