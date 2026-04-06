# SAPD Sergeant Promotional Exam – Adaptive Practice Quiz

A single-file web app for studying the SAPD SGT promotional exam. No installs, no build tools — just open `index.html` in a browser or deploy to GitHub Pages.

---

## What's Covered


The quiz mirrors the actual exam breakdown across all four sections:

| Section | Questions | Topics |
|---|---|---|
| General Manual (GM) | 50 | Procedures 200, 303, 306, 309, 310, 314, 315, 318, 324, 330, 401, 403, 410, 501, 502, 601, 604, 609, 619, 620 |
| Penal Code (PC) | ~50 | Chapters 9, 19, 20, 20A, 21, 22, 25, 28, 29, 30, 31, 38, 39, 42, 49 |
| Textbook (TB) | ~42 | Chapters 1, 2, 4, 6, 7, 8, 10, 13 — *Police Administration*, 10th Ed. (Swanson et al.) |
| CBA | 20 | Articles 28–37 (COSA/SAPOA Agreement, May 2022–Sept 2026) |

---

## How It Works

- **Spaced repetition** — questions you miss come back more often; correct answers cycle out faster
- **Progress is saved** — localStorage keeps your stats between sessions, even after closing the browser
- **Filter by section** — drill just GM, PC, Textbook, or CBA, or mix them all
- **Configurable session length** — 10, 20, 50, or all questions per session
- **Study references** — every question shows exactly which procedure, section, or chapter to review if you get it wrong
- **Progress screen** — tracks accuracy by section and ranks your weakest topics

---

## Deploying to GitHub Pages

1. Upload `index.html` and this `README.md` to a GitHub repository
2. Go to **Settings → Pages**
3. Under *Source*, select your main branch and click **Save**
4. GitHub will provide a link (e.g. `https://yourusername.github.io/repo-name`) — bookmark it on your phone or desktop

---

## Exam Details

- **Date:** April 23, 2026 at 0900
- **Location:** Henry B. Gonzalez Convention Center – Hemisfair Ballroom
- **Format:** 100 multiple-choice questions (50 GM · 10 PC · 20 Textbook · 20 CBA)
