# VE Logistics — Website (Draft)

Bilingual (TH/EN) lead-generation site for **VE Logistics** — a fleet platform and
freight-matching network for Thailand. The site's goal is to generate leads and
**demo bookings** from fleet operators and freight customers. EV is positioned as the
data-driven *outcome*, not the entry requirement (works with every fleet — petrol,
diesel, or electric).

## Pages

| File | Description |
|------|-------------|
| `index.html` | Design chooser — links to both options |
| `clean.html` | **Option A** — Clean & Corporate (IBM Plex, minimal, trust-first) |
| `bold.html`  | **Option B** — Bold & Branded (Chakra Petch, red-forward, high-energy) |

Both options share the same content and message; only the visual treatment differs.

## Status / notes

- **Draft for internal review.** Copy describes intended capabilities, not confirmed
  operational status.
- Metrics (150+, ~18%, 2,400+) and the dashboard preview are **mock-ups** pending
  Business Development verification (see `../05-evidence/ve-bd-questionnaire.docx`).
- The demo form is front-end only — it needs a real submission endpoint (form backend,
  CRM, or email) before going live.
- Contact details (domain, email, phone) are placeholders to be confirmed by BD.

## Run locally

Just open `index.html` in a browser — no build step, no dependencies. Fonts load from
Google Fonts (needs internet).

## Deploy (GitHub Pages)

1. Push this folder to a GitHub repo (see push plan in the delivery notes).
2. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / `root`**.
3. The site publishes at `https://<user-or-org>.github.io/<repo>/`.

## Tech

Plain static HTML/CSS/JS. No framework. Self-contained per page. Light/dark theme aware.

---
© 2026 VE Logistics · a CIG Utilities & Infrastructure initiative
