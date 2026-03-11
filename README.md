<div align="center">

<img width="512" height="512" alt="icon" src="https://github.com/user-attachments/assets/f65cccdf-bc3c-4cb9-8dcb-930e2cb70909" />

# BaselineApp

### Professional Baseball Development Tracker for Android

**Track. Analyze. Develop.**

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android)](https://play.google.com/store)
[![Price](https://img.shields.io/badge/Price-%2410.00-blue?style=flat-square)](https://play.google.com/store)
[![Privacy](https://img.shields.io/badge/Data-100%25%20Local-success?style=flat-square)](PRIVACY_POLICY.md)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)]()

</div>

---

## What is BaselineApp?

BaselineApp is a **professional-grade baseball development tracker** built for players, coaches, and parents who are serious about measurable improvement. Whether you're tracking bat speed with a Blast sensor, logging pitching velocity, or monitoring athletic development, BaselineApp gives you a complete picture of an athlete's progress — all stored privately on your device, with zero subscriptions and zero data collection.

> *Your data belongs to you. It never leaves your device.*

---

## ✨ Features

### 📊 Dashboard
- **Overall progress score** — a single percentage showing how close the athlete is to all their goals combined
- **Configurable top-3 hero metrics** — pin any 3 metrics to the top of the dashboard for at-a-glance monitoring
- **Radar chart (Player Profile)** — a fully configurable spider chart showing up to 10 metrics at once, visualizing strengths and weaknesses instantly
- **Metric cards by category** — Batting, Pitching, and Athletic metrics each displayed with current value, goal, and % to goal ring
- **Goal completion rings** — a grid of circular progress indicators for every tracked metric
- **Lateral imbalance warning** — automatic alert if left/right lateral bound difference exceeds 10%, flagging potential injury risk

### 📈 Trends
- **Per-metric trend charts** — line graphs showing progress over time for every metric
- **Session history visualization** — see exactly how each metric moves across all logged sessions

### 📋 Sessions
- **Full session log** — browse all past sessions with date, swing count, and key stats
- **Expand any session** — drill into individual swing rows, pitch rows, and athletic measurements
- **Edit or delete sessions** — full control over your historical data

### ⚾ Batting Metrics (Blast Motion Sensor)
- **Bat Speed** (mph) — speed of the barrel at contact
- **Attack Angle** (°) — swing plane with target band (5°–15°) and color-coded feedback
- **Time to Contact** (sec) — how quickly the hands deliver the barrel
- **Peak Hand Speed** (mph) — maximum hand velocity during the swing
- **Rotational Acceleration** (G) — explosive power from rotation start to peak speed

### 🎯 Pitching Metrics
- **4-Seam Fastball Command** (%) — strike percentage auto-calculated from logged pitches
- **Fastball Velo Top 10** (mph) — average of the 10 fastest pitches, tracking velocity ceiling over time

### 🏋️ Athletic Metrics
- **Lateral Bound L & R** (in) — lateral explosiveness measured per rep, best attempt saved
- **Body Weight** (lbs) — baseline mass tracking
- **Deadlift** (lbs) — posterior chain strength with 1.5× bodyweight target
- **Relative Power Efficiency (RPE)** — composite score: `(Deadlift × Bat Speed) ÷ Body Weight`

### 🛠️ Custom Metrics
- **Add any metric** — name, unit, category, goal, and description are all customizable
- **Three tracking types:**
  - *Per swing* — logged in swing rows, top-10 average saved (Batting)
  - *Per pitch* — logged alongside each pitch, top-10 average saved (Pitching)
  - *Per rep* — log multiple attempts, best result saved (Athletic)
  - *Once per session* — single value entry for any category
- **Auto-populates Glossary** — every custom metric automatically appears with its description
- **Appears everywhere** — Dashboard cards, Trends charts, Goals, Glossary, and Radar chart

### 🎯 Goals System
- **Set individual goals** for every metric — built-in and custom
- **Smart goal math** — handles higher-is-better, lower-is-better, and target-band metrics
- **Goals persist per user** — each athlete has their own goal profile

### 👤 Multi-User Profiles
- **Multiple athlete accounts** on one device — perfect for coaches tracking several players
- **Per-user data isolation** — sessions, goals, settings, and profile photos are completely separate
- **Profile photos** — tap the avatar in the menu to set a photo from your gallery
- **Secure authentication** — PBKDF2 password hashing with 100,000 iterations and random salt

### 🔒 Privacy & Security
- **100% local storage** — all data lives in the app's private IndexedDB, never transmitted anywhere
- **No internet required** — the app works entirely offline
- **No ads, no subscriptions, no tracking** — one-time purchase, forever yours
- **COPPA compliant** — no external data collection of any kind
- **Delete Account** — permanently wipes all data for a user with one tap

---

## 📱 Screenshots

> *(Screenshots coming soon)*

---

## 🏗️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 18 + Vite |
| Styling | Tailwind CSS + custom dark theme |
| Charts | Recharts (line charts + radar) |
| Database | IndexedDB (fully local, no server) |
| Auth | PBKDF2 / Web Crypto API |
| Android | WebView wrapper (Java, minSdk 24) |
| Fonts | Oswald + Barlow |

---

## 🚀 Getting Started (Developers)

### Prerequisites
- Node.js 18+
- Android Studio (for Android build)
- Java 17

### Build

```bash
# 1. Install dependencies
cd frontend
npm install

# 2. Build React app
npm run build

# 3. Copy to Android assets
xcopy /E /I /Y dist "..\app\src\main\assets\www"

# 4. Open BaselineApp-Android/ in Android Studio
# 5. File → Sync Project with Gradle Files
# 6. Run with the green triangle
```

### Gradle Requirements
- Gradle 8.11
- compileSdk 34 / targetSdk 34
- minSdk 24 (Android 7.0+)
- Java 17

---

## 📄 Privacy Policy

BaselineApp collects no personal data. All data is stored locally on your device and is never transmitted to any server or third party.

[Read the full Privacy Policy](PRIVACY_POLICY.md)

**Contact:** baselineapphq@gmail.com

---

## 📦 Availability

BaselineApp is available on the **Google Play Store** for a one-time purchase of **$9.99**.

No subscriptions. No in-app purchases. No ads. Ever.

---

<div align="center">

*Built for athletes who take development seriously.*

**⚾ BaselineApp — Track. Analyze. Develop.**

</div>
