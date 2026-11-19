# Build your Claude dashboard

A free Claude skill for med spas, dermatology and plastic surgery practices, by Audrey Campbell, MPH ([The Audrey Aesthetic](https://theaudreyaesthetic.com)). Last reviewed November 2026.

A step-by-step guide to building a monthly KPI dashboard in Claude. The skill asks about your practice first, starts you with five numbers worth watching, tells you exactly which reports to export from your system, checks them for patient information, and builds the dashboard with you. Then it shows you how to share it and how to update it each month. Totals only: no patient information.

## How to use it

1. Install it (below).
2. In Claude, say "build my practice dashboard." It asks about your systems, your Claude plan, who should see the dashboard, and what you want it to help you decide.
3. Start with five KPIs: rebooking rate, membership conversion, consult conversion, average ticket and revenue per provider hour. There are many more worth tracking later, like membership penetration, client lifetime value and cancellation rate.
4. Export the reports it lists for your system (Boulevard, Zenoti, Mangomint, Vagaro, PatientNow, Moxie, Nextech, Jane or another), and drag them in.
5. Get your dashboard, a monthly totals file, sharing steps for your plan, and a 20 to 30 minute monthly routine.

## What you get back

- Your numbers, checked, with the report each one came from
- The dashboard itself, built in Claude as an artifact you can open and share
- A monthly totals file (one row per month) that is all the dashboard ever needs
- Your report list, to save for next month
- Sharing steps for your Claude plan
- The prompt to paste next month

## What's in this folder

| File | What it is |
|---|---|
| `skills/build-your-claude-dashboard/SKILL.md` | The Claude skill. |
| `skills/build-your-claude-dashboard/references/reports-to-pull.md` | Which reports to export, and where to find them, for eight booking and EMR systems. |
| `skills/build-your-claude-dashboard/references/monthly-numbers-template.md` | The monthly totals file: columns, an example and the rules. |
| `skills/build-your-claude-dashboard/references/anthropic-sources.md` | What Anthropic's own help center says about artifacts, Claude Data, sharing, connectors and scheduled tasks, with links and the date checked. |

## Be honest about the limits

- The dashboard is only as good as your data. If appointments aren't closed out or consults aren't booked as consults, it will look precise and be wrong.
- It doesn't refresh itself. Built from exported reports, it changes when someone adds the new month. Claude's own dashboard template (Claude Data) refreshes on its own only with a live data connection, and most med spa booking systems don't connect to Claude yet.
- Setup takes real work: one to two hours the first time, then 20 to 30 minutes a month.

## Install the skill

- **Claude:** turn on file creation under Settings, Capabilities. Then go to Customize, Skills, +, Upload a skill, and pick `build-your-claude-dashboard.zip` from the `downloads` folder.
- **Claude Code:** `/plugin marketplace add audcampbell/aesthetic-ai-toolkit`, then `/plugin install build-your-claude-dashboard@aesthetic-ai-toolkit`.
- **ChatGPT or any other AI:** paste `SKILL.md` into a Project's instructions or at the top of a new chat. The Claude-specific steps won't apply, but the KPI list, reports and monthly routine will.

## Want a dashboard that pulls your data for you?

For a dashboard that pulls your EMR, payroll and accounting in automatically, by provider and by location, Audrey suggests [Illume](https://www.joinillume.com/) (partner), and can connect you with them. Use this skill as your starting point in the meantime.

Moving these numbers takes a plan and your team behind it. Want help building that plan? At the end, the skill offers to draft an email to Audrey with your numbers in it. You review it and send it yourself. Or [get in touch](https://theaudreyaesthetic.com/#contact).

## License

The skill is MIT licensed. The guide text is CC BY 4.0.
