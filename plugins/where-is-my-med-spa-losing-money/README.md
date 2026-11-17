# Where is my med spa losing money?

A free diagnostic for med spas and aesthetic practices, by Audrey Campbell, MPH ([The Audrey Aesthetic](https://theaudreyaesthetic.com)).

Enter ten numbers from last month. You get back the leak that costs you most, what it's worth, and a 30-day plan to fix it. Totals only: no patient information.

## What's in this folder

| File | What it is |
|---|---|
| `where-is-my-med-spa-losing-money.xlsx` | The diagnostic as a spreadsheet. It opens in Excel, Google Sheets (File, then Import) or Numbers. Fill in the shaded cells. |
| `skills/where-is-my-med-spa-losing-money/SKILL.md` | An AI skill that ranks your leaks and builds the 30-day plan for the biggest one. It works in Claude, ChatGPT or any AI. |
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

No AI does the arithmetic. Each leak is valued at your average ticket, the revenue you'd see a month if you hit your own goal. The leaks overlap, so they're ranked, never added together.

- **Average ticket** = service revenue ÷ completed appointments
- **Rebooking** = (goal − your rate) × completed appointments × average ticket. This counts future visits booked each month.
- **Inquiries that never book** = (goal − inquiries booked ÷ inquiries) × inquiries × average ticket
- **Appointments lost** = (lost ÷ (completed + lost) − goal) × (completed + lost) × average ticket
- **Retail** = (goal − retail ÷ service revenue) × service revenue. This counts sales, not profit.
- **Discounts** = (discounts ÷ (revenue + discounts) − goal) × (revenue + discounts)
- **Open hours** = (goal − booked ÷ scheduled hours) × scheduled hours × revenue per booked hour. This is shown separately, because fixing the other leaks is how those hours fill.

## Before you use it

- Totals only. Keep patient names and details out.
- The dollar figures are estimates at your own goals, not promised results.
- The default goals are starting points, not industry averages. Published med spa benchmarks are scarce and mostly come from software vendors.
- This is a planning tool, not financial or legal advice. Check your state's rules before charging deposits or cancellation fees.

## Want help fixing the top leak?

Audrey works through the fix with practices, from the checkout script to the weekly report. [Get in touch](https://theaudreyaesthetic.com/#contact).

## License

The skill and the spreadsheet are MIT licensed. The guide text is CC BY 4.0.
