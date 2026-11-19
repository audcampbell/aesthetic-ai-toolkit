# Price your treatment menu

A free Claude skill for med spas, aesthetics, wellness and plastic surgery practices, by Audrey Campbell, MPH ([The Audrey Aesthetic](https://theaudreyaesthetic.com)).

Drag in your treatment menu, product invoices or cost of goods, membership details and monthly overhead. The skill reads them, asks only for what's missing, works out what every treatment really costs you, and hands back recommended prices.

## How to use it

1. Install it (below).
2. In Claude, say "price my menu" and drag in whatever you have: a menu PDF or screenshot, invoices, your membership terms, a P&L or a plain list of monthly costs, and last month's sales by service. No files? It offers a fill-in template.
3. Answer what's missing, a few questions at a time, each with a suggested answer:
   - **Market and positioning:** rural or small town, suburban, a mid-size city, a major metro or a resort market; value, mid-market or luxury.
   - **Your profit goal** for each treatment. It suggests 30% on neurotoxin and filler as a strong goal, and 45% or more on skin, facial and device treatments.
   - **Neurotoxin:** vial size, what you pay per vial after rebates, how you dilute, how your product compares to Botox units (Daxxify at 2 to 1), and whether all your toxins cost the same per area. It works out your cost per unit.
   - **How you price:** Audrey recommends per area for neurotoxin and filler. Per unit and per syringe are supported, priced side by side.
   - **Time, capacity and what comes off each sale:** with typical numbers if you don't know yours.

## What you get back

- Your true cost per unit, per syringe and per treatment
- A recommended price for every treatment, with your margin for regular patients and for members, checked against published price ranges for your market
- Recommendations for anything losing money or under target, and a membership check
- A service mix check: each treatment's share of revenue next to its share of profit and its profit per hour, and how to grow the higher-margin work (microneedling, facials, peels) around your injectables
- Supplies and cost tips, and a patient-facing menu in your voice
- A spreadsheet of the tables to keep

## What's in this folder

| File | What it is |
|---|---|
| `skills/price-your-treatment-menu/SKILL.md` | The Claude skill. Paste it into ChatGPT or any AI if you don't use Claude. |
| `skills/price-your-treatment-menu/references/market-ranges.md` | Published price and product-cost ranges (sources and dates listed) that the skill uses as a sanity check, never as a price to copy. |
| `skills/price-your-treatment-menu/references/intake-template.md` | A fill-in template for owners without files to drop in. |


## How the math works

The skill runs every formula in code, never in its head, and shows its work. The method is time-driven activity-based costing: each cost is charged by the minutes a treatment uses of a room or a provider.

- **Cost per unit** = what you pay for a vial, after rebates ÷ units in the vial
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
- **Price per unit follows the ratio:** Audrey recommends 2 Daxxify units to 1 Botox unit, and pricing each toxin so an area costs about the same whichever one the patient chooses. If Botox is $14 a unit, Daxxify is about $7. If Botox is $15, Dysport is about $5.

Dosing is always your provider's decision. The skill never suggests fewer units to hit a price.

## Install the skill

- **Claude:** turn on file creation under Settings, Capabilities. Then go to Customize, Skills, +, Upload a skill, and pick `price-your-treatment-menu.zip` from the `downloads` folder.
- **Claude Code:** `/plugin marketplace add audcampbell/aesthetic-ai-toolkit`, then `/plugin install price-your-treatment-menu@aesthetic-ai-toolkit`.
- **ChatGPT:** create a Project and paste `SKILL.md` into its instructions.
- **Any other AI:** paste `SKILL.md` at the top of a new chat.

## Before you use it

- Use the costs on your own invoices, after rebates. Product prices and loyalty programs change often. Every number in the example is made up.
- Your price comes from your own costs and target. The published ranges are a sanity check, never a price to copy, and the skill never names what a nearby practice charges.
- Many states treat commission on medical procedures, or a medical director paid a percentage of revenue, as illegal fee-splitting. Ask a healthcare attorney.
- When you publish prices, follow your state's rules on advertising medical prices.
- Keep patient information out. The tool only needs business numbers.
- This is a planning tool, not financial, tax or legal advice.

## Want it set up for you?

Audrey builds full pricing models with a practice's real costs, moves menus to per-area pricing, tests memberships against them, and sets up the monthly report.

Want to understand your cost of goods better? Audrey suggests [Medvelle](https://www.medvelle.com/) for purchasing and inventory (partner). Or [reach out to Audrey](https://theaudreyaesthetic.com/#contact) to put this to work or build your Claude dashboard.

## License

The skill is MIT licensed. The guide text is CC BY 4.0. Use them, and credit The Audrey Aesthetic.
