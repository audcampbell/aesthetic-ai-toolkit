# Price your treatment menu

A free pricing tool for med spas, dermatology and plastic surgery practices, by Audrey Campbell, MPH ([The Audrey Aesthetic](https://theaudreyaesthetic.com)).

Put in what each treatment really costs you: product, supplies, provider time and the room it ties up. See what to charge, your margin today, and which services lose money every time they're booked.

## What's in this folder

| File | What it is |
|---|---|
| `price-your-treatment-menu.xlsx` | The calculator as a spreadsheet. It opens in Excel, Google Sheets (File, then Import) or Numbers. Fill in the shaded cells. |
| `SKILL.md` | An AI skill that explains your results and drafts the menu patients see. It works in Claude, ChatGPT or any AI. |
| `sample-practice.md` | The made-up practice used in the example, with its full results. |

The same calculator runs in your browser at theaudreyaesthetic.com/guides/price-your-treatment-menu.

## How the math works

No AI does the arithmetic. The method is time-driven activity-based costing: each cost is charged by the minutes a treatment uses of a room or a provider.

- **Facility cost per room hour** = room and facility costs ÷ (rooms × room hours × how full)
- **Team cost per provider hour** = team and admin costs ÷ (providers × provider hours × how full)
- **Costs you** = units × cost per unit × (1 + waste) + supplies + provider cost per hour × provider minutes ÷ 60 + facility cost per room hour × room minutes ÷ 60 + team cost per provider hour × provider minutes ÷ 60
- **What you keep** = 1 − commission − card fees − discounts − (patients who finance × financing fee)
- **Charge at least** = costs you ÷ what you keep
- **Suggested price** = costs you ÷ (what you keep − profit you want), rounded up to the next $5
- **Margin now** = (your price × what you keep − costs you) ÷ your price
- **Profit per provider hour** = profit ÷ provider minutes × 60

Facility costs follow the room, because a room or device costs the same whether or not it's booked. Team and admin costs follow the provider, because front desk and admin work grow with appointments.

## Install the skill

- **Claude:** turn on file creation under Settings, Capabilities. Then go to Customize, Skills, +, Upload a skill, and pick this folder as a zip.
- **Claude Code:** copy this folder into `~/.claude/skills/`, or add this repository as a plugin marketplace.
- **ChatGPT:** create a Project and paste `SKILL.md` into its instructions.
- **Any other AI:** paste `SKILL.md` at the top of a new chat.

## Before you use it

- Use the costs on your own invoices, after rebates. Product prices and loyalty programs change often. Every number in the example is made up.
- It works only from your own costs. It doesn't show what other practices charge, and it isn't a market price.
- Many states treat commission on medical procedures, or a medical director paid a percentage of revenue, as illegal fee-splitting. Ask a healthcare attorney.
- When you publish prices, follow your state's rules on advertising medical prices.
- Keep patient information out. The tool only needs business numbers.
- This is a planning tool, not financial, tax or legal advice.

## Want it set up for you?

Audrey builds full pricing models with a practice's real costs, tests memberships and packages against them, and sets up the monthly report. [Get in touch](https://theaudreyaesthetic.com/#contact).

## License

The skill and the spreadsheet are MIT licensed. The guide text is CC BY 4.0. Use them, and credit The Audrey Aesthetic.
