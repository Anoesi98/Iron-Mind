# 🛡️ IRONMIND — Recovery Command Center

A personal protocol dashboard for anxiety and panic attack recovery. Evidence-based supplements, breathwork, diet, and lifestyle routines — built for daily use.

![IRONMIND](https://img.shields.io/badge/IRONMIND-Recovery%20Protocol-d9a032?style=for-the-badge&labelColor=0b0d12)

---

## What It Is

IRONMIND is a single-page web app that consolidates a complete recovery protocol into a mobile-first tactical dashboard. It was designed for someone recovering from panic attacks following SSRI discontinuation, but the underlying research applies broadly to anxiety management and nervous system regulation.

The stack is built around **AG1** (morning foundation) and **AGZ** (evening recovery), with targeted supplements, daily checklists, lifestyle protocols, and dietary guidance — all backed by clinical research.

---

## Features

- **Daily Checklist** — Morning, midday, evening, and bedtime tasks with progress tracking. Saves locally and resets each day.
- **Supplement Stack** — Full protocol with AG1/AGZ as the base. Expandable cards with dosage, timing, mechanism, and evidence ratings. Filter by Owned, Core, Optional, Replaced, or Not Purchased.
- **Replacement Map** — Collapsible dropdowns showing exactly what AG1 and AGZ replace from the expanded protocol.
- **Daily Routine** — 9 lifestyle protocols (exercise, breathwork, sleep, sunlight, cold exposure, vagus nerve, meditation, journaling, social connection).
- **Diet Guide** — Meal structure rules, daily non-negotiables, weekly targets, and beverages.
- **Avoid List** — Severity-coded substances and triggers to eliminate (Critical / High / Moderate).
- **Science Section** — The neuroscience of what happened (SSRI discontinuation → cannabis → panic), recovery timeline, and medication decision framework.
- **Emergency Panic Protocol** — Always-accessible 6-step immediate response (physiological sigh, L-theanine, cold water, grounding, observation, blood sugar).

## Design

- Dark mode, mobile-first
- Living neural particle background (canvas animation)
- Amber ripple effects on every tap
- Staggered list entry animations
- Smooth expand/collapse without page flicker
- Inline SVG favicon (amber shield + lightning bolt)
- Open Graph meta tags for link previews

---

## Deployment

This is a **single HTML file** — no build step, no dependencies, no framework.

### GitHub Pages

1. Push `index.html` to a repo
2. Go to **Settings → Pages → Source: main branch**
3. Your site is live

### Vercel / Netlify

Drag the file (or a folder containing it) into the deploy interface. Done.

### Local

Open `index.html` in any browser. Everything works offline except the Google Fonts import.

---

## File Structure

```
/
├── index.html          ← The entire app (single file, ~30KB gzipped)
└── README.md
```

No `favicon.ico` needed — the favicon is embedded as an inline SVG data URI inside the HTML.

---

## Tech

- Vanilla JavaScript (no React, no framework)
- CSS custom properties for theming
- Canvas API for neural particle background
- LocalStorage for daily checklist persistence
- Google Fonts (Bebas Neue, Barlow, Barlow Condensed)

---

## Based On

The supplement protocol, diet plan, and lifestyle interventions are synthesized from clinical research including:

- Myo-inositol for panic disorder (double-blind crossover trials)
- Stanford cyclic sighing RCT for anxiety
- Mediterranean diet meta-analyses for mental health
- Resistance training effect sizes for anxiety reduction
- Post-SSRI neuroplasticity and serotonin receptor recovery
- Gut-brain axis psychobiotic research (CEREBIOME strains)
- AG1 and AGZ ingredient profiles mapped against the expanded protocol

---

## Disclaimer

This is a personal tool, not medical advice. Always consult a healthcare professional before starting any supplement protocol or making changes to medication. The information here is for educational purposes based on published research.

---

Built with 🛡️ by Anthony
