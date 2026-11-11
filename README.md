# Income Sprint — Local Business Dashboard Pilot

**Owner:** Jayent Singh Parihar  
**Sprint date:** November 11, 2026  
**Stage:** Outreach preparation and pilot validation

## Project overview

Income Sprint is an early-stage freelance service project helping small businesses turn an Excel or CSV enquiry sheet into a clear, one-page dashboard. The initial focus is event companies and a marketing agency in Nagpur.

The goal is to validate a ₹2,999 dashboard pilot, demonstrate the value of enquiry and follow-up tracking, and develop a repeatable workflow for finding prospects, agreeing scope, delivering dashboards, and recording results.

This repository document is a project plan. It does not contain a working application or implemented automation. Prospect descriptions and the sprint ledger below are supplied project information, not independently verified research. Businesses’ current reporting tools and interest remain unverified.

## Pilot offer

| Item | Scope |
| --- | --- |
| Fixed price | ₹2,999 |
| Data source | One Excel or CSV source |
| Deliverable | One-page dashboard in Excel or Power BI |
| Metrics | Up to five |
| Revisions | One |
| Delivery | Within two business days after the file and scope are agreed |

Agree the dashboard format, source columns, metric definitions, and revision expectations before starting.

## Prospect shortlist

| Priority | Prospect | Dashboard angle | Public contact |
| --- | --- | --- | --- |
| 1 | Sterling Events | Track event enquiries, pending quotes, and confirmed bookings by event type. | [Business website](https://www.sterlingevents.co.in/) |
| 2 | Avenza Marketing | Track the agency’s own sales pipeline across marketing and graphic design services. | [Business website](https://www.avenzamarketing.in/) |
| 3 | Innovations Solutions & Events | Track enquiries through booking for corporate events, weddings, and celebrations. | [Contact page](https://innovationsevents.com/contact-us/) |

Start with Sterling Events. Its stated mix of weddings and corporate events provides a concrete demo: which enquiries turn into bookings and which quotes still need a follow-up. Confirm each prospect’s services and appropriate contact channel before outreach.

## Outreach drafts

These are drafts for review; this document does not authorize sending them.

### Sterling Events

> Hi Sterling Events team, I saw that you handle both corporate events and weddings. If you track enquiries and quotes in Excel, I can turn that sheet into a one-page dashboard showing pending quotes, confirmed bookings, and booked value by event type. I’m offering a ₹2,999 pilot. Would you like to see a sample built with fictional event data?  
> — Jayent Singh Parihar

### Avenza Marketing

> Hi Avenza team, I saw that you offer both performance marketing and graphic design. If you track your own sales enquiries in Excel, I can build a one-page dashboard showing which services attract enquiries, which proposals are open, and what you’ve won. The pilot is ₹2,999. Would you be open to seeing a sample?  
> — Jayent Singh Parihar

### Innovations Solutions & Events

> Hi Innovations team, I saw that you plan corporate events, weddings, and celebrations. If you keep an enquiry spreadsheet, I can turn it into a one-page dashboard that shows what’s awaiting a quote, what’s booked, and which follow-ups are due. The pilot is ₹2,999. Would a sample be useful?  
> — Jayent Singh Parihar

## Event dashboard demo specification

Use fictional event data and label the dashboard **“Demonstration data — not actual client results.”**

### Five proposed metrics

| Metric | Proposed definition |
| --- | --- |
| Enquiries | Count of unique enquiry IDs in the selected period |
| Open quotes | Count of enquiries with a quote sent and no confirmed, lost, or cancelled outcome |
| Confirmed bookings | Count of enquiries with status Confirmed |
| Booked value | Sum of agreed booking values for confirmed bookings, in INR; this is not cash collected |
| Overdue follow-ups | Count of active enquiries with a next follow-up date before the dashboard’s as-of date |

Use enquiry date for the initial period filter and clearly display the as-of date. Confirm these definitions with the client before delivery.

### Suggested source columns

- Enquiry ID
- Enquiry date
- Customer or company name
- Event type
- Event date
- Enquiry source
- Status
- Quote amount (INR)
- Confirmed booking value (INR)
- Last contact date
- Next follow-up date
- Notes

Suggested statuses: New, Contacted, Quote Sent, Confirmed, Lost, Cancelled.

### Proposed one-page layout

1. Five metric cards at the top.
2. Enquiries and bookings by event type.
3. A table of open quotes and overdue follow-ups.
4. A visible reporting period, as-of date, and demonstration-data label.

## Delivery workflow

1. Build the fictional-data demo.
2. Review the Sterling Events pitch and verify the contact channel.
3. Send only after explicit authorization and record the actual send date.
4. If interested, confirm the prospect’s current process and reporting needs.
5. Agree the pilot scope and receive the source file securely.
6. Validate the data and agree how to handle missing or duplicate entries.
7. Build the dashboard and reconcile totals against the source.
8. Deliver within the agreed two-business-day window.
9. Complete one agreed revision.
10. Record the outcome, invoice status, payment received, and feedback separately.

Keep real client data, credentials, and payment information out of a public repository. Use fictional or properly anonymized examples for portfolio demonstrations.

## Planned automation

These capabilities are proposed, not implemented:

- Prospect status tracking and follow-up reminders.
- Reusable outreach and proposal drafts.
- Source-file validation and duplicate checks.
- Dashboard refresh workflows.
- Project delivery checklists.
- Separate tracking of quotes, invoices, costs, and cash received.

Any future messaging automation should retain explicit authorization before sending. Income depends on client demand and completed sales; this project makes no earnings guarantee.

## Sprint ledger — supplied snapshot

| Activity | Recorded amount |
| --- | ---: |
| Leads researched, as reported in the supplied sprint | 3 |
| Pitches drafted | 3 |
| Sends by the agent | 0 |
| Quotes issued | 0 |
| Amount invoiced | ₹0 |
| Amount spent | ₹0 |

Any outreach, replies, or cash received outside the supplied sprint remain unverified. No verified downloads, active users, client results, or revenue figures are available.

## Next actions

- [ ] Prepare the fictional event dashboard sample.
- [ ] Review the Sterling Events pitch first.
- [ ] Verify its current services and public business contact channel.
- [ ] Obtain authorization before sending outreach.
- [ ] Record replies and agree a pilot scope if there is interest.
- [ ] Update the sprint ledger with evidence of completed actions.

## Uploading this document to GitHub

Upload this file as `README.md` in the repository root. GitHub will display it as the project’s introduction. Uploading this document does not create the dashboard or activate any automation.

