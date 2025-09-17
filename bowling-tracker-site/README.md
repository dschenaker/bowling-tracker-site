# Bowling League Tracker • Big Ben (44 ft)

This repo contains a simple, static site and two assets:
- `assets/BigBen-LanePlan.png` — your lane play visual
- `sheets/League Night Entry (import to your tracker).xlsx` — per‑game auto‑scoring sheet

## Quick start (VS Code + GitHub Pages)
1. **Unzip** this package into a new folder.
2. Open the folder in **VS Code**. Install the “Live Server” extension (optional).
3. Open `index.html` and right‑click → **Open with Live Server** to preview locally.
4. Create a new repo on GitHub, commit all files, and push.
5. In the repo: **Settings → Pages → Source: `main` / `/ (root)`**. Save.
6. Your site will be live at: `https://<your-username>.github.io/<repo-name>/`

## Using the entry sheet
- In Google Sheets, open your master tracker.
- **File → Import → Upload** the entry workbook → **Insert new sheet(s)**.
- On the **League Night Entry** sheet, enter date (B3) and score your games (X, /, -, or 0–9).
- Copy the small summary block (Date, G1, G2, G3, High, Low, Series) into the next empty row on **Main**.

## Notes
- This is a static site (no server), safe to publish on GitHub Pages.
- You can customize styling by editing `index.html`.
- MIT licensed — make it yours.
