# 🎯 Mock Lens

**Mock Lens** is a lightweight, offline-first mock test analyzer, weak-topic tracker, and spaced-revision planner built specifically for **SSC (CGL, CHSL, GD)** and **Railway (RRB NTPC, Group D, ALP)** aspirants.

🔗 **Live App:** `https://YOUR_USERNAME.github.io/mock-lens/`

---

## ✨ Key Features

- **📊 Complete Mock & Sectional Analysis:** Track raw scores, accuracy, attempt rate, negative mark loss, shift difficulty, percentile, and cutoff clearance across full-length and sectional tests.
- **🏆 Personal Mock Challenges:** Set custom or preset mock sprints (e.g., *Weekly Target: 10 Mocks*) with live progress bars, countdowns, and required daily pace tracking.
- **⚡ Testbook & Answer Key AI Auto-Fill (BYOK):** Paste raw Testbook scorecard text, official answer key summaries, or upload result screenshots to auto-populate section and topic scores using your own free Google Gemini API key.
- **🎯 Weak-Topic Ranking & Spaced Revision:** Automatically prioritizes red/amber topics based on exam weightage and recent accuracy, generating 7/14/30-day study plans with spaced recall (`1, 3, 7, 14, 30 days`).
- **🗂️ Mistake Notebook & Flashcard Quiz:** Log wrong questions with shortcuts and practice them in an active-recall flashcard quiz mode (2 consecutive correct recalls mark a question as *Mastered*).
- **⏱️ Built-in Sectional Timer & Consistency Tracker:** Quick countdown timer (`15m / 25m`) with audio alert and a 14-day study consistency heatmap.
- **🔒 100% Private & Offline-Ready:** Runs as a single zero-dependency HTML file. All data stays locally in your browser (`localStorage`) with one-click JSON backup/restore and printable PDF analysis sheets.

---

## 🚀 How to Use

1. Open the live link in Chrome/Edge on your laptop or phone.
2. *(Optional)* Tap **⋮ → Add to Home screen** on mobile to install it as an offline app.
3. Click **Clear examples** on the Home banner to remove sample mocks.
4. Go to **Setup & backup** to select your target exam, set your target score %, and add your free [Google AI Studio](https://aistudio.google.com/apikey) Gemini API key if you want AI coaching and scorecard auto-fill.
5. Export a JSON backup weekly from **Setup & backup** to keep your records safe across devices.

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3 (Bento + Glassmorphic UI, Dark/Light themes), Vanilla JavaScript (ES5/ES6 compatible)
- **Storage & Offline:** Browser `localStorage` + Service Worker caching
- **AI Integration:** Google Gemini REST API (Client-side BYOK)
