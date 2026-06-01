# Roanoke Crawl Space Pros — roanokecrawlspacepros.com

Static SEO site for **Niche #1** in the RANKRENT portfolio: Crawl Space Encapsulation, Roanoke VA.

## Stack
- Pure static HTML + one CSS file. No build step, no framework. <2s load target.
- Deploy: Vercel (static). Config in `vercel.json`.

## Pages
- `index.html` — Home (hero, services, why-us, FAQ, LocalBusiness schema)
- `services.html` — Services (Service schema)
- `service-area.html` — Roanoke Valley coverage
- `about.html` — About / trust
- `contact.html` — Contact + quote form

## SEO
- Per-page title/meta/canonical, single H1, OpenGraph on home
- `sitemap.xml`, `robots.txt`
- JSON-LD: LocalBusiness, Service, FAQ

## ⚠️ Before going live (placeholders to replace)
1. **Phone number** — `(540) 555-0100` / `+15405550100` is a PLACEHOLDER. Replace with the real Twilio tracking number across all files once provisioned.
2. **Form endpoint** — `https://formspree.io/f/PLACEHOLDER` needs a real Formspree (or equivalent) form ID.
3. **Business details** — review NAP, hours, and any claims (e.g. "500+ sealed", "4.9 rating") with the actual renter before publishing as fact.

## Local preview
```
cd roanoke-crawlspace-encapsulation
python3 -m http.server 8080
```
