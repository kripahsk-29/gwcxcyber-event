# Escape the Bug — Halloween Games

Two Halloween-themed browser games for **Escape the Bug**, the Lehigh Girls Who Code x
Lehigh Cybersecurity Club event (Oct 14). Each is a single `.html` file — no install,
no build step, no server, and no hosting platform (Vercel, Netlify, etc.) required or
intended. They're built to run **entirely on their own, offline, on one laptop.**

## How to run them (at the event or anywhere else)

1. Download or `git clone` this repo.
2. Double-click either file:
   - `phish-or-treat.html` — a phishing-email detection game
   - `bug-hunt.html` — a pseudocode debugging game
3. It opens directly in your default browser (Chrome, Safari, Firefox, Edge). That's it.

No `npm install`, no dev server, no internet connection needed once the file is on the
laptop — all HTML, CSS, and JavaScript live in that one file. For the event, click the
**⛶ Fullscreen** button on each game's start screen.

## Each game at a glance

- Team enters a name on the start screen, then plays a 10-minute timed round.
- Score, hints, and a "secret escape code" are shown on the end screen (ties into the
  larger Escape the Bug event).
- Press **Shift+A** at any time to open a hidden facilitator answer key.
- Click **Reset for Next Team** on the end screen to hand the laptop to the next group.

## Editing content

Both files are intentionally simple, single-file, and commented for beginner JS editors:

- `phish-or-treat.html` — edit the `EMAILS` array near the top of the `<script>` block.
- `bug-hunt.html` — edit the `LEVELS` array near the top of the `<script>` block.

Open the file in any text editor, change the text inside an existing `{ ... }` entry, or
copy one to add a new email/level. No other code changes are needed.
