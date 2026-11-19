# Where is my med spa losing money?

A free Claude skill for med spas and aesthetic practices, by Audrey Campbell, MPH ([The Audrey Aesthetic](https://theaudreyaesthetic.com)).

Drop last month's reports into Claude: your sales summary, appointment summary, schedule or utilization report, and lead or inquiry report, straight out of your EMR or booking system. The skill pulls out ten numbers, shows you where each came from, asks only for what's missing, and gives back the leak that costs you most, what it's worth, and a 30-day plan to fix it. Summary reports only: no patient information.

## How to use it

1. Install it (below).
2. In Claude, say "where am I losing money?" and drag in your reports. Not sure which reports? Tell it which booking or EMR system you use, and it lists the exact reports to export and where to find them. No reports? Type the numbers and it asks for each one.
3. Confirm the numbers it found, set your goals (it suggests starting points), and get your ranked leaks and plan.

## What's in this folder

| File | What it is |
|---|---|
| `where-is-my-med-spa-losing-money.xlsx` | Optional: the same math as a spreadsheet, for anyone not using AI. It opens in Excel, Google Sheets (File, then Import) or Numbers. Fill in the shaded cells. |
| `skills/where-is-my-med-spa-losing-money/SKILL.md` | The Claude skill. It reads your reports, ranks your leaks and builds the 30-day plan for the biggest one. Paste it into ChatGPT or any AI if you don't use Claude. |
| `skills/where-is-my-med-spa-losing-money/references/reports-to-pull.md` | Which reports to export and where to find them in Boulevard, Zenoti, Mangomint, Vagaro, PatientNow, Moxie, Nextech and Jane, and which of the ten numbers each one gives. |
| `sample-practice.md` | The made-up med spa used in the example, with its results. |

## The ten numbers

1. Service revenue
2. Completed appointments
3. Appointments lost to no-shows and late cancellations
4. Provider hours on the schedule
5. Provider hours actually booked
6. New inquiries: calls, forms and DMs
7. Inquiries that booked
8. Patients who left with their next visit booked (%)
9. Discounts and promotions given ($)
10. Skincare and retail sales ($)

## How the math works

The skill runs every formula in code, never in its head, and shows its work. Each leak is valued at your average ticket, the revenue you'd see a month if you hit your own goal. The leaks overlap, so they're ranked, never added together.

- **Average ticket** = service revenue ÷ completed appointments
- **Rebooking** = (goal − your rate) × completed appointments × average ticket. This counts future visits booked each month.
- **Inquiries that never book** = (goal − inquiries booked ÷ inquiries) × inquiries × average ticket
- **Appointments lost** = (lost ÷ (completed + lost) − goal) × (completed + lost) × average ticket
- **Retail** = (goal − retail ÷ service revenue) × service revenue. This counts sales, not profit.
- **Discounts** = (discounts ÷ (revenue + discounts) − goal) × (revenue + discounts)
- **Open hours** = (goal − booked ÷ scheduled hours) × scheduled hours × revenue per booked hour. This is shown separately, because fixing the other leaks is how those hours fill.

## Install the skill

- **Claude:** turn on file creation under Settings, Capabilities. Then go to Customize, Skills, +, Upload a skill, and pick `where-is-my-med-spa-losing-money.zip` from the `downloads` folder.
- **Claude Code:** `/plugin marketplace add audcampbell/aesthetic-ai-toolkit`, then `/plugin install where-is-my-med-spa-losing-money@aesthetic-ai-toolkit`.
- **ChatGPT or any other AI:** paste `SKILL.md` into a Project's instructions or at the top of a new chat.

## Before you use it

- Totals only. Keep patient names and details out.
- The dollar figures are estimates at your own goals, not promised results.
- The default goals are starting points, not industry averages. Published med spa benchmarks are scarce and mostly come from software vendors.
- This is a planning tool, not financial or legal advice. Check your state's rules before charging deposits or cancellation fees.

## Want a dashboard that does this for you?

For a dynamic, AI-native dashboard, so you don't pull and enter all of this by hand, Audrey suggests [Illume](https://www.joinillume.com/) (partner). Use this skill as your planning tool in the meantime, especially if you're not sure your numbers or KPIs are right.

Want to walk through your leaks with a person and build the action plan? At the end, the skill offers to draft an email to Audrey with your top leaks in it. You review it and send it yourself. Or [get in touch](https://theaudreyaesthetic.com/#contact).

## License

The skill and the spreadsheet are MIT licensed. The guide text is CC BY 4.0.
