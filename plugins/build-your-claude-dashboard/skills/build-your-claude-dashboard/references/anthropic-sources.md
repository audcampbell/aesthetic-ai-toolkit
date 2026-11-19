# What Anthropic says about dashboards, artifacts, connectors and scheduled tasks

Checked: November 19, 2026, on Anthropic's own help center and website only. Most help articles show "Updated this week" or "Updated today" instead of a date. Claude changes often, so if the owner's screen differs, trust the screen and the live article.

## Artifacts
Source: [What are artifacts and how do I use them?](https://support.claude.com/en/articles/17153992-what-are-artifacts-and-how-do-i-use-them)
- An artifact is something Claude makes that opens beside the chat. You can edit it, come back to it and share it. All artifacts are saved to the Artifacts tab in the sidebar.
- Create one by asking in any chat, by choosing "Output" in the message box and picking a template, or from the Artifacts tab.
- Artifacts in chat are on all plans. The Data, Sheets (beta) and Whiteboards (beta) templates are on Pro, Max, Ultra, Team and Enterprise.
- Artifacts need "Cloud code execution and file creation" (called "Create and edit files" in the newer Settings). Free, Pro, Max and Ultra: Settings, then Capabilities. Team and Enterprise: Organization settings, then Capabilities.
- Artifacts can connect to apps you've connected to Claude (Pro and higher, web and desktop). The first time, Claude asks you to approve the tools. Everyone connects their own apps.
- An artifact can include an upload control for images, PDFs or CSV files. Up to 20 MB per file.
- Artifacts can save data between visits, for one person or shared.

## Claude Data (dashboards)
Sources: [Get started with Claude Data](https://support.claude.com/en/articles/17454700-get-started-with-claude-data), [Claude Artifacts](https://claude.com/features/artifacts), [Claude Whiteboards, Claude Sheets, and Claude Data](https://claude.com/resources/articles/sheets-whiteboards-data) (November 10, 2026)
- Claude Data, formerly Claude Dashboards, makes dashboards and data stories. Claude writes a query for each chart. Each chart shows its query and when it was last refreshed.
- Plans: Pro, Max, Ultra, Team and Enterprise. On Team it's on by default. On Enterprise it turns on by default November 20, 2026, unless an owner already chose a setting.
- It needs a connected data source first: a data warehouse (for example Redshift, BigQuery, Snowflake) or a connected app such as Salesforce. The help article does not list uploaded files as a source.
- Claude refreshes the data when someone opens the dashboard and the data is due. The help article says there is no scheduled refresh.
- Live sharing (beta) lets people in your organization see your results without their own access to the source.
- Anthropic suggests it for quick questions, not as a replacement for deeper analysis tools.

## Sharing artifacts
Source: [Share artifacts](https://support.claude.com/en/articles/9547008-share-artifacts), [Artifacts admin guide for Team and Enterprise plans](https://support.claude.com/en/articles/16994751-artifacts-admin-guide-for-team-and-enterprise-plans)
- Artifacts start private. Nothing is shared until you share it.
- Pro, Max and Ultra: "Only you" or "Anyone with the link," plus email invitations to specific people (beta).
- Team and Enterprise: "Only people invited," "Anyone at [your organization]," or "Anyone with the link" if an Owner turned on external sharing. Enterprise can also share with groups.
- Sharing settings can't be changed in the iPhone or Android apps. Use the web or desktop app.
- Shared artifacts use each viewer's own connections. If a viewer can't reach a data source, that part shows an error. The exception is a Claude Data dashboard with live sharing.
- When you share an artifact made in a chat, viewers also get the attachments and files in that chat.
- Unpublishing permanently deletes the artifact's stored data.

## Connectors
Sources: [Use connectors to extend Claude's capabilities](https://support.claude.com/en/articles/11176164-use-connectors-to-extend-claude-s-capabilities), [Use Google Workspace connectors](https://support.claude.com/en/articles/10166901-use-google-workspace-connectors)
- Connectors let Claude reach your apps, read data and act in them, with your own permissions in that app.
- Turn one on in Customize, then Connectors, or from the + in a chat, then Connectors, then Manage connectors.
- A connected app isn't on in every chat automatically. Turn it on per chat from the + menu.
- Team and Enterprise: an Owner enables connectors for the organization first, then each person signs in.
- Google Drive, Gmail and Google Calendar connectors are available to all users. The Drive connector can read Sheets, Slides, PDFs and Office files, text only.
- Anthropic says to connect only services you trust and need.

## Scheduled tasks
Source: [Schedule recurring tasks in Claude Cowork](https://support.claude.com/en/articles/13854387-schedule-recurring-tasks-in-claude-cowork)
- Available on Pro, Max, Ultra, Team and Enterprise.
- Frequency: hourly, daily, weekly, on weekdays, or on demand. No monthly option is listed.
- Tasks run in the cloud, even when your computer is asleep, unless they use a folder on your computer.
- They can use connectors, skills and files saved to your Claude account.

## Projects
Source: [What are projects?](https://support.claude.com/en/articles/9517075-what-are-projects)
- A Project is a workspace with its own chats, files and instructions. Free accounts can make up to five.

## Uploads
Source: [Upload files to Claude](https://support.claude.com/en/articles/8241126-upload-files-to-claude)
- Claude reads PDF, DOCX, CSV, TXT, XLSX and other files. Up to 20 files per chat. Project files up to 30 MB each.
- Excel (XLSX) uploads need code execution and file creation turned on.

## HIPAA
Sources: [HIPAA-ready Enterprise plans](https://support.claude.com/en/articles/13296973-hipaa-ready-enterprise-plans), [Business Associate Agreements (BAA) for commercial customers](https://privacy.claude.com/en/articles/8114513-business-associate-agreements-baa-for-commercial-customers)
- Only Claude Enterprise can enable HIPAA and a BAA. Team, Free, Pro, Max and Ultra can't.
- Even under the BAA, Anthropic lists connectors, skills, and publishing or sharing artifacts as not covered.
- The dashboard in this skill uses totals only, so it needs no patient information on any plan.

## Not found on Anthropic's pages
- Whether Claude Data accepts uploaded CSV files as a source (the help article names only warehouses and connected apps).
- Any direct connector for med spa booking or EMR systems.
- A monthly option for scheduled tasks.
