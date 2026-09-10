# skyHire portal (preview)

Interactive wireframe for skyHire, covering two roles in one page.

**Live preview:** https://yaswanthramp.github.io/skyhire-referrals-preview/

Switch role in the header. Both roles read and write one document store, so nothing has to be
kept in step between them.

## Member

The employee portal. Refer people, track them, run your own onboarding, and keep your record right.

- **Overview** referral KPIs, openings matched to your network, live status feed
- **Open Roles** filterable openings with description, eligibility and bonus; Refer on every card
- **Role detail** full description, eligibility checklist, interview process, bonus split
- **My Referrals** six-stage pipeline per referee, with a detail drawer and full timeline
- **My Documents** your own file only, plus whatever HR has asked you for, with upload
- **My Profile** what Skypoint holds about you, your onboarding tasks, and change requests
- **Rewards** paid, pending and in-pipeline bonuses, and the payout rules

## Admin (HR Operations)

The Candidate Document Centre. Every candidate folder in one workspace.

- **Folders** a folder per candidate, keyed on candidate ID, with completion meters
- **All documents** every document across candidates, with bulk actions
- **Missing** what has not arrived, due dates and reminders
- **Hired** pre-onboarding verification and the handoff to the employee record
- **Candidate folder** category tabs, checklist, audit trail, and a review drawer that verifies
- **Onboarding** start a new hire, track their task list, and decide on everything they send in
- **Approvals** one queue for submitted documents and employee change requests, approve or reject

## The point of it

Request documents from a candidate as the admin, switch to Member, and the request is waiting,
naming who asked and why. Upload as the member, switch to Admin, and the file is already in the
folder marked for review. One record, two surfaces, no second store.

The same holds for the rest of the employee record. An employee asks to change their address and
attaches proof; HR sees the old and new values side by side and either approves it, which is the
only thing that writes to the record, or rejects it with a reason the employee reads word for
word. Nothing changes quietly, and there is always a trail of who changed what and why.

Built with the Radix flavour of the Skypoint design system (Radix Colors 12-step scales, Radix
Themes geometry, Skypoint amber, Inter). Light and dark themes. Single page, no build step.

All names, roles and figures are sample data.
