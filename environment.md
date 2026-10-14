# Tools and access for internship sourcing

## Research environment

Use Codex with this repository, Exa search and page reading, public web/GitHub reading and the [Bluejay take-home overview](https://app.notion.com/p/3f814dfefe6781699efbf43f9f69a5ca) and [candidate review output](https://app.notion.com/p/5537a615c85f48d69e0b8954bf6e0d7b). These are the current Notion pages shared with Rohan as view-only. Check tool access at the start of a run. Search connectivity and candidate quality are separate checks. Contact information requires identity-supported evidence.

No local server, standalone model key or always-on daemon is required. Provider usage limits apply. Python 3.11+ is needed only for source tests and offline helpers.

## Reusable skills

Load these skills in the Codex environment used for the work. They are reusable Codex procedures; their full definitions are not bundled in this public repository.

| Skill | When to use it |
| --- | --- |
| `source-recruiting-prospects` | Required for fresh sourcing, intern-level assessment and verified delivery to the private Notion run database. |
| `discover-recruiting-queries` | Required alongside sourcing to compare discovery routes, deduplicate people and maintain query history. |
| `source-bluejay-interns` | Bluejay-specific compatibility entry point. It routes to `source-recruiting-prospects` and the current internship instructions; it is not a separate search method. |
| `review-github` | Inspect candidate code and attribute implementation without executing candidate code. |
| `write-outreach` | Use only when outreach drafts are requested; follow sender setup and approval steps in [email-handoff.md](email-handoff.md). |
| `learn-ranking` | Interpret attributed feedback and propose evidence-supported process changes. Do not silently change active criteria. |

Start with the prompt in [the review guide](README.md). Read the relevant skills before using them.

## Operator capabilities

- Codex with the authorized research and public web/GitHub reading tools.
- Access to the linked Notion overview and candidate review output. Do not assume access to other private Notion pages; Lina must grant access if an additional source is required.
- The review criteria and sender handoff described in [README.md](README.md) and [email-handoff.md](email-handoff.md).

## Operator and sender access

Each operator needs their own Codex session, repository access, connected research tools and explicitly granted access to the required Notion records. Keep credentials private and grant only the access authorized for the task. A filtered Notion view is not an access boundary.

For outreach, use [sender setup](email-handoff.md). Codex needs a mail tool authenticated as the named sender, private writing guidance, feedback on five calibration drafts, an approved template and recipient batch, and an explicit send instruction. Pending mailbox access or writing feedback holds sending while authorized discovery continues.
