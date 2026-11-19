# Monthly totals file

One row per month. One column per number. Totals only, never a list of patients. Save it as a CSV or Excel file named `[practice]-monthly-numbers`. Each month, add one row.

## Columns

| Column | What goes in it | Where it comes from |
|---|---|---|
| month | First day of the month, for example 2026-10-01 | |
| service_revenue | Service sales, in dollars | Sales summary |
| completed_appointments | Visits that happened | Appointments report |
| patients_rebooked_pct | Share of patients who left with their next visit booked, as a percent | Rebooking or pre-booking report |
| nonmember_patients_seen | Patients seen who were not members | Appointments or client report |
| new_memberships | Memberships sold or started that month | Membership report |
| consults_completed | Appointments booked as a consult that happened | Appointments report, filtered to consults |
| consults_booked_treatment | Of those, how many booked a treatment (same rule every month) | Appointments report |
| provider_hours_worked | Provider hours worked | Utilization report or payroll |
| notes | Anything unusual: a closed week, a new provider, a promotion, a change in how a number is counted | You |

## Example (made-up numbers)

```
month,service_revenue,completed_appointments,patients_rebooked_pct,nonmember_patients_seen,new_memberships,consults_completed,consults_booked_treatment,provider_hours_worked,notes
2026-09-01,114000,231,27,150,9,40,22,480,
2026-10-01,120000,240,25,155,11,44,26,480,Fall filler promo
```

The five KPIs come from these columns:
- Rebooking rate: patients_rebooked_pct
- Membership conversion: new_memberships ÷ nonmember_patients_seen
- Consult conversion: consults_booked_treatment ÷ consults_completed
- Average ticket: service_revenue ÷ completed_appointments
- Revenue per provider hour: service_revenue ÷ provider_hours_worked

## Rules
- Same date range on every report: the 1st to the last day of the month.
- Same settings every month (tax and tips in or out, accrual or cash).
- If a number is missing, leave it blank. Don't type zero.
