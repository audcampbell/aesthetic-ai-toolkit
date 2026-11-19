# HIPAA-safe review replies

A free Claude skill for US med spas, dermatology and plastic surgery practices, by Audrey Campbell, MPH ([The Audrey Aesthetic](https://theaudreyaesthetic.com)). Last reviewed November 2026.

Paste in a Google, Yelp, Facebook or RealSelf review. Get back a reply in your practice's voice that never confirms the reviewer was a patient and never mentions their care, even when they did. The skill tells you which reviews to take offline, which ones not to answer until you've talked to your attorney, and gives you a call script for the hard ones.

## Why it matters

HHS has made practices pay over review replies: $10,000 (Dallas, 2019, Yelp), $23,000 (California, 2022, Yelp), a $50,000 penalty (North Carolina, 2022) and $30,000 (New Jersey, 2023, Google). In each case the practice added patient details while answering a complaint. The reviewer can tell their story. The practice can't add to it. Sources are in `references/hhs-review-cases.md`.

## How to use it

1. Install it (below).
2. In Claude, say "help me reply to this review" and paste the review text. Nothing else about the person.
3. The first time, it asks about your practice: who signs replies, the number for taking things offline, three words for your voice, and a few past replies you liked.
4. Get your reply (two versions for a negative review), a safety checklist under it, and a call script when the review should go offline.

## What you get back

- Which of four buckets the review falls in: thank, reply and invite offline, take offline only, or don't reply yet
- The reply in your voice, under 80 words
- A safety checklist for each reply
- A call or email script for the hard ones
- Optional: a one-page review reply policy for your team

## What's in this folder

| File | What it is |
|---|---|
| `skills/hipaa-safe-review-replies/SKILL.md` | The Claude skill. |
| `skills/hipaa-safe-review-replies/references/hhs-review-cases.md` | The HHS cases, with links to hhs.gov. |

## Install the skill

- **Claude:** turn on file creation under Settings, Capabilities. Then go to Customize, Skills, +, Upload a skill, and pick `hipaa-safe-review-replies.zip` from the `downloads` folder.
- **Claude Code:** `/plugin marketplace add audcampbell/aesthetic-ai-toolkit`, then `/plugin install hipaa-safe-review-replies@aesthetic-ai-toolkit`.
- **ChatGPT or any other AI:** paste `SKILL.md` into a Project's instructions or at the top of a new chat.

## Before you use it

- Paste only the public review. Never paste chart notes or "what really happened."
- This is an educational drafting tool, not legal advice. Talk to your healthcare attorney about any review that mentions a complication, a lawsuit or a board complaint.

Want help with a review reply policy or front desk training? At the end, the skill offers to draft an email to Audrey. You review it and send it yourself. Or [get in touch](https://theaudreyaesthetic.com/#contact).

## License

The skill is MIT licensed. The guide text is CC BY 4.0.
