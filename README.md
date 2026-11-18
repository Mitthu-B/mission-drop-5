# 🚀 Mission: Drop 5 — T-Minus Habit & Accountability Dashboard

> **No apps. No alarms. Just a NASA-style launch countdown living right on my desktop.**

## 💡 The Idea
Most weight-loss and habit plans fail because goals feel too far away and phone notifications quickly turn into background noise. I wanted a **zero-click accountability system** I couldn't ignore—so I used **Google Gemini** to reverse-engineer a 32-day "T-minus" flight plan to lose 5 lbs by **December 20**, paired with a custom desktop wallpaper and an interactive web tracker.

---

## 🛠️ How It Was Built (AI Workflow)

1. **Constraint-Driven Prompting:**
   Guided Gemini to ask only three targeted questions about my daily routine and restrict every milestone to **under 5 words** for instant scannability.
2. **Routine Calibration:**
   Anchored the 32-day timeline around real-world habits: a **6:00–6:30 AM** wake-up window, **45-minute walks on Mon/Wed/Fri**, and home-cooked staples (**eggs, chicken, and veggies**).
3. **UI-Aware Visual Generation:**
   Generated a high-resolution fall sunrise wallpaper featuring a chalkboard checklist of the biggest milestones—engineered with clean sky space at the top so desktop clocks and icons never cover the text.
4. **Interactive Web Dashboard:**
   Turned the static plan into a live single-page web app featuring a real-time countdown clock, persistent `localStorage` checkboxes, a progress bar, and a celebratory confetti burst at `TARGET`.

---

## 📅 The T-Minus Flight Plan

- **T-32 (Nov 18):** Set baseline weight today.
- **T-28 (Nov 22):** Complete first three walks.
- **T-21 (Nov 29):** Batch-cook chicken and veggies.
- **T-14 (Dec 6):** Check weight; trim snack portions.
- **T-7 (Dec 13):** Increase walking pace slightly.
- **T-3 (Dec 17):** Cut salty foods; hydrate.
- **T-1 (Dec 19):** Light dinner; sleep early.
- **TARGET (Dec 20):** Morning weigh-in; goal reached!

---

## 📂 Project Structure

```text
mission-drop-5/
├── index.html      # Interactive countdown timer, checklist, and prompt breakdown
├── wallpaper.jpg   # Custom AI-generated desktop command wallpaper
└── README.md       # Project overview and AI workflow documentation
