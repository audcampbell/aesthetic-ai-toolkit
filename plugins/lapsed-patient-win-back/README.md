# Lapsed patient win-back

A free Claude skill for US med spas, dermatology and plastic surgery practices, by Audrey Campbell, MPH ([The Audrey Aesthetic](https://theaudreyaesthetic.com)). Last reviewed November 2026.

Bring patients back, starting with the ones who already paid. Part 1 works down what's on the books: packages about to expire, packages with treatments left, and membership balances over $200. Part 2 brings back lapsed patients: neurotoxin, facial and peel, skincare buyers, and consults who never booked. You get template emails and texts to make your own, with your branding, your provider names and your offers. You build the actual lists in your own booking or email system. No patient lists ever go into the chat.

## How to use it

1. Install it (below).
2. In Claude, say "help me win back patients."
3. Answer a few questions: your systems, how many packages are expiring, how many members have balances, your season, any offer, and how you collect consent for email and texts. Counts only.
4. Get your groups (prepaid money first), how to find each one in your system, a sequence calendar, template emails and texts, a compliance checklist, and a tracker.

## What you get back

- Part 1 groups: expiring packages, unused treatments, membership balances over $200, unused prepaid balances
- Part 2 groups: neurotoxin, facial and peel, skincare buyers, consults who never booked
- A three to four week sequence for each: email, text (only to patients who agreed to marketing texts), email, last note
- Template emails and texts with eye-catching subject lines and placeholders like {first_name}, {provider_name}, {sessions_left} and {expiration_date}, filled in by your own system
- A checklist for CAN-SPAM, texting consent, expiration rules and HIPAA marketing rules
- A weekly tracker: bookings, revenue, and prepaid treatments or dollars redeemed

## What's in this folder

| File | What it is |
|---|---|
| `skills/lapsed-patient-win-back/SKILL.md` | The Claude skill. |
| `skills/lapsed-patient-win-back/references/consent-rules.md` | HIPAA marketing, CAN-SPAM and texting rules, with links to official sources and the date checked. Includes the FCC opt-out change that takes effect November 25, 2026. |

## Install the skill

- **Claude:** turn on file creation under Settings, Capabilities. Then go to Customize, Skills, +, Upload a skill, and pick `lapsed-patient-win-back.zip` from the `downloads` folder.
- **Claude Code:** `/plugin marketplace add audcampbell/aesthetic-ai-toolkit`, then `/plugin install lapsed-patient-win-back@aesthetic-ai-toolkit`.
- **ChatGPT or any other AI:** paste `SKILL.md` into a Project's instructions or at the top of a new chat.

## Before you use it

- Groups and counts only. Never paste a patient list.
- Send through your own booking, email or texting platform, under a BAA.
- Text only patients who gave written consent to marketing texts. Consent to appointment reminders doesn't count.
- Check your state's rules before telling patients a package or gift card expires.
- Double check HIPAA marketing rules with your healthcare attorney. This is a planning tool, not legal advice.

## Make it automatic

These are easy win-backs you can run by hand. The best version runs on its own: set up automatic win-back and package reminders in your EMR or CRM, ideally with a consultant. Want help? At the end, the skill offers to draft an email to Audrey. You review it and send it yourself. Or [get in touch](https://theaudreyaesthetic.com/#contact).

## License

The skill is MIT licensed. The guide text is CC BY 4.0.
