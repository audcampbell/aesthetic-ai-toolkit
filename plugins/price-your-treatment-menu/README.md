# Price your treatment menu

A free pricing tool for med spas, dermatology and plastic surgery practices, by Audrey Campbell, MPH ([The Audrey Aesthetic](https://theaudreyaesthetic.com)).

Put in what each treatment really costs you: product, waste, supplies, topical numbing, provider time and the room it ties up.

- **Neurotoxin and filler priced per area**, which we recommend. Neurotoxin starts at the 64-unit upper-face dose, and filler is priced as a range across the syringes an area usually takes. The per-unit equivalent is shown too, so you can compare.
- **A margin check for members**, so a membership discount never turns a treatment into a loss.
- **Skin and device treatments**: microneedling, RF microneedling, BBL or IPL, peels and laser.
- **Your market and positioning** (value, mid-market or luxury) set your starting profit target and how the menu is worded. The tool never looks up other practices' prices.

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
- **Neurotoxin product** = units × cost per unit × (1 + waste)
- **Filler product** = syringes × cost per syringe, at the low and the high end of the range
- **Costs you** = product + supplies + numbing + provider cost per hour × provider minutes ÷ 60 + facility cost per room hour × (room minutes + numbing minutes) ÷ 60 + team cost per provider hour × provider minutes ÷ 60
- **What you keep** = 1 − commission − card fees − other discounts − (patients who finance × financing fee)
- **What you keep from a member** = (1 − membership discount) × (1 − commission − card fees − patients who finance × financing fee)
- **Charge at least** = costs you ÷ what you keep
- **Suggested price** = costs you ÷ (what you keep − profit you want), rounded up to the next $5. Per unit, it's rounded up to the next 50 cents.

## Neurotoxin units

- **Upper face:** starts at 64 units, the FDA-labeled dose for Botox Cosmetic and Xeomin.
- **Frown lines:** Botox Cosmetic, Xeomin, Jeuveau and Letybo 20; Dysport 50; Daxxify 40.
- **Upper face for other products:** 64 Botox units converted at a common ratio: about 3 to 1 for Dysport (192), 2 to 1 for Daxxify (128), and 1 to 1 for Jeuveau and Letybo (64). These ratios are a clinical convention, not FDA doses.

Dosing is always your provider's decision. The calculator never suggests fewer units to hit a price.

## Install the skill

- **Claude:** turn on file creation under Settings, Capabilities. Then go to Customize, Skills, +, Upload a skill, and pick this folder as a zip.
- **Claude Code:** copy this folder into `~/.claude/skills/`, or add this repository as a plugin marketplace.
- **ChatGPT:** create a Project and paste `SKILL.md` into its instructions.
- **Any other AI:** paste `SKILL.md` at the top of a new chat.

## Before you use it

- Use the costs on your own invoices, after rebates. Product prices and loyalty programs change often. Every number in the example is made up.
- It works only from your own costs. Your market is used only to word the menu. It doesn't show what other practices charge, and it isn't a market price.
- Many states treat commission on medical procedures, or a medical director paid a percentage of revenue, as illegal fee-splitting. Ask a healthcare attorney.
- When you publish prices, follow your state's rules on advertising medical prices.
- Keep patient information out. The tool only needs business numbers.
- This is a planning tool, not financial, tax or legal advice.

## Want it set up for you?

Audrey builds full pricing models with a practice's real costs, moves menus to per-area pricing, tests memberships against them, and sets up the monthly report.

Want a clearer view of your cost of goods? Audrey recommends [Medvelle](https://www.medvelle.com/) for purchasing and inventory (partner). [Get in touch](https://theaudreyaesthetic.com/#contact).

## License

The skill and the spreadsheet are MIT licensed. The guide text is CC BY 4.0. Use them, and credit The Audrey Aesthetic.
