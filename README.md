# PrepMap Pro 🗺️📚  
**Turn scattered prep PDFs into a personalised study calendar — 100 % offline.**

---

## ✨ What it does
1. **Import multiple PDFs** (placement guides, coding sets, system‑design decks).  
2. **Auto‑detect skills** – Algorithms, Data Structures, System Design, Behavioural.  
3. **Rank sections** by TF‑IDF × company weight profile (Google default).  
4. **Generate a day‑by‑day schedule** (2 h coding • 1 h design • 30 m behavioural).  
5. **Export:**  
   * 📅 **prepmap_plan.ics** – ready for Google / Outlook Calendar  
   * 📄 JSON outline – share or feed into a back‑end later  

_All processing stays in your browser; no file ever leaves your laptop._

---

## 🏁 Quick start

```bash
git clone https://github.com/yourname/prepmap-pro
cd prepmap-pro

# add a wide hero image:
mkdir -p assets && cp ~/Pictures/hero_study.jpg assets/

# serve locally (choose one)
npx serve .          # simple static server
# OR
python -m http.server
