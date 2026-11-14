---
title: "10 - Sensitive Information"
dateCreated: 2026-11-13
status: draft-2026
tags:
  - theme/writing
  - theme/craft
---
# 10 - Sensitive information

Internal docs feel private, so people paste things they shouldn't. But internal docs get shared, exported, screenshotted, and searched. **Treat every doc like it could leave the building.**

> **Template note:** Notes like this are instructions for whoever sets up the guide. **Delete them before you publish.** (How to customize: §00.)

## Never put these in docs

- Passwords, API keys, tokens, and other credentials
- [Customer names and data]
- [Employee personal information, like personal email addresses, home addresses, and phone numbers]
- [Financial account details]
- [Health information]
- [Security details, like server names, IP addresses, and internal URLs]
- [Unreleased product or business plans]

> **Customize (D3):** Keep the items you checked in D3. Credentials always stay on the list.

## Point to it instead

Tell readers where to find sensitive information without including it:

- **Yes:** Get the admin password from the "Payroll admin" entry in [password manager].
- **No:** The admin password is Summer2026!

**Where it lives:** [password manager or secure location, from D3]
**Questions about where something should live?** Ask [contact, from D3].

## Use placeholders in examples

- **Credentials:** `YOUR_API_KEY`, `your-password-here`
- **Websites and email:** example.com, name@example.com (these domains are reserved for examples)
- **Phone numbers:** 555-0100 through 555-0199 (reserved for fictional use in the US)
- **People:** made-up names, never real customers or coworkers

## Check screenshots before you share

Blur or crop names, email addresses, account numbers, and anything else on the list above. Also check the edges of the screen: browser tabs, bookmarks, and notifications can give away more than you think.

## Labels and legal requirements

- **Label confidential docs:** [required notice from D4, for example "Confidential: Internal use only"]
- **Our requirements:** [privacy laws, regulations, or audits from D4]
- **Not sure?** Ask [legal or compliance contact] before you publish.

> **Customize (D4):** Add your required labels and legal requirements. If none apply, delete this subsection.

## If something sensitive gets posted

1. **Tell [contact, from D3] right away.**
2. **Remove it,** but don't assume that's enough. Page history, search indexes, and notifications can keep a copy.
3. **If it was a password or key, change it.** Once a secret has been posted, treat it as public.
