---
name: site-builder
description: Build a high-converting one-page website with a real, committed design direction, not generic AI slop. It interviews you first, commits a design system tied to your actual business, then builds a single self-contained responsive animated index.html you can open and host. No frameworks, no build step. Use for "build me a website / landing page", "make a one-pager for my business", "a site to sell X".
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
---

# Site Builder — a one-page site with a real design direction, not AI slop

Most AI sites are different but somehow look the same: the same fonts, the same indigo gradient on white, the same centred hero over three feature cards. That happens because the model reaches for the most common choice every time. This skill stops that. It interviews you, commits to a design direction grounded in your specific business, critiques that direction to strip anything generic, then builds one self-contained `index.html` that is responsive, lightly animated, and built to convert.

*(A free skill from Oloye. The AI Automation Guy. Want one set up for your business? See the end.)*

## When to use
"build me a website / landing page", "a one-pager for my business", "a site to sell X".

## Phase 1 — Discovery (ask before building anything)
Ask a tight, conversational set of questions. Only ask for what is missing, 6 to 9 max, do not interrogate. Cover:

- **The owner / business:** what it is, what genuinely makes it different, and what real proof exists (results, reviews, credentials). No proof gets invented later.
- **The visitor:** who lands on this page, what they already believe, what they are afraid of, and what outcome they actually want.
- **The one job:** the single action a visitor should take (book, buy, join, message), and the one feeling the page should leave them with.
- **The world of the subject:** the materials, tools, vocabulary, and references specific to this business. This is the raw material for a distinctive design, so mine it.
- **Brand basics:** wordmark / logo text, any existing colours or fonts, a light or dark lean, and any images they already have (optional).

Default if they will not choose: dark base `#0E0F12` with one bright accent.

## Phase 2 — Commit a design direction (before writing any code)
Run two passes. Do not skip to code.

**Pass A: write a short design brief (the token system).**
- Subject, audience, and single job, one line each.
- **Colour:** 4 to 6 named hex values, each with a one-line reason tied to the subject. "Trust blue" is not a reason. The palette should come from the business's own world.
- **Type:** a display face (used sparingly), a body face, and an optional utility face. Name them and set the scale and weights.
- **Layout:** one sentence plus a tiny ASCII wireframe for each key section.
- **Signature:** ONE memorable element drawn from the subject's own world (a motif, a layout move, a texture, a way of labelling). This is the thing that makes the page not look like everyone else's.

**Pass B: critique the brief against defaults.**
- For every choice ask: "would I pick this exact thing for a completely different business?" If yes, it is generic, so replace it.
- Name and reject the AI tells on sight: indigo or purple gradients on white, the same three default fonts, glassmorphism by default, a centred hero over three identical feature cards as the only idea, emoji used as icons, fake testimonials, invented statistics.
- Only move to code once the direction is specific to THIS business.

## Style presets (pick ONE to anchor the vibe)
Optional. Pick one, do not stack them. The preset steers the look, the brief above still drives the specifics.
- **Minimalist / editorial:** whitespace, restraint, the content breathes. Good for blogs, writers, premium services.
- **Brutalist / industrial:** raw, heavy, anti-corporate, high contrast. Good for bold or contrarian brands.
- **Premium / luxury:** fashion-brand restraint, oversized type, lots of air. Good for high-ticket offers.
- **Clean default:** solid, professional product or business look. The safe pick.

## Rules (what makes it convert)
- **One primary CTA, repeated.** One job per section.
- **Benefit-led copy:** people buy the outcome (time saved, money made, stress gone), not the feature. Plain language, no jargon, no em dashes, no fabricated stats, no fake testimonials.
- **Mobile-first, fully responsive.**
- **Single self-contained file:** inline CSS, Google Fonts via `<link>`, a tiny IntersectionObserver script for scroll reveals. Nothing to install, no framework, no build step.

## Structure (conversion-first)
1. Sticky top bar: wordmark + CTA button.
2. Hero: benefit headline + one subline + primary CTA.
3. The problem: the pain, specific and felt.
4. How it works: 3 simple steps.
5. What you get: 3 to 4 outcomes.
6. Proof: honest only.
7. Final CTA band.
8. Footer.

## Design execution (the no-slop defaults)
- Use ONE accent sparingly: buttons, key highlights, the logo accent. Never colour the body text.
- Big type, real hierarchy, generous whitespace, one focal point per section.
- A display font + a body font (the ones committed in Pass A, e.g. Space Grotesk + Inter as a fallback).
- The **signature** element from Pass A must actually appear on the page. If it does not, the direction was decoration, not design.
- Motion with intent, not scattered effects: a short page-load sequence, fade-up on scroll, a soft accent glow behind the hero, a gentle hover lift on buttons and cards, a glow pulse on the primary CTA. Respect `prefers-reduced-motion`.
- Responsive: single column on mobile, then a desktop breakpoint (~760px) with a bigger centred hero, multi-column steps and outcomes.
- Optional images: if provided (or generated with Higgsfield), wire in a hero + one mid-page image, web-optimised (WebP, `ffmpeg -i in -vf scale=WIDTH:-1 -c:v libwebp -quality 80 out.webp`). If none, the site looks great text-only.

## Build steps
1. Run Discovery (Phase 1).
2. Commit the design direction and run the self-critique (Phase 2). Pick a preset if useful.
3. Write the copy section by section, benefit-led.
4. Build one `index.html`: the structure + the committed tokens + the signature element + the animation layer + one CTA wired to the destination URL.
5. Open it in the browser. Iterate on request ("make the hero bolder", "swap to light", "push the signature harder").

## Optional: build it as a team (more theatrical)
If you run multiple agents, split the work to show collaboration: one runs discovery and writes the brief, one commits the design direction, one writes the copy, one builds. Same output, but it reads like a team. Not required, a single pass builds the whole thing.

## Make it yours
Swap the accent colour, the fonts, the wordmark, and the preset for any brand. The discovery, the commit-then-critique method, and the conversion rules stay the same. That method is what keeps every build distinct instead of another lookalike.

---
Built by **Oloye. The AI Automation Guy.** Want the AI that answers your customers set up for your business? Comment or DM **'AUDIT'** for a free look.
