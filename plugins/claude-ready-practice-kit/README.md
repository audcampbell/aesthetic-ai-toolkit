# Claude-ready practice kit

A free Claude skill for med spas, dermatology and plastic surgery practices, by Audrey Campbell, MPH ([The Audrey Aesthetic](https://theaudreyaesthetic.com)). Last reviewed November 2026.

Set Claude up for your practice as five Projects: front desk, marketing, finance, hiring and operations. A Project is a workspace in Claude with its own chats, files and instructions, so Claude already knows your menu, policies and voice when your team opens it. The skill asks about your practice and your Claude plan first, then gives each Project a ready-to-paste instruction, a list of files to add, the connectors worth turning on, and what to leave out.

## How to use it

1. Install it (below).
2. In Claude, say "set up Claude for my practice."
3. Answer a few questions: your plan, your team, where your files live, your systems and your voice.
4. Set up one Project at a time. Each comes with the steps, the instruction, a file checklist, connectors, what to leave out, three starter prompts and sharing settings.

## The five Projects

| Project | Files to add | Leave out |
|---|---|---|
| Front desk | Menu and prices, booking and cancellation policies, membership terms, FAQ, scripts | Patient messages, the schedule, anything from the EMR |
| Marketing | Brand guide, approved service descriptions, marketing calendar, approved claims | Before-and-after photos, testimonials with names, patient lists |
| Finance | P&L, monthly totals, invoices, payroll summary, menu | Any report with one row per patient, bank logins |
| Hiring | Job descriptions and pay ranges, org chart, handbook, onboarding plan | Candidates' personal details, staff health information |
| Operations | SOPs, vendor list, equipment, compliance calendar | Incident reports with patient details, chart audits |

Free accounts can make up to five Projects. Team and Enterprise can share Projects with the team.

## What's in this folder

| File | What it is |
|---|---|
| `skills/claude-ready-practice-kit/SKILL.md` | The Claude skill. |
| `skills/claude-ready-practice-kit/references/project-setups.md` | The five Projects: instructions, files, connectors and what to leave out. |
| `skills/claude-ready-practice-kit/references/anthropic-sources.md` | What Anthropic's own help center says about Projects, connectors, sharing and HIPAA, with links and the date checked. |

## Install the skill

- **Claude:** turn on file creation under Settings, Capabilities. Then go to Customize, Skills, +, Upload a skill, and pick `claude-ready-practice-kit.zip` from the `downloads` folder.
- **Claude Code:** `/plugin marketplace add audcampbell/aesthetic-ai-toolkit`, then `/plugin install claude-ready-practice-kit@aesthetic-ai-toolkit`.
- **ChatGPT or any other AI:** paste `SKILL.md` into a Project's instructions or at the top of a new chat. The Claude steps won't match exactly, but the Project setups will.

## Before you use it

- No patient information in any Project. Claude Free, Pro, Max and Team can't sign a BAA, and even on Claude Enterprise, Anthropic says connectors, skills and shared artifacts aren't covered.
- Claude changes often. If a menu looks different, check Anthropic's help center.

Want help setting it up with your team? At the end, the skill offers to draft an email to Audrey. You review it and send it yourself. Or [get in touch](https://theaudreyaesthetic.com/#contact).

## License

The skill is MIT licensed. The guide text is CC BY 4.0.
