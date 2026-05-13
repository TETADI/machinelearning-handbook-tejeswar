# Machine Learning Mastery — A Master Curriculum

The third landing page — a complete, ground-up ML curriculum in plain English. Built so a software engineer with zero ML background can learn from the Perceptron (1958) to today's Agentic AI (2026+) — with every concept explained intuition-first, math-second, and connected back to modern LLMs.

**Distinct from the other two pages:**
- **Architecture Handbook** — warm editorial cream paper for *enterprise architects*.
- **Ecosystem Guide** — dark tech navy for *AI engineers entering the field*.
- **ML Mastery (this)** — friendly notebook white + ink blue + gold highlighter for *students learning ML end-to-end*.

## What's covered (9 modules)

| # | Module | Highlights |
|---|---|---|
| 01 | Historical Context | 70-year timeline · AI vs ML vs DL vs GenAI nested-circles diagram |
| 02 | Mathematical Foundation | 6 pillars (linear algebra, calculus, probability, statistics, info theory, optimization) + worked Bayes example |
| 03 | The Algorithm Library | 60+ algorithms in 10 families · decision table + 80/20 rule |
| 04 | Deep Learning · Full Stack | MLP → CNN → RNN → Transformer (with self-attention formula) |
| 05 | The Full ML Lifecycle | End-to-end pipeline diagram + evaluation-metric cheat sheet |
| 06 | The LLM & GenAI Era | 10-year evolution timeline + 9 stages from tokenization to agents |
| 07 | The Complete Toolbox | Every library, framework, vector DB, and platform organized by layer |
| 08 | Needs → Solutions | Practical "if you have this problem, use this tool" map |
| 09 | Professional Roadmap | Role comparison + 12-month study plan with monthly projects |

## Files

| File | Purpose |
|---|---|
| `index.html` | Complete single-page site (HTML + CSS + minimal JS) |
| `portrait.jpg` | Author photo · same as the other two pages |

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy to Vercel — separate project

This is a **third, separate** Vercel project. Same deploy flow as the others:

1. Create a new GitHub repo (e.g. `ml-mastery-tejeswar`):
   ```bash
   cd ml-mastery
   git init
   git add .
   git commit -m "feat: ML mastery curriculum"
   git branch -M main
   git remote add origin https://github.com/<your-username>/ml-mastery-tejeswar.git
   git push -u origin main
   ```
2. Go to **vercel.com/new** → Import the new repo.
3. Click Deploy. You'll get a URL like `ml-mastery-tejeswar.vercel.app`.

All three sites can live as separate Vercel projects under the same account — all stay free, all carry your byline.

## Your three-site portfolio

| Site | Audience | Vibe |
|---|---|---|
| **Enterprise AI Architecture Handbook** | Architects, senior engineers | Editorial, cream paper, serif-led |
| **AI Ecosystem Guide** | AI engineers entering the field | Tech, dark navy, electric mint |
| **ML Mastery** | Anyone learning ML from scratch | Friendly notebook, ink blue + gold |

Each one fills a different niche — together they show you can communicate across audiences.
