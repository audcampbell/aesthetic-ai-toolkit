# Aesthetic AI Toolkit

Free AI skills, calculators and kits for medical aesthetics practices (med spas, dermatology and plastic surgery), by Audrey Campbell, MPH, of [The Audrey Aesthetic](https://theaudreyaesthetic.com).

Each tool stands on its own. Take only the one you need. Each starts with your practice's own numbers, so what it gives back is yours, and none of them needs patient information.

## Pick the tool you need

| Tool | What it does | Download |
|---|---|---|
| [Price your treatment menu](plugins/price-your-treatment-menu) | Price neurotoxin and filler per area (filler as a range), plus skin and device treatments. Check every treatment's margin for regular patients and for members. | [Skill (.zip)](downloads/price-your-treatment-menu.zip) |
| [Where is my med spa losing money?](plugins/where-is-my-med-spa-losing-money) | Ten totals from last month. See which leak costs you most (rebooking, inquiries, no-shows, retail, discounts), and get a 30-day plan for it. | [Skill (.zip)](downloads/where-is-my-med-spa-losing-money.zip) |
| [Find and vet your medical director](plugins/find-your-medical-director) | First-call questions, a scorecard for comparing candidates, red flags, and a brief for your healthcare attorney. US; not legal advice. | [Skill (.zip)](downloads/find-your-medical-director.zip) |
| [Claim your practice in ChatGPT](plugins/claim-your-practice-in-chatgpt) | See what ChatGPT, Gemini and Perplexity say about you, claim your ChatGPT Business Hub listing, fix wrong details, and track mentions monthly. | [Skill (.zip)](downloads/claim-your-practice-in-chatgpt.zip) |
| [Ad Claim Check](plugins/ad-claim-check) | Screens US ads, captions, web pages and review replies for what the FTC, FDA, state boards, Meta or Google might flag, and rewrites them. Not legal advice. | [Skill (.zip)](downloads/ad-claim-check.zip) |

Want them all? [Download every tool at once (.zip)](downloads/aesthetic-ai-toolkit-all.zip).

## Install one tool

**Claude app:**
1. Download that tool's zip above.
2. Turn on file creation under Settings, Capabilities.
3. Go to Customize (or Plugins), then Skills, +, Upload a skill, and pick the zip.

**Claude Code:** add the toolkit once, then install only the tools you want.

```
/plugin marketplace add audcampbell/aesthetic-ai-toolkit
/plugin install price-your-treatment-menu@aesthetic-ai-toolkit
```

Swap in `where-is-my-med-spa-losing-money`, `find-your-medical-director`, `ad-claim-check` or `claim-your-practice-in-chatgpt` for the others.

**ChatGPT or any other AI:** open the tool's `SKILL.md` and paste it into a Project's instructions, or at the top of a new chat.

**No AI at all:** the calculators and the medical director kit come as spreadsheets that open in Excel, Google Sheets or Numbers.

## Ground rules

- No patient information goes into any of these tools.
- Calculators use plain formulas, never AI arithmetic, and every formula is listed.
- These are planning and educational tools, not financial, tax, legal or clinical advice.

## Want it set up for you?

Audrey sets these up in practices, with your real numbers and your team, and can introduce you to the healthcare attorneys and vendors she recommends. [Get in touch](https://theaudreyaesthetic.com/#contact).

## License

Skills and spreadsheets: MIT. Guide text: CC BY 4.0.
