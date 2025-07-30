# PrepMap Pro 🗺️📚  
**Turn scattered prep PDFs into a personalised study calendar — 100 % offline.**



---

## Overview
**PrepMap Pro** ingests multiple prep PDFs (coding sets, system‑design decks, behavioural guides) and auto‑generates a day‑by‑day study calendar directly in your browser.  
No server, no signup — just open `index.html` and drop your files.

---

## Key Features
- **Multi‑PDF import** (drag & drop ≤ 10 files).  
- **Skill detection & ranking** — Algorithms, Data Structures, System Design, Behavioural.  
- **Company‑aware weighting** (Google default; Amazon & Meta presets planned).  
- **Calendar generator** — spreads topics over your chosen window, exports `.ics`.  
- **JSON outline export** for future back‑end or sharing.  
- Works **100 % offline** — perfect for low‑bandwidth campuses.

---

## Tech Stack
| Layer           | Choice             | Why                             |
|-----------------|--------------------|---------------------------------|
| PDF parsing     | `pdf.js 3.11`      | Reliable, runs in browser       |
| NLP heuristic   | Regex + TF‑IDF     | Tiny footprint, < 50 ms/page    |
| Calendar export | Hand‑rolled iCal   | Zero dependencies               |
| UI              | Vanilla HTML/JS    | Runs from `file://`, no build   |

---

## Getting Started
```bash
git clone https://github.com/Vamika1615/PreMap-pro
cd PreMap-pro

# (optional) add a wide hero image
mkdir -p assets && cp ~/Pictures/hero_study.jpg assets/

# serve locally (choose one)
npx serve .                 # requires Node
# OR
python -m http.server


---



