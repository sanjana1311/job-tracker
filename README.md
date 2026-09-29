# Job Tracker

A job-search tracker that keeps your applications, networking, and rejection
insights in one place. Built by describing it to Muse, Meta's personal AI
agent — no code written by hand.

**Live demo:** https://muse.ai/s/public-job-tracker-xjxz616xgxsertxz

## What it does

- **Dashboard** — active applications, interviews, warm contacts, response
  rate, and what needs attention next
- **Applications** — every opportunity with its stage and next move:
  Saved → Applied → Screen → Interview → Offer (or Rejected / Withdrawn)
- **Networking** — turn names into conversations: track contacts from
  "to contact" through "referral"
- **Rejection insights** — log outcomes, spot patterns by stage and reason,
  and change the next attempt
- **Import / export** — bring applications in from CSV, download a backup of
  your workspace

Your data stays in your browser session — download a backup before closing
the tab, then import it next time.

## Install

No dependencies, no build step.

```bash
git clone https://github.com/sanjana1311/job-tracker.git
cd job-tracker
```

## Run

**Option 1 — live demo (nothing to install):**

https://sanjana1311.github.io/job-tracker/

**Option 2 — open the file:**

Open `index.html` in any browser. Double-clicking it works.

**Option 3 — local server (optional):**

```bash
python3 -m http.server 8000
```

then visit http://localhost:8000 in your browser.

## License

MIT © Sanjana Ravikumar.
