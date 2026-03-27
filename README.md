# 🏏 IPL Fantasy League 2026

A fully offline, browser-based IPL Fantasy League tracker for 12 players across all 70 IPL 2026 matches.

## Features
- **Leaderboard** — Live rankings with Total Points, Avg Points, Matches Played, and Top-3 Finishes
- **Add Score** — Enter points per player for any match; mark players as DNP (Did Not Play)
- **Match History** — Browse all scored matches with expandable scorecards
- **Persistent** — All data saved in your browser's localStorage (survives page refresh)

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it `ipl-fantasy-2026` (or anything you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the file
1. On your new repo page, click **Add file → Upload files**
2. Drag and drop `index.html` into the upload area
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repo's **Settings** tab
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose branch: **main**, folder: **/ (root)**
5. Click **Save**

### Step 4 — Access your app
- Wait ~1 minute, then visit:  
  `https://YOUR_USERNAME.github.io/ipl-fantasy-2026/`

---

## 💻 Run Locally in VS Code

1. Open the `index.html` file in VS Code
2. Install the **Live Server** extension (by Ritwick Dey)
3. Right-click `index.html` → **Open with Live Server**
4. The app opens in your browser at `http://127.0.0.1:5500`

---

## 📖 How to Use

### Adding Scores (after each IPL match)
1. Click **ADD SCORE** tab
2. Select the match from the dropdown
3. Enter points for each player
4. If a player didn't participate, check the **DNP** box
5. Click **SAVE SCORES** — scores are auto-saved to your browser

### Reading the Leaderboard
| Column | Meaning |
|---|---|
| Matches Played | e.g., `8/10` = played 8 out of 10 completed matches |
| Avg Pts | Total ÷ matches actually played |
| 🎯 Top 3 Finishes | How many times this player finished in the top 3 within a single match |
| Total | Cumulative points across all matches |

### Match History
- Click any match row to expand and see all player scores for that match
- 🥇🥈🥉 medals shown for top 3 scorers in each match
- Click 🗑 to delete scores for a match

---

## Players
Bony · Agni · Ayan Da · Joydeep · Rony · Saptarshi Da · Jitanjan · Aritree · Vicky · Ziko · Sourodip · Dipta

## Schedule
IPL 2026: 70 matches · March 28 – May 24, 2026

---

> Data is stored in your browser's `localStorage`. Clearing browser data will erase scores. For backup, open DevTools → Application → Local Storage and copy the `ipl_fantasy_2026_scores` value.
