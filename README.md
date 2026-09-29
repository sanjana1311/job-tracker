# Job Tracker

A job-search tracker that keeps your applications, networking, and rejection
insights in one place. Built by describing it to Muse, Meta's personal AI
agent — no code written by hand.

**Live demo:** https://sanjana1311.github.io/job-tracker/

Also demoed on Muse: https://muse.ai/s/public-job-tracker-xjxz616xgxsertxz

## What it does

- **Applications** — every opportunity with its stage and next move:
  Saved → Applied → Screen → Interview → Offer (or Rejected / Withdrawn).
  The summary strip shows Active, Interviews, Referrals (applications that
  came through a referral), and Next Move (what needs attention). Search,
  filter by stage, and add applications with **+ Add application**; edit any
  card to fix details. Overdue follow-ups get a "Follow up overdue" pill.
- **H-1B sponsorship flag** — each application carries a sponsorship status
  (Sponsors H-1B / Doesn't sponsor / Unknown), filterable from the
  Applications filters. A built-in table of 25+ well-known companies
  (Anthropic, OpenAI, Meta, Google-family employers, and more) pre-fills the
  flag when you enter a matching company — you can always override it.
- **Network** — track recruiters, referrals, alumni, and team members. Add
  contacts manually, or use **Import from LinkedIn**: upload the
  `Connections.csv` you download from LinkedIn (Settings → Data Privacy →
  Get a copy of your data → Connections). It previews every parsed contact,
  skips duplicates, and imports only on your confirm.
- **Insights** — rejection analytics: log outcomes, spot patterns by stage
  and reason, and change the next attempt.
- **Import / export** — bring applications in from CSV, export them back out,
  or download a full JSON backup of your workspace.
- **Light / dark mode** — toggle in the header; your choice is remembered.

Your data stays in your browser session — download a backup before closing
the tab, then import it next time.

## Install

No dependencies, no build step. It's a single `index.html`.

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
