# GymSync — Couples Workout Planner

A drag-and-drop weekly workout planner built for two (or more). Plan your gym week side by side, track the weights you lift, and build a streak with a GitHub-style habit heatmap — all in a single HTML file with no backend required.

---

## Features

### 📅 Weekly Kanban Board
- Days run vertically, each person gets their own column side by side
- Drag an **exercise** from the library to any day cell to schedule it
- Drag an entire **category** (e.g. Legs, Push, Pull) to fill a day with all its exercises at once
- Drag scheduled cards **between cells** to reschedule
- Navigate **between weeks** using the `←` `→` arrows — each week's plan is saved independently

### 👥 Multi-Person Support
- Starts with two users (You & GF) — add up to **6 people**
- Each person gets a unique colour that follows their cards across the board
- Weights are tracked **per person per exercise** — no cross-contamination

### 🏋️ Exercise Library
- 7 built-in categories: **Legs, Push, Pull, Core & Abs, Triceps, Body Shaping, Cardio & Conditioning**
- Collapsible sidebar — click the **☰ / ‹** button to hide it and get more board space
- **Add your own exercises** with custom sets, muscle group, and category
- Create new categories on the fly
- Custom exercises are marked with a purple **CUSTOM** badge and can be deleted

### ⚖️ Weight Tracker
- Every exercise card has a **`+ weight`** badge
- Click it to log your weight (e.g. `60 kg`, `135 lbs`)
- Shows your last logged weight and date — so you always know where to pick up next session
- Weights persist across weeks

### 🌙 Rest Days
- **Rest all** button on any day label — marks the whole row as a rest day for everyone
- **Individual rest toggle** per person cell (hover to reveal) — useful when schedules differ
- Rest cells show a 🌙 icon and block drag-and-drop so nothing gets scheduled accidentally

### 💪 Muscle Coverage Indicator
- Appears below the board once you have exercises planned
- Shows which of the 5 muscle groups (Legs, Push, Pull, Core, Cardio) each person is covering that week
- Highlights missing groups so you can spot imbalances at a glance

### 🔥 Habit Heatmap
- GitHub-style contribution grid showing your workout history over the last 52 weeks
- Click **✓ Mark done** on any day after your workout to log it
- Cell colour intensity reflects how many exercises were done that day
- Hover any cell to see the exact date and exercise count

### ✏️ Customisable
- Click the **app title** to rename it — updates the logo letter and browser tab too
- Shared **Remarks** section for weekly notes, goals, or reminders

---

## Getting Started

No install, no dependencies, no server.

1. Download `index.html`
2. Open it in any modern browser
3. Start planning

Or visit the live site: **[your-username.github.io/gymsync](https://your-username.github.io/gymsync)**

---

## Hosting on GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages**
4. Under *Source*, select **Deploy from a branch → main → / (root)**
5. Click Save — your site will be live at `https://your-username.github.io/repo-name` within a minute

---

## Data & Privacy

All data is stored in your **browser's localStorage** — nothing is sent to any server. This means:

- ✅ Works completely offline after first load
- ✅ No account or login required
- ⚠️ Data is tied to the browser you use — clearing site data will erase it
- ⚠️ Not synced between devices (yet)

---

## Tech Stack

| | |
|---|---|
| UI | React 18 (via CDN, no build step) |
| Styling | Inline styles + plain CSS |
| Font | DM Sans (Google Fonts) |
| Storage | `localStorage` |
| Build | None — single `.html` file |

---

## Roadmap

- [ ] Weight progression chart (line graph per exercise over time)
- [ ] Week templates — save and restore a week plan in one click
- [ ] Export / print view
- [ ] Shareable link via URL-encoded state
- [ ] Per-person goal tags

---

## License

MIT — do whatever you want with it.
