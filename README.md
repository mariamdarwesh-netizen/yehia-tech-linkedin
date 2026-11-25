# Yehia Tech · LinkedIn Skill for Claude

A skill that turns Claude into your LinkedIn coach. Ask it anything about LinkedIn and it answers with the same prompts
Yehia Tech uses in the video **«ابني LinkedIn profile من الصفر في 7 خطوات»**, filled with your own details.

You don't copy prompts anymore. Just ask:

- «اكتبلي Headline، أنا Junior Data Analyst»
- «ظبطلي الـ About ده: …»
- «لو أنا recruiter في Vodafone هكلّمني ولا لأ؟» (attach your profile PDF)
- «أبعت إيه لـ recruiter في Instabug؟»
- «عايز أفكار بوستات عن Power BI»
- "Rewrite my experience as achievements"

Claude asks you once for the basics (name, field, target role, target companies, the topic you post about), then
gives you the finished answer.

## What's inside

| | |
|---|---|
| `SKILL.md` | how Claude picks the right prompt and answers |
| `references/prompts.md` | 14 prompts: Headline, Keywords, Positioning, About, Experience (XYZ), Featured, recommendations, Profile Audit, Recruiter Test, Outreach, a 30-day plan, comments, 30 post ideas |
| `references/playbook.md` | the 7 steps of the video, tips, and a 12-item checklist |
| `references/templates.md` | the headline formula, connection notes, and 5 post templates (Arabic + English) |

## Install

### Claude app (claude.ai, desktop, mobile)

1. Download **yehia-tech-linkedin.zip** from the [latest release](https://github.com/mariamdarwesh-netizen/yehia-tech-linkedin/releases/latest).
2. In Claude, open **Settings → Capabilities** (or **Customize → Skills**) and upload the ZIP as a skill.
3. Make sure the skill is turned on, then ask any LinkedIn question.

### Claude Code

```bash
git clone https://github.com/mariamdarwesh-netizen/yehia-tech-linkedin.git ~/.claude/skills/yehia-tech-linkedin
```

Start a new Claude Code session and ask your question. To update later: `git -C ~/.claude/skills/yehia-tech-linkedin pull`.

## Tips

- Attach your profile as a PDF (LinkedIn → your profile → **More → Save to PDF**) for the audit and the recruiter test.
- Claude never invents numbers about you. If an achievement needs a number, it asks.
- Not sure where to start? Ask «أبدأ منين؟» and it walks you through the 7 steps in order.

---

Made by **Yehia Tech**.
