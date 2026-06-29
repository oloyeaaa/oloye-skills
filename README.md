# oloye-skills

Free AI skills from **Oloye. The AI Automation Guy.** Each one does a real, boring job for your business so
you don't have to. Built for the **Claude app** (claude.ai) so you can run them on demand or on a schedule.

---

## The skills

| Skill | What it does | Download |
|---|---|---|
| **Invoice Chaser** | Your unpaid invoices → polite, firm chase emails drafted into your Gmail, getting firmer the more overdue they are. Get paid faster. | [⬇ invoice-chaser.zip](https://github.com/oloyeaaa/oloye-skills/raw/master/downloads/invoice-chaser.zip) |
| **Review Reply Machine** | Your Google reviews → an on-brand reply for each in seconds. Thanks the good, handles the bad with class. | [⬇ review-replies.zip](https://github.com/oloyeaaa/oloye-skills/raw/master/downloads/review-replies.zip) |
| **Post Pack** | One idea or voice note → a week of ready-to-post captions in your voice, with hashtags. | [⬇ post-pack.zip](https://github.com/oloyeaaa/oloye-skills/raw/master/downloads/post-pack.zip) |

---

## How to add a skill to the Claude app (2 minutes)

1. **Download** the skill ZIP you want (links above). Don't unzip it.
2. In the Claude app, turn on **Code Execution** once: **Settings > Capabilities** (you only do this the first time).
3. Go to **Customize > Skills**.
4. Click the **`+`** button, then **Create skill**, then **Upload a skill**.
5. Choose the **ZIP** you downloaded. It appears in your skills list, toggled on.

That's it. Now just ask Claude to use it (e.g. "chase my unpaid invoices") and it runs.

### Run it on a schedule (the good bit)
Once a skill is in your app, you can set a **routine** so it runs by itself, for example:
- *Every Monday 9am:* "Write me a week of posts" (Post Pack)
- *Every Friday:* "Chase any unpaid invoices" (Invoice Chaser)

Set it once, it works on its own.

---

## What each skill needs

- **A Claude account** with Code Execution enabled (free to switch on).
- **Invoice Chaser:** connect your **Gmail** (it only drafts, it never sends — you always hit send).
- **Post Pack:** connect **Metricool** if you want it to schedule the posts for you (optional).
- The skill tells you when it needs something. Nothing technical.

Want to read exactly what a skill does first? Open its `SKILL.md` under [`plugins/`](plugins/). Plain English.

---

## Who made this

**Oloye. The AI Automation Guy.** I build AI that does the boring work for small businesses: answering
customers, writing content, chasing leads.

These are the bits you can run yourself, free. If you'd rather have it **built for you and running 24/7**,
that's the day job. See what I do at [oloye.co.uk](https://oloye.co.uk).

---

## Using Claude Code instead?

If you use the Claude Code CLI, you can install these as plugins instead of uploading ZIPs:

```text
/plugin marketplace add oloyeaaa/oloye-skills
/plugin install invoice-chaser@oloye-skills
```

## Licence

MIT. Use it, fork it, ship with it. See [`LICENSE`](LICENSE).
