---
version: alpha
name: Roanoke Crawl Space Pros — Appalachian Heritage
description: Warm, grounded design system for a local home-service brand. Pine + terracotta clay on warm paper. Feels trustworthy, regional, and human.
colors:
  paper: "#FCFAF5"
  cream: "#F5F2EC"
  sand: "#EDE8DE"
  ink: "#3D382F"
  ink-soft: "#6B645A"
  line: "#DED9CE"
  pine: "#3D6B4F"
  pine-d: "#2F4D39"
  pine-ink: "#E8EFE5"
  clay: "#C45A33"
  clay-d: "#B04A2A"
  clay-soft: "#D9896A"
  amber: "#E6B94A"
  ember: "#BF3A1A"
typography:
  display:
    fontFamily: "Bricolage Grotesque"
    fontWeight: 700
    letterSpacing: "-0.02em"
    lineHeight: 1.05
  body:
    fontFamily: "Hanken Grotesk"
    fontWeight: 400
    lineHeight: 1.65
  h1:
    fontFamily: "Bricolage Grotesque"
    fontSize: "clamp(2.6rem,1.9rem + 3.6vw,4.6rem)"
    fontWeight: 800
    lineHeight: 1.02
  h2:
    fontFamily: "Bricolage Grotesque"
    fontSize: "clamp(1.75rem,1.45rem + 1.4vw,2.5rem)"
    fontWeight: 700
  body-md:
    fontFamily: "Hanken Grotesk"
    fontSize: "clamp(1rem,.97rem + .15vw,1.075rem)"
    lineHeight: 1.65
rounded:
  sm: 11px
  md: 14px
  lg: 22px
spacing:
  pad-section: "clamp(48px,6vw,96px)"
  wrap-max: 1140px
  gap-card: 20px
components:
  button-primary:
    backgroundColor: "{colors.clay}"
    textColor: "#FFFFFF"
    rounded: 12px
    padding: "15px 26px"
  button-primary-hover:
    backgroundColor: "{colors.clay-d}"
    textColor: "#FFFFFF"
  button-secondary:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.pine}"
    rounded: 12px
    padding: "15px 26px"
  button-secondary-hover:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.pine}"
  card:
    backgroundColor: "{colors.paper}"
    rounded: "{rounded.md}"
    padding: 26px
  badge:
    backgroundColor: "oklch(100% 0 0 / .08)"
    textColor: "#FFFFFF"
    rounded: 999px
    padding: "7px 13px"
  form-input:
    backgroundColor: "{colors.cream}"
    rounded: 11px
    padding: "13px 14px"
---

## Overview

Appalachian Heritage — a warm, regional design system for a crawl-space encapsulation service in Virginia's Blue Ridge. The palette draws from the landscape: deep forest pine, terracotta clay soil, and warm paper tones reminiscent of craft millwork. Every element signals trust, permanence, and local authenticity. Nothing feels like a SaaS landing page.

## Colors

- **Paper (#FCFAF5):** Near-white warm surface for cards, forms, and content blocks.
- **Cream (#F5F2EC):** Page background — warmer than pure white, reduces eye strain.
- **Pine (#3D6B4F):** Deep forest green for dark surfaces, hero backgrounds, and brand identity.
- **Pine Dark (#2F4D39):** Darker pine for header bars, footers, and maximum contrast on light text.
- **Clay (#C45A33):** Terracotta CTA color — the sole high-emphasis action color. Used for primary buttons, phone CTAs, and link accents.
- **Ink (#3D382F):** Warm espresso for body text — dark enough for readability, warm enough to feel human.
- **Ember (#BF3A1A):** Emergency/urgent messaging bar. Used sparingly.

## Typography

**Bricolage Grotesque** for display: headings, hero text, brand wordmark. 800-weight for H1, 700 for H2–H3. Tight line-height (1.02–1.05), negative letter-spacing. Feels hand-crafted and regional.

**Hanken Grotesk** for body and UI: functional sans-serif with warmth. 1.65 line-height for readability. System font stack fallback.

No more than two type families on any page. Use the display font only where impact is needed.

## Layout & Spacing

- Content wrapper max-width: 1140px
- Section padding: clamp(48px, 6vw, 96px) — generous on desktop, restrained on mobile
- Card grid gaps: 20px
- All sections use 22px–32px side padding (mobile/desktop)
- Mobile-first breakpoints at 680px (grid), 760px (width), 960px (nav)

## Components

`button-primary`: Clay background, white text, 12px rounding. The primary action on every page — "Get Free Estimate," "Call Now," form submits.

`button-secondary`: Paper/white background, pine text. For secondary actions, "Learn More" links.

`card`: White paper surface, 14px rounding, subtle shadow. Used for service cards, testimonial cards, FAQ items.

`badge`: Semi-transparent light background, white text, pill-rounded. Used in hero for trust markers (Licensed & Insured, Free Estimates).

## Do's and Don'ts

✅ Do use clay ONLY for primary CTAs — never for decorative elements.
✅ Do keep content max-width to 68ch for paragraphs.
✅ Do use the eyebrow pattern (small uppercase label with clay dash) to introduce sections.
✅ Do front-load answers — start every section with the key fact, then explain.

❌ Don't introduce a third brand color for CTAs. Clay is the only high-emphasis action color.
❌ Don't use pure white (#FFFFFF) as a background — use Paper or Cream.
❌ Don't use more than one H1 per page.
❌ Don't center-align paragraphs — left-align only.
