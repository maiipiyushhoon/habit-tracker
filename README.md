# habit-tracker
It's a habit tracker for daily habits 

<div align="center">

# 🎯 Getting 1% Better Each Day
### Oct 2026 — 31-Day Interactive Habit & Sleep Dashboard

[![Live Demo](https://img.shields.io/badge/🚀_Live_App-GitHub_Pages-10b981?style=for-the-badge)]
[![Mobile Optimized](https://img.shields.io/badge/📱_UI-Mobile_First_PWA-0ea5e9?style=for-the-badge)](#)
[![Zero Dependencies](https://img.shields.io/badge/⚡_Stack-Vanilla_JS_%2B_Tailwind-f59e0b?style=for-the-badge)](#)
[![Notion Ready](https://img.shields.io/badge/📓_Notion-Embed_Ready-ffffff?style=for-the-badge&logo=notion&logoColor=black)](#)

<p align="center">
  A lightweight, offline-capable mobile web application that digitizes my physical <b>31-Day Habit & Sleep Tracker</b> into an interactive analytics dashboard with real-time SVG charts, a 31-day matrix grid, and persistent local storage.
</p>

[🔗 **Launch Live Dashboard**] · [📲 **Install on Phone**](#-install-as-a-mobile-app-pwa) · [📓 **Embed in Notion**](#-embed-inside-notion-mobile)

</div>

---

## ✨ Key Features

* **📱 Daily Mobile Logger (Tab 1):**
  * Swipeable **Day 1 – Day 31** pill selector with live daily point totals (`X / 12 pts`).
  * One-tap **Done (`✓`)** and **Missed (`✗`)** toggles for all 12 daily habits.
  * Instant **Sleep Hours** selector matching the physical paper scale (`0 hr` to `9 hrs`).
  * Animated SVG completion ring gauge + live dual sparkline (Daily Points vs. Sleep Curve).
* **🗓️ 31-Day Paper Sheet Matrix (Tab 2):**
  * Full 31-column interactive grid with a sticky left column for smooth horizontal scrolling on mobile screens.
  * Tap any cell to cycle states (`✓` → `✗` → `blank`) and automatically recalculate the **Total Points** row.
* **📈 Connected Sleep Line Graph (Tab 3):**
  * Custom SVG line-and-dot graph replicating the physical sleep tracker (`0 hr` top row, `9 hrs → 5 hrs` scale).
  * Interactive dot matrix below the chart—tap any coordinate to re-plot sleep hours and redraw the curve in real time.
* **🏆 Evaluation & Consistency Analytics (Tab 4):**
  * **Daily Total Points Bar & Trend Line Chart** across all 31 days.
  * **Habit Consistency Breakdown** ranking all 12 habits by completion percentage (`✓` vs `✗`).
* **💾 100% Client-Side Persistence:**
  * Powered by browser `localStorage`—all checkmarks, sleep logs, and monthly notes save automatically without a backend database.
  * Includes a one-tap **Reset Data** button to restore the baseline Oct 2026 sheet data.

---

## 📋 The 12 Tracked Habits & Rules

| # | Habit / Rule | Category | Daily Target |
| :-: | :--- | :--- | :---: |
| **1** | `6:00` | ⏰ Morning Routine | Wake up on time |
| **2** | `workout/stretch` | 💪 Fitness | Physical training / mobility |
| **3** | `3 hr Deep Work` | 💻 Focus & Code | Uninterrupted deep work block |
| **4** | `Soft skills` | 🗣️ Communication | Practice & articulation |
| **5** | `meditate` | 🧘 Mindfulness | Daily mindfulness session |
| **6** | `3/4 L water` | 💧 Hydration | Hit daily hydration target |
| **7** | `one topic` | 📚 Learning | Master one core concept daily |
| **8** | `journal` | ✍️ Reflection | Daily log & mental clarity |
| **9** | `read` | 📖 Reading | Daily reading habit |
| **10** | `feynman` | 🧠 Active Recall | Teach/explain a learned concept |
| **11** | `music` | 🎧 Creative / Mind | Music session |
| **12** | `walk` | 🚶 Movement | Daily outdoor walk |

---

## 📊 Live Data Preview (Days 1–13 Baseline)

*(GitHub automatically renders these Mermaid charts from the repository markdown)*

### 💤 Sleep Curve (0 – 9 hrs Scale)
```mermaid
xychart-beta
    title "Oct 2026 Sleep Tracker (Days 1 - 13)"
    x-axis ["D1", "D2", "D3", "D4", "D5", "D6", "D7", "D8", "D9", "D10", "D11", "D12", "D13"]
    y-axis "Sleep Hours" 0 --> 9
    line [6, 7, 8, 7, 5, 6, 5, 7, 8, 8, 9, 8, 0]
