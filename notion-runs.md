# Native Notion databases for sourcing runs

Use an authorized native Notion database under the output hub linked in [README.md](README.md#notion-deliverables). View access to the public review page does not imply write access. Lina must explicitly grant the operator the access needed for a run.

## Row identity and counts

One unique person is one row per run. Deduplicate canonical identity links within the run. Add every distinct, readable, role-plausible discovered person to that database, including people awaiting technical assessment. A run that finds 105 people must show all 105 rows in All people.

Five and ten are review checkpoints within the same run, not new databases. Discovery, assessments, human decisions and drafts update the same rows. Never make static candidate tables, alphabetic table fragments, checkpoint copies or a separate draft queue.

## Properties

- Name: title; Profile, GitHub and Source: URLs.
- Stage: Discovered / Needs verification / Assessed / Reviewed.
- Initial screen: Advance / Needs verification / Deprioritize.
- Evidence band: Standout / Strong / Decent / Mixed / Weak for this role / Needs verification.
- Confidence: High / Medium / Low.
- Reason or concern, Feedback, Next check and Discovery query: text.
- Lina Decision: Proceed / Hold / Pass; blank is awaiting a decision. Human controlled.
- Observed on: date; Contact email: email; Sender: text.
- Draft subject and Draft body: text.
- Draft status: Not drafted / Draft / Needs sender feedback / Ready for approval / Approved / Sent / Delivery unknown / Do not contact.
- Template approved and Recipient approved: checkboxes, changed only from explicit human approval.
- Delivery receipt: URL; keep provider IDs and execution details in the row page.

Put current experience, up to three prior workplaces where listed, education, substantive implementation evidence, identity-match notes, source observations and sender feedback inside the row page. Unassessed people keep Stage Discovered and unknown assessment/decision fields blank. Do not rate unknown work as average or weak.

## Views of the same database

- **All people:** native table with no permanent filter, showing every row. Show Name, Profile, Stage, Evidence band, Reason or concern, Lina Decision, Feedback and Draft status. Quick filters may help review; clear them before counting the entire run.
- **Review:** same data source, filtered to Stage Assessed or Reviewed. Show Name, Profile, Evidence band, Confidence, Reason or concern, Lina Decision, Feedback and Next check.
- **Drafts:** same data source, filtered to Draft body is not empty. Show Name, Contact email, Sender, Draft subject, Draft body, Draft status, Template approved and Recipient approved.

Enable cell wrapping and freeze the Name column. Additional filtered views are allowed; additional candidate databases within a run are not.

## Write and verify

Fetch the native database and data source schema before writing. Create row pages under its data source. Reconcile uncertain writes, deduplicate identities and preserve existing human fields. Read back each delivered row.

Query the complete unfiltered data source, paginate to exhaustion and verify distinct row count. Report discovered, assessed and reviewed counts separately. Confirm a stated 105-person run really contains 105 distinct rows, not 105 search results or a view limited to a subset.

Return the exact database/view link at each checkpoint. Save run stage, counts, query trials, current feedback checkpoint and next action in the database description or its parent page. Resume only the active run; never restore deleted candidate records from local caches. Sending still requires the separate template, recipient and explicit execution approvals in [email-handoff.md](email-handoff.md).
