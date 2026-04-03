# MoodFlow — Personal Mental Health Tracker

> A personal mood and wellbeing Progressive Web App (PWA) — installable on iPhone, fully private, no App Store needed.

**Live app:** https://angelikiouzounaki-oss.github.io/MoodFlow

---

## What is MoodFlow?

MoodFlow is a personal emotional health tracker built as a single HTML file that runs entirely in your browser. It can be installed on your iPhone home screen where it behaves like a native app.

- **No App Store** — install directly from Safari
- **Fully private** — all data stays on your device, nothing is sent to any server
- **Works offline** — no internet required after first load
- **Free forever** — hosted on GitHub Pages at no cost

---

## Install on iPhone

1. Open **Safari** on your iPhone and go to your app URL.
2. Tap the **Share button** (box with arrow).
3. Tap **Add to Home Screen**.
4. Tap **Add**.

MoodFlow appears as a full-screen home icon.

---

## Features

### 📱 Three pages

| Page | Description |
|------|-------------|
| **Log** | Enter daily mood, sleep, habits, CPTSD + ADHD details |
| **History** | Browse past days, edit/delete, export/backup, import |
| **Insights** | Charts + correlation analytics (sleep/mood, CPTSD, ADHD) |

---

### 📅 Date navigation

- Today / Yesterday / custom day using day controls
- All entries saved per-date
- Works for past dates (edit older days)

---

### 🧩 Log categories

#### General
- Sleep hours, sleep quality, mood (depression, irritability, anxiety, outlook)
- Productivity, motivation, loneliness, chores, hygiene, nutrition, exercise, social time, media

#### CPTSD
- Felt safe, hypervigilance, triggers, dissociation, panic attacks
- Emotional dysregulation, shame, isolation urge, racing thoughts, somatic symptoms
- Trigger log text area

#### ADHD
- Focus, distractibility, brain fog, hyperactivity, task initiation, working memory, RSD
- Sensory overload, executive function, strategies used, racing mind

---

### 🧠 Insights page

- Period tabs: **14 / 30 / 60 / 90 days**
- General charts:
  - Mood trends
  - Sleep trends
  - Habit frequency
  - Correlation: Sleep vs Mood
- CPTSD charts:
  - Symptoms
  - Trauma responses
  - Correlation: Felt Safe vs Dysregulation
- ADHD charts:
  - Executive function
  - Sensory overload
  - Correlation: Sleep vs Focus

---

### 💡 Branding + PWA ready

- In HTML head:
  - `apple-touch-icon`
  - `icon 192x192`
  - `manifest.json`
  - `theme-color`
- Allows real app icon + fullscreen behavior on iPhone home screen.

---

### 📤 Export / import

History exports:

| Option | Description |
|--------|-------------|
| All entries — CSV | Full dataset |
| Period entries — CSV | Filtered by timeframe |
| Full backup — JSON | Complete app state |
| Import backup — JSON | Restore from file (with confirm) |

---

### 🔒 Data & privacy

| Question | Answer |
|----------|--------|
| Where is data stored? | `localStorage` in browser |
| Is data sent away? | No |
| Offline support? | Yes |
| Clear cache risk? | Yes, data removed (use backup) |

---

### ⚙️ Technical stack

- **Single-HTML app** (no build/compiler)
- **Vanilla JS**
- **Chart.js** for graphs
- **localStorage** persistence
- **PWA meta tags** support
- **GitHub Pages hosting**

---

### 🧾 Contribution

1. Fork repo
2. Update code/README
3. PR with description
4. Merge after review
