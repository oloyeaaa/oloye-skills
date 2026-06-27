# oloye-skills

Free Claude Code skills from **Oloye. The AI Automation Guy.**

Install once. Get every skill in here, plus whatever ships next.

First skill in the box: **`site-builder`** — describe your business in two lines and get back a finished, high-converting one-page website. One self-contained `index.html`. No frameworks. No build step. Open it, host it, done.

---

## Install (60 seconds)

Inside Claude Code, run:

```text
/plugin marketplace add oloyeaaa/oloye-skills
/plugin install site-builder@oloye-skills
```

That's it. Now use it:

```text
/site-builder
```

Answer the few questions it asks (what the business is, the one action you want visitors to take, your brand colour) and it writes the copy, designs the page, and builds the file.

> New skills get added to this same marketplace over time. To pull the latest:
>
> ```text
> /plugin marketplace update oloye-skills
> ```

---

## What `site-builder` actually does

- **Writes the copy for you.** Benefit-led, plain language, no jargon, no fake testimonials, no made-up stats.
- **Designs a premium page.** Dark or light, one accent colour used with restraint, big type, generous whitespace, subtle scroll animations.
- **Ships one file.** Inline CSS, Google Fonts, a tiny scroll-reveal script. Nothing to install, nothing to deploy through. Drag the `index.html` anywhere.
- **Conversion-first structure.** Sticky CTA bar, benefit hero, the problem, how it works, what you get, honest proof, final CTA, footer. One primary action, repeated.

Then it opens the page so you can see it, and you iterate by just asking ("make the hero bolder", "switch to light", "swap the accent to green").

---

## Requirements

- [Claude Code](https://claude.com/claude-code) installed and signed in.
- That's the whole list.

---

## What's inside

```text
oloye-skills/
├── .claude-plugin/
│   └── marketplace.json        # the marketplace catalogue
└── plugins/
    └── site-builder/
        ├── .claude-plugin/
        │   └── plugin.json      # the plugin manifest
        └── skills/
            └── site-builder/
                └── SKILL.md      # the skill itself
```

Want to read what it does before installing? It's all in [`plugins/site-builder/skills/site-builder/SKILL.md`](plugins/site-builder/skills/site-builder/SKILL.md). Plain English, no surprises.

---

## Who made this

**Oloye. The AI Automation Guy.** I build AI that does the boring work for small businesses: answering customers, writing content, following up on leads.

Want the AI that answers your customers set up for *your* business? DM **'AUDIT'** for a free look.

## Licence

MIT. Use it, fork it, ship sites with it. See [`LICENSE`](LICENSE).
