---
title: "05 - Document Types & Templates"
dateCreated: Friday, November 13th 2026, 11:52:40 am
dateModified: Friday, November 13th 2026, 4:47:03 pm
status: draft-2026
tags:
  - theme/writing
  - theme/craft
---
# 05 - Document types & templates

When docs of the same type share the same structure, readers know where to look. Writers don't have to start from a blank page, either. Copy a template, fill it in, and delete what you don't need.

> **Template note:** Notes like this are instructions for whoever sets up the guide. **Delete them before you publish.** (How to customize: §00.)

## Where our docs live

Docs spread across tools fast. Before long, nobody knows which doc lives in Google Docs, which is only in Word, and which exists only in a Slack thread. Our Documentation Map answers that question in one place.

| Type of doc | Where it lives | Source of truth? | Owner |
| --- | --- | --- | --- |
| [Help articles] | [Confluence: Help space] | [Yes] | [Support team] |
| [Processes (SOPs)] | [Google Drive: Ops folder] | [Yes] | [Operations lead] |
| [Team updates] | [Slack: #team-updates] | [No; archived monthly to Confluence] | [Team leads] |

**When docs disagree, the source of truth wins.** If you find a conflict, fix the copy or tell the owner.

> **Customize (A4, B1):** Fill in one row per type of doc, using your answers about where docs live and who reads them. Keep the map somewhere everyone can find it, and update it when something moves.

## Templates

### How-to guide

For a task someone needs to complete.

```markdown
# [Do the task], for example "Request time off"

[One sentence: what this helps you do, and when you'd need it.]

## Before you start
- [Access, tools, or information needed]

## Steps
1. [First action]
2. [Next action]

## What happens next
[What the reader should see or expect.]

## Related
- [Link to related docs]
```

### Reference

For information people look up: settings, policies, specs, contacts.

```markdown
# [Topic], for example "Expense limits by role"

[One sentence: what this covers.]

## [Topic details]
[A table works well here.]

## Related
- [Link to related docs]
```

### Troubleshooting

For fixing a specific problem.

```markdown
# [Problem, in the words people use], for example "Can't connect to the VPN"

## Symptoms
[What the reader sees.]

## Cause
[Why it happens, if known.]

## Solution
1. [First thing to try]
2. [Next thing to try]

## Still stuck?
Contact [team or channel].
```

### Process or standard operating procedure (SOP)

For work that has to be done the same way every time.

```markdown
# [Process name], for example "Monthly payroll close"

**Owner:** [Name or role]
**Last reviewed:** [Date]

## Purpose
[Why this process exists.]

## When to use it
[Trigger or schedule.]

## Steps
1. [Step, and who does it]

## Exceptions
[What to do when something doesn't fit.]
```

### Explainer

For a concept or "how this works."

```markdown
# [Concept], for example "How our on-call rotation works"

## What it is
## Why it matters
## How it works
## Related
```

### FAQs

Use FAQs sparingly. They tend to become a dumping ground for answers that belong in a real doc. When a question comes up again and again, fix the doc it came from, then link to it.

> **Customize (A6):** Keep templates for the doc types you write most. Delete the rest, or add your own.

## Starting points

Many tools include starter templates you can adapt, including Confluence and Notion. For more examples, see [The Good Docs Project](https://www.thegooddocsproject.dev/), a free collection of documentation templates.
