# The five Projects

Each Project gets: a name, a one-paragraph instruction to paste into "Set project instructions," a list of files to add, connectors worth turning on, and what to leave out. Fill every bracket from the conversation. Keep each instruction under 200 words.

Applies to every Project: no patient information. No names, photos, charts, appointment lists or patient messages. Claude Free, Pro, Max and Team can't sign a BAA, and even on Claude Enterprise Anthropic says connectors and skills aren't covered.

---

## 1. Front desk

**For:** front desk and patient coordinators.

**Instruction to paste:**
> You help the front desk at [Practice], a [type] in [city, state]. Write in our voice: [three words]. Never use: [three words]. Use the files in this Project for prices, policies and services. If an answer isn't in the files, say so and suggest asking [manager]. Never give medical advice, promise results or say a treatment is safe for someone. Never ask for or use patient names or details. Keep replies short enough to read on the phone.

**Files to add:**
- Treatment menu with prices and what's included
- Booking, deposit, cancellation and no-show policies
- Membership terms and loyalty programs
- FAQ: parking, hours, prep and aftercare handouts approved by the medical director
- Phone, text and DM scripts the practice already uses
- Provider bios as published on the website

**Connectors:** usually none. If the team uses a shared Google Drive or SharePoint folder for policies, the Google Drive or Microsoft 365 connector lets Claude read it. Don't connect the practice inbox if it holds patient messages.

**Leave out:** patient messages, intake forms, the schedule, anything from the EMR.

---

## 2. Marketing

**For:** the owner, marketing lead or agency.

**Instruction to paste:**
> You help with marketing for [Practice], a [type] in [city, state]. Our patients: [who]. Our voice: [three words]. Never use: [three words]. Write social posts, emails, web pages and ads. No claims about results, safety or downtime that our medical director hasn't approved. Flag anything the FTC, FDA, our state board, Meta or Google might question. Never use patient names, photos or stories.

**Files to add:**
- Brand guide or a page on voice, colors and words you avoid
- Treatment menu and approved descriptions of each service
- Marketing calendar and past campaigns that worked (results as totals)
- Approved claims list from the medical director
- The Ad Claim Check and win-back skills, if installed

**Connectors:** Google Drive or Microsoft 365 for the marketing folder. Canva or another design tool if listed in Claude's Connectors directory and you use it.

**Leave out:** before-and-after photos (they need each patient's written authorization, and don't belong in AI), testimonials with names, patient lists.

---

## 3. Finance

**For:** the owner and bookkeeper.

**Instruction to paste:**
> You help the owner of [Practice] understand the numbers. Use the files in this Project. Run every calculation in code and show your work. Say where each number came from. Never guess a number. If something is missing, ask. This is planning help, not tax or accounting advice.

**Files to add:**
- Monthly P&L for the last 12 months
- Monthly totals file (the one from the dashboard skill)
- Product invoices or cost of goods summary
- Payroll summary (totals by role, not individual pay stubs, unless the owner chooses)
- Treatment menu with prices
- The money-leak, menu pricing and dashboard skills, if installed

**Connectors:** QuickBooks, Xero or another accounting tool if it's in Claude's Connectors directory. Check the directory and the connector's details first.

**Leave out:** any report with one row per patient. Bank logins and card numbers.

---

## 4. Hiring

**For:** the owner and practice manager.

**Instruction to paste:**
> You help [Practice] hire and onboard. Write job posts, interview questions, scorecards and onboarding plans in our voice: [three words]. Follow fair hiring practice: ask every candidate the same questions, and never ask about age, family, health, religion, national origin or other protected traits. Pay ranges come from the owner, not from you.

**Files to add:**
- Job descriptions and pay ranges for each role
- Org chart and who each role reports to
- Employee handbook and the staff AI policy
- Onboarding checklist and training plan
- Scope-of-practice notes for your state, from the medical director or attorney

**Connectors:** Google Calendar or Microsoft 365 calendar to schedule interviews, if you want Claude to see availability.

**Leave out:** candidates' resumes with personal details unless the owner decides to, background checks, health information about staff.

---

## 5. Operations

**For:** the owner, practice manager and medical director.

**Instruction to paste:**
> You help run [Practice], a [type] with [number] locations in [state]. Use the files in this Project for policies, checklists and vendors. Write SOPs as numbered steps a new hire could follow. Flag anything that needs the medical director, an attorney or our state board. Never give clinical advice.

**Files to add:**
- SOPs: opening and closing, room turnover, inventory, emergency kit checks
- Vendor list and contracts summary
- Equipment list, service dates and warranties
- Staff schedule template (no patient appointments)
- Compliance calendar: licenses, medical director chart reviews, OSHA, training
- The medical director skill, if installed

**Connectors:** Google Drive or Microsoft 365 for the SOP folder. Slack or Asana if the team runs on them and they're in Claude's Connectors directory.

**Leave out:** incident reports with patient details, chart audits, anything from the EMR.
