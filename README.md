# Aesthetic AI Toolkit

Free Claude skills and kits for medical aesthetics practices (med spas, aesthetics, wellness and plastic surgery), by Audrey Campbell, MPH, of [The Audrey Aesthetic](https://theaudreyaesthetic.com).

Each skill stands on its own. Take only the one you need. Drop in your practice's own files (a menu, invoices, last month's reports) and it asks only for what's missing, so what it gives back is yours. None of them needs patient information.

## Pick the tool you need

| Tool | What it does | Download |
|---|---|---|
| [Price your treatment menu](plugins/price-your-treatment-menu) | Drop in your menu, invoices, membership and overhead. Get your true cost per unit and per treatment, recommended prices, a member margin check and a draft menu. | [Skill (.zip)](downloads/price-your-treatment-menu.zip) |
| [Where is my med spa losing money?](plugins/where-is-my-med-spa-losing-money) | Drop in last month's reports. See which leak costs you most (rebooking, inquiries, no-shows, retail, discounts), and get a 30-day plan for it. | [Skill (.zip)](downloads/where-is-my-med-spa-losing-money.zip) |
| [Find and vet your medical director](plugins/find-your-medical-director) | First-call questions, a scorecard for comparing candidates, red flags, and a brief for your healthcare attorney. US; not legal advice. | [Skill (.zip)](downloads/find-your-medical-director.zip) |
| [Claim your practice in ChatGPT](plugins/claim-your-practice-in-chatgpt) | See what ChatGPT, Gemini and Perplexity say about you, claim your ChatGPT Business Hub listing, fix wrong details, and track mentions monthly. | [Skill (.zip)](downloads/claim-your-practice-in-chatgpt.zip) |
| [Ad Claim Check](plugins/ad-claim-check) | Screens US ads, captions, web pages and review replies for what the FTC, FDA, state boards, Meta or Google might flag, and rewrites them. Not legal advice. | [Skill (.zip)](downloads/ad-claim-check.zip) |
| [Build your Claude dashboard](plugins/build-your-claude-dashboard) | Step by step: start with five KPIs, export the right reports, take out patient information, then build, share and refresh a monthly dashboard in Claude. | [Skill (.zip)](downloads/build-your-claude-dashboard.zip) |
| [HIPAA-safe review replies](plugins/hipaa-safe-review-replies) | Paste a Google or Yelp review. Get a reply in your voice that never confirms the reviewer was a patient, and know which ones to take offline. Not legal advice. | [Skill (.zip)](downloads/hipaa-safe-review-replies.zip) |
| [Lapsed patient win-back](plugins/lapsed-patient-win-back) | Work down expiring packages and member balances first, then bring back lapsed patients. Template emails and texts with your branding, a tracker, and opt-out rules built in. Never patient lists. | [Skill (.zip)](downloads/lapsed-patient-win-back.zip) |
| [Claude-ready practice kit](plugins/claude-ready-practice-kit) | Set up five Claude Projects (front desk, marketing, finance, hiring, operations): what to paste, which files to add, which connectors to turn on, and what to leave out. | [Skill (.zip)](downloads/claude-ready-practice-kit.zip) |
| [Build your provider pay plan](plugins/build-your-provider-pay-plan) | A pay plan and offer for an injector, esthetician or wellness provider: market base rate, a KPI bonus in flat dollars, raises and retention extras, with the cost checked. | [Skill (.zip)](downloads/build-your-provider-pay-plan.zip) |

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

Swap in `where-is-my-med-spa-losing-money`, `find-your-medical-director`, `ad-claim-check`, `claim-your-practice-in-chatgpt`, `build-your-claude-dashboard`, `hipaa-safe-review-replies`, `lapsed-patient-win-back`, `claude-ready-practice-kit` or `build-your-provider-pay-plan` for the others.

**ChatGPT or any other AI:** open the tool's `SKILL.md` and paste it into a Project's instructions, or at the top of a new chat.

**No AI at all:** the revenue math and the medical director kit also come as spreadsheets that open in Excel, Google Sheets or Numbers.

## Ground rules

- No patient information goes into any of these tools.
- The skills run every formula in code, never in their head, and every formula is listed.
- These are planning and educational tools, not financial, tax, legal or clinical advice.

## Want it set up for you?

Audrey sets these up in practices, with your real numbers and your team, and can introduce you to the healthcare attorneys and vendors she recommends. [Get in touch](https://theaudreyaesthetic.com/#contact).

## License

Skills and spreadsheets: MIT. Guide text: CC BY 4.0.
