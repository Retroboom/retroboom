# Claude Code Brief — retroboomgames.com

## Project Overview

Add a homepage, blog section, and shared navigation to an existing static site hosted on GitHub. The site currently has two utility pages with no homepage and no navigation connecting them.

---

## Existing Site Structure

Do not modify or break existing pages. The current pages are:

- `/` — HoF Campaign Tracker (existing, keep as-is)
- `/breakpoint-tracker` — Break Point Tracker (existing, keep as-is)

The new homepage will live at `/index.html` (replacing or wrapping the current root, depending on how the repo is structured — check before touching).

There is one existing image asset to use:
- `/hailoffirecampaigntitle.png` — the Hail of Fire title treatment. Use this in the HoF feature section on the homepage.

---

## What to Build

### 1. Shared Navigation Bar
Add to all pages (homepage, both existing utility pages, and blog).

Contents:
- Retroboom Games wordmark (links to `/`) — use Monoton font
- Games (links to games section on homepage, or a future `/games` page — use `#games` anchor for now)
- Campaign Tracker (links to `/`)
- Break Point Tracker (links to `/breakpoint-tracker`)
- Discord (placeholder link — use `#` for now, flagged as TODO)

---

### 2. Homepage (`/index.html`)

Sections in order:

#### Hero
- Headline: **Made to be Played.**
- Subheading: Tabletop games that run deep and play simple.

#### Hail of Fire Feature Section
- Game title: Hail of Fire
- Body: Company-level WWII miniatures. Fast, intuitive mechanics. Fog of war drives every decision. Ten years in development. Free to download. A regular feature at HMGS conventions, where game masters have earned more than a dozen awards running it.
- Use the existing image `/hailoffirecampaigntitle.png` in this section
- Two CTAs:
  - [Download Free] → `https://www.wargamevault.com/en/product/188181/hail-of-fire`
  - [Join the Discord] → `#` (placeholder, flagged as TODO)

#### Games Grid (id="games")
Seven cards. Hail of Fire card is the active/featured one. All others should feel "coming soon" — visually subdued (e.g. reduced opacity, muted treatment, no CTAs).

| Game | Type | One-liner |
|------|------|-----------|
| Hail of Fire | Historical WWII Minis | Company-level WWII miniatures. Fast, intuitive mechanics. Fog of war drives every decision. |
| Ashen Empires | Fantasy Minis | Steampunk fantasy warfare running on a single engine: leadership. A cascading activation system puts command and control at the heart of every battle. |
| The Damned | Co-op Minis | Simple rules, dark tone, evolving campaign. Co-op demon hunting focused on a narrative engine that tells a new story every time. |
| Full Burn | Sci-Fi Minis | Fast-play military mecha combat — cross-table dashes, fast decisions, and the kinetic flair of your favorite action games. Lock on and burn. |
| Bleeding Edge | TCG | A cyberpunk TCG built for immersive world building and dramatic emergent play. The world, the meta, all shaped by the players. |
| \<HOT//WIRED_\> | TTRPG | No classes. No skill lists. \<HOT//WIRED_\> is a fast-play cyberpunk TTRPG where the Skill Scope system turns your character concept into your mechanics. |
| Forsaken Dark | TTRPG | Fast-play dark fantasy survival. Descend into the Forsaken Dark — brutal combat, desperate choices, and magic that summons something barely controllable and ancient. |

#### Footer
- retroboomgames.com
- Discord link (placeholder)
- WargameVault link → `https://www.wargamevault.com/en/product/188181/hail-of-fire`

---

### 3. Blog Section (`/blog`)

- Simple reverse-chronological post list page at `/blog/index.html`
- Individual post template at `/blog/post.html` (or equivalent static structure)
- No CMS required — static HTML is fine
- The first post will be a Hail of Fire design diary; leave a clearly marked placeholder
- Link to `/blog` in the footer (and optionally the nav)

---

## Aesthetic Direction

- **Background:** Near-black — `#0a0a0a` base, `#111111` for slightly elevated surfaces, `#1a1a1a` for cards
- **Text:** Off-white `#f0f0f0` for primary, `#888888` for secondary/muted, `#333333` for borders and dividers
- **Palette:** Strictly black, white, and gray. Yellow, red, and blue may be used sparingly as accents where genuinely needed — not decoratively.
- **Style:** Typography-driven. No illustration or art assets required beyond the existing HoF title image. Serious indie publisher feel — not a hobby blog, not a corporate site.
- **Formatting:** Clean, considered spacing. Generous padding. Let the type breathe. Dividers are `1px solid #333333`.

### Typography
- **Wordmark / Hero headline:** Monoton (Google Fonts) — used for the site wordmark and the hero `<h1>`
- **Game titles and section headings:** Barlow Condensed (Google Fonts), weight 700, uppercase, tight letter-spacing
- **Body / nav / labels:** Barlow (Google Fonts), weight 300–400
- Load all three via a single Google Fonts request: `Monoton`, `Barlow Condensed:wght@400;600;700`, `Barlow:wght@300;400`

### Key Layout Decisions
- No navbar on initial build — add once content structure is confirmed
- Wordmark sits inside the hero section above the headline, styled small and muted
- HoF feature section: two-column grid (text left, image right), collapses to single column on mobile
- Games grid: `repeat(auto-fill, minmax(260px, 1fr))`, separated by `1px` gutters on a `#333333` background (creates grid line effect without borders on each card)
- Active game card (Hail of Fire): slightly elevated background `#111111`
- Coming-soon game cards: `opacity: 0.35`
- Buttons: primary = solid white with dark text; secondary = transparent with gray border

---

## Technical Notes

- Static site, hosted on GitHub Pages
- No build tools required unless already in use in the repo — check first
- No JavaScript frameworks required
- External fonts via Google Fonts CDN is fine
- The existing utility pages may have their own styles — match the new aesthetic where possible without breaking them

---

## Placeholders / TODOs (flag clearly in code comments)

- Discord invite URL (two instances: nav and HoF CTA)
- Blog first post content

---

## Out of Scope

- Games detail pages (future work)
- Ko-fi / support integration (future work)
- Points system or game lookup tools
