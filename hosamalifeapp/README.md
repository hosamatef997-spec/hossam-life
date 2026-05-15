# 🌙 حسام ليف · Hossam Life

> Daily personal dashboard — devotions, habits, finance, photography, life.

A beautifully crafted personal PWA dashboard built with care for Hossam.

🌐 **Live:** [hosamatef997.github.io/hossam-life](https://hosamatef997.github.io/hossam-life/)

---

## ✨ Features

### 🕌 Devotions & Faith
- Daily morning devotions tracker (atef, deceased, adhkar)
- Live prayer times for Dubai (via Aladhan API)
- Friday card with weekly tradition checklist
- Devotion streak with milestone celebrations (7, 14, 30, 60+ days)

### 💰 Finance Hub
- Real-time balance tracking with inline editing
- Multi-currency support (AED ↔ EGP)
- Expense categories with icons
- Monthly obligations management
- Two apartments installment countdown
- Smart spending alerts (2x daily average trigger)

### ✅ Productivity
- Daily tasks with quick add
- Habits tracker with streak counters
- Recurring daily routines
- Watch list (series + movies)

### 📸 Photography
- Photo of the day calendar
- Daily shoot challenges
- Mood board for inspiration
- Instagram post tracker

### 🤖 Smart Telegram Bot
- Send voice notes — auto-transcribed by Gemini in Arabic
- Send text — parsed by Claude into structured items
- 6 query commands: `/balance`, `/today`, `/tasks`, `/streak`, `/expenses`, `/help`
- Natural Arabic queries: "ايه فلوسي؟", "ملخص اليوم"
- Proactive notifications: morning digest, Friday reminder, spending alerts, end-of-day digest, photo reminder, monthly installment alerts

### 📊 AI Weekly Report
- Every Saturday 7 AM Dubai time
- Claude Sonnet 4.6 analyzes your week
- Personalized insights, wins, watch areas, and weekly goals

### 🔐 Privacy & Sync
- Google sign-in via Firebase Auth
- Cloud sync via Firestore (encrypted at rest)
- Photos stored on Cloudinary (your unsigned preset)
- PIN lock for sensitive data
- LocalStorage as source of truth, cloud for cross-device sync

---

## 🏗️ Tech Stack

- **Frontend:** Vanilla HTML + Alpine.js v3 + Tailwind (CDN)
- **Auth:** Firebase Auth (Google OAuth)
- **Database:** Firestore (per-user document)
- **Storage:** Cloudinary (unsigned upload)
- **Automation:** n8n workflows on n8n.cloud
- **AI:**
  - Claude Haiku 4.5 (text parsing)
  - Claude Sonnet 4.6 (weekly insights)
  - Gemini 2.5 Flash (voice transcription)
- **Drag & drop:** SortableJS
- **Bot:** Telegram (@mminteriors_design_bot)

---

## 📱 PWA Install

1. Open the site on iPhone Safari or Android Chrome
2. Share → Add to Home Screen
3. Use as a standalone app

---

## 🚀 Version History

- **v2.3** — Unified Finance Hub + Weekly AI Report
- **v2.2** — Smart Inbox Bot (voice + text + commands)
- **v2.1** — Telegram notifications + smart triggers
- **v2.0** — Mobile UX overhaul, collapsible widgets, long-press edit
- **v1.7** — Drag & drop reorder + PIN lock
- **v1.6** — Photography widgets
- **v1.0** — Initial release

---

## 📜 License

Built with care for Hossam — personal use.

---

*Made by Claude + Hossam · Powered by automation + intention*
