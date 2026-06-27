---
name: site-builder
description: Build a high-converting, on-brand one-page website from a short brief. Writes the copy, designs the page, and builds a single self-contained responsive animated index.html you can open and host, no frameworks, no build step. Use for "build me a website / landing page", "make a one-pager for my business", "a site to sell X".
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
---

# Site Builder — a high-converting one-page site, fast

Give it your business and your brand colour. It writes the copy, designs the page, and builds a single self-contained `index.html` that is responsive, lightly animated, and built to convert. Then it opens it. No frameworks, no build step.

*(A free skill from Oloye. The AI Automation Guy. Want one set up for your business? See the end.)*

## When to use
"build me a website / landing page", "a one-pager for my business", "a site to sell X".

## Ask for (only what is missing)
- What the business is, and who it is for.
- The ONE thing a visitor should do (book a call, buy, join, message).
- Brand: one accent colour (hex) and light or dark. Default: dark `#0E0F12` with one bright accent.
- Wordmark / logo text.
- Any images they already have (optional).

## Rules (what makes it convert)
- **One primary CTA, repeated.** One job per section.
- **Benefit-led copy:** people buy the outcome (time saved, money made, stress gone), not the feature. Plain language, no jargon, no em dashes, no fabricated stats, no fake testimonials.
- **Mobile-first, fully responsive.**
- **Single self-contained file:** inline CSS, Google Fonts via `<link>`, a tiny IntersectionObserver script for scroll reveals. Nothing to install.

## Structure (conversion-first)
1. Sticky top bar: wordmark + CTA button.
2. Hero: benefit headline + one subline + primary CTA.
3. The problem: the pain, specific and felt.
4. How it works: 3 simple steps.
5. What you get: 3 to 4 outcomes.
6. Proof: honest only.
7. Final CTA band.
8. Footer.

## Design defaults (premium, brandable)
- Dark base (or light), with ONE accent used sparingly: buttons, key highlights, the logo accent. Never colour the body text.
- Big type, lots of whitespace, one focal point per section.
- A display font + a body font (e.g. Space Grotesk + Inter).
- Subtle motion: fade-up on scroll, a soft accent glow behind the hero, gentle hover lift on buttons and cards, a glow pulse on the primary CTA. Respect `prefers-reduced-motion`.
- Responsive: single column on mobile, then a desktop breakpoint (~760px) with a bigger centred hero, multi-column steps and outcomes.
- Optional images: if provided, wire in a hero + one mid-page image, web-optimised (WebP, `ffmpeg -i in -vf scale=WIDTH:-1 -c:v libwebp -quality 80 out.webp`). If none, the site looks great text-only.

## Build steps
1. Lock the brief (business, ONE action, accent colour, light or dark).
2. Write the copy section by section.
3. Build one `index.html` with the structure + design defaults + the animation layer + one CTA wired to the destination URL.
4. Open it in the browser. Iterate on request ("make the hero bolder", "swap to light", etc.).

## Optional: build it as a team (more theatrical)
If you run multiple agents, split the work to show collaboration: one writes the copy, one sets the design, one builds. Same output, but it reads like a team. Not required, a single pass builds the whole thing.

## Make it yours
Swap the accent colour, the fonts and the wordmark for any brand. The structure and the conversion rules stay the same.

---
Built by **Oloye. The AI Automation Guy.** Want the AI that answers your customers set up for your business? Comment or DM **'AUDIT'** for a free look.
