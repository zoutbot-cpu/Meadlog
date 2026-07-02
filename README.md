# Mead Log

A simple, self-contained mead-brewing logbook. Track recipes, starting gravity, ingredients, and dated tasting/progress notes for every batch — no backend required.

**Live page:** https://zoutbot-cpu.github.io/Meadlog/
**Privacy Policy:** https://zoutbot-cpu.github.io/Meadlog/privacy.html
[Preview|meadlog-preview.png]
## Features

- Log each batch's recipe, starting gravity, and ingredient list with amounts
- Add dated notes over time (gravity checks, racking, tasting notes)
- ABV calculator from OG/FG, plus a projected-ABV estimate fitted from your gravity readings while fermentation is still in progress
- Data saves automatically to your browser
- Optional Google Drive sync (via the `drive.appdata` scope — a narrow, non-sensitive permission limited to a single hidden app-specific folder) to keep your data in sync across devices

## Setup

1. Open the live page above.
2. (Optional) Click **Connect Drive** to sync your data to Google Drive, so it follows you across devices/browsers instead of staying local to one browser.

## Notes

- This is a static HTML/JS page — no server, no database.
- Without Google Drive connected, data is stored in your browser's local storage and is tied to that specific browser.
- The Google OAuth client is going through Google's brand verification process so the "unverified app" warning can be removed for anyone using Drive sync.
