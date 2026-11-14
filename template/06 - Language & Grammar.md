---
title: "06 - Language & Grammar"
dateCreated: Tuesday, March 28th 2023, 7:08:20 pm
dateModified: Friday, November 13th 2026, 4:48:48 pm
tags:
  - theme/writing
  - theme/language
status: draft-2026
---
# 06 - Language & grammar

Clear, concise, and easy for anyone on the team to read.

> **Template note:** Notes like this are instructions for whoever sets up the guide. **Delete them before you publish.** (How to customize: §00.)

## Our references

This guide covers the rules our team uses most. For anything it doesn't cover:

- **Main reference:** [Microsoft Writing Style Guide](https://learn.microsoft.com/en-us/style-guide/welcome/) (free online)
- **Grammar and punctuation:** *The Chicago Manual of Style*, 18th edition. Chicago's [Q&A pages](https://www.chicagomanualofstyle.org/qanda/latest.html) are free to read.
- **Spelling:** [Merriam-Webster](https://www.merriam-webster.com/). When it lists more than one spelling, use the first one.

**If this guide and one of our references disagree on a language or grammar question, follow this guide.**

> **Customize (B3, B8):** Swap in your main reference, grammar fallback, and dictionary. For UK English, use an Oxford dictionary instead of Merriam-Webster.

## Tone

Tone is the mood of your writing. Ours is **professional but friendly**: easy to read, still trustworthy. Write the way you'd explain something to one of your coworkers.

| Instead of this | Write this |
| --- | --- |
| Utilize the dashboard functionality to facilitate report generation. | Use the dashboard to create reports. |
| It should be noted that access requests may take some time. | Access requests can take up to two days. |
| This is super easy, just hit the button lol | Select **Submit**. |

- **Be concise.** Cut words that don't add meaning.
- **Be specific.** "Up to two days" beats "some time."
- **Skip idioms and slang.** They confuse readers who speak English as a second language and trip up translation tools (see §09).

> **Customize (B4):** If you chose formal or conversational, rewrite the first paragraph and the table to match.

## Voice

Voice is how your docs sound to the reader. Keep it consistent across every doc, no matter who writes it.

### Talk to the reader as "you"

Write as though you're talking to the person reading. For steps, start with the action (this is called the **imperative**): "Select **Export**." The "you" is implied.

- **Yes:** You can export reports as PDFs. To export one, select **Export**.
- **No:** The user can export reports as PDFs. Users should select **Export**.

Use the third person for what software or other people do: "The system sends a confirmation email."

> **Customize (B5):** If you chose third person, flip these examples and explain why (for example, formal compliance docs).

### Use "we" for the team

In internal docs, the reader is part of the team, so "we" includes them: "We ship updates on Fridays." It makes docs feel personal and helps new teammates feel like they belong.

- **Make it clear which "we."** If it could mean the company, your team, or the docs team, name the team: "The support team reviews tickets daily."
- **Use "you" for steps, not "we."** Write "Select **Save**," not "Now we select **Save**."
- **Don't let "we" hide an owner.** "We should update this page" leaves it to no one. Name who: "[Team or person] updates this page each quarter."

> **Why this differs from some style guides:** Customer-facing guides, like Microsoft's, often avoid "we" because there it means the company talking *at* a customer. In internal docs, "we" includes the reader.
>
> **Customize (B5):** If you chose not to use "we," replace this subsection with: "Avoid 'we.' Name the team instead."

### Use active voice

The subject does the action in **active voice**. It's shorter and makes clear who does what.

- **Yes:** The finance team approves all purchase requests.
- **No:** All purchase requests are approved by the finance team.

**Not sure which one you wrote? Try the zombie test.** Add "by zombies" after the verb. If the sentence still makes sense, it's passive.

- "All purchase requests are approved *by zombies*." Makes sense, so it's passive.
- "The finance team approves *by zombies* all purchase requests." Nonsense, so it's active.

*(The zombie test was popularized by Rebecca Johnson of Marine Corps University. [Read more about it at Mental Floss](https://www.mentalfloss.com/language/grammar/passive-voice-why-everyone-gets-it-wrong).)*

Passive voice is fine when the actor doesn't matter or is unknown: "The file was deleted."

### Use present tense

Docs describe how things work now. Future tense makes readers wonder when it'll be true.

- **Yes:** The report shows last month's totals.
- **No:** The report will show last month's totals.

### Use contractions

Common contractions (*it's*, *you're*, *don't*) sound friendly and natural. Avoid awkward ones like *there'd*, *it'll*, and *they'd*.

For warnings where a missed word could cause harm, spell it out: "Do **not** delete this folder."

> **Customize (B6):** If you chose no contractions, replace this subsection with: "Spell out contractions (*do not*, *you will*)."

### Use gender-neutral language

When you don't know someone's gender, use "they," or rewrite with "you" or a role ("the requester"). See §08 for more.

## Spelling and word choice

- **[Company]** is always written exactly this way. Not: [common mistakes from A1].
- Use [US] English spelling.

### Word list

Use the same word for the same thing, every time. When a new term comes up, suggest it to [guide owner, from A2], who adds it here (see §12).

| Use | Not | Notes |
| --- | --- | --- |
| email | e-mail | |
| log in (verb), login (noun) | log-in | "Log in to the portal." "Your login expired." |
| set up (verb), setup (noun) | set-up | "Set up your account." "Finish the setup." |
| back up (verb), backup (noun) | back-up | "Back up your files." "Restore from the backup." |
| check out (verb), checkout (noun) | check-out | "Check out the new dashboard." "Go to checkout." |
| allowlist, blocklist | whitelist, blacklist | See §08 |
| [Your product or tool name] | [Common misspelling] | |

> **Customize (A1, B3, D2):** Replace the starter rows with your own terms. Keep this list short and real. It grows best from actual questions.

## Abbreviations and acronyms

- **Spell it out first.** On first use, write the full term followed by the acronym in parentheses: "single sign-on (SSO)." After that, use the acronym.
- **Skip the spell-out for acronyms everyone knows better than the full term,** like PDF, URL, and USB. If spelling it out would make readers stop and think ("universal serial bus?"), don't. A good sign: the acronym is in the dictionary.
- **Use only acronyms your readers know.** If most readers would have to stop and think, spell it out.
- **Don't introduce an acronym you only use once.**
- **Skip the possessive.** Write "the API settings," not "the API's settings."
- **Don't start a heading with a new acronym.** Define it in the text first.
- **Write out common Latin abbreviations.** Use "for example" instead of *e.g.*, "that is" instead of *i.e.*, and "and so on" (or a complete list) instead of *etc.* They're easy to mix up and hard for readers who speak English as a second language.

| Acronym | Meaning | Spell out on first use? |
| --- | --- | --- |
| API | application programming interface | Yes |
| FAQ | frequently asked questions | No |
| PDF | Portable Document Format | No |
| SSO | single sign-on | Yes |
| TLS | Transport Layer Security | Yes |
| UI | user interface | Yes |
| URL | uniform resource locator | No |
| VPN | virtual private network | Yes |
| [Your acronym] | [What it means] | [Yes or no] |

> **Customize (A1, B1):** Replace these with your team's acronyms, especially internal ones (team names, project code names, tool nicknames). Set the last column based on your readers: a developer team may never need "API" spelled out. New hires will thank you.

## Punctuation

Punctuation isn't noticeable when it's done right. But when it's done wrong, it can change the meaning.

> Let's eat, Grandma.
> Let's eat Grandma.
>
> This is a classic example of a comma placement to die for.

- **In a list of three or more, put a comma before the last item** (the *serial comma*, also called the Oxford comma): "docs, slides, and spreadsheets."
- **When two words work together to describe a noun, hyphenate them** (a *compound modifier*): "a high-quality image." No hyphen when they come after the noun: "the image is high quality."
- **Use an en dash (–) for ranges:** "pages 5–10," "9:00 AM–5:00 PM." It's a little longer than a hyphen.
  - **Mac:** Option + hyphen
  - **Windows:** Alt + 0150 (on the number pad)
  - **HTML or Markdown:** `&ndash;`
- **Use em dashes (—) sparingly, with no spaces.** A comma, colon, or parentheses usually work better.
  - **Mac:** Option + Shift + hyphen
  - **Windows:** Alt + 0151 (on the number pad)
  - **HTML or Markdown:** `&mdash;`
- **Put periods and commas inside quotation marks.**
  - **Yes:** Call it "the dashboard."
  - **No:** Call it "the dashboard".
- **Use semicolons sparingly.** Two short sentences are usually clearer than one long one.
  - **Instead of:** The team worked on the project for months; it's finally ready to present.
  - **Try:** The team worked on the project for months. It's finally ready to present.
- **Skip exclamation points** in most docs. Save them for real excitement, like a launch announcement.

> **Customize (C3, C5, B3):** If you chose no serial comma, update the first rule. If you chose hyphens ("5-10") or words ("5 to 10") for ranges, replace the en dash rule. In UK English, punctuation goes outside the quotation marks unless it's part of the quote.

## Numbers and units

- **Technical values are always numerals:** version numbers, measurements, pixels, ports, error codes, numbers in the UI, and anything the reader types. Put a space before a unit: "5 GB," "3 inches," "16 px."
- **For everyday counts in sentences, spell out zero through nine and use numerals for 10 and up:** "five steps," "15 users."
- **Spell out a number that starts a sentence,** or rewrite the sentence so it doesn't start with one.
- **Use commas in numbers with four or more digits:** "1,000," "25,000." **Except** years, ports, version numbers, and codes: "2026," "port 8080."
- **Units we use often:** [list from C5, for example GB, MB, px].

> **Customize (C5):** If you chose Chicago's rule, change the everyday-counts bullet to "spell out one through one hundred." If you chose always numerals, delete that bullet.

## Dates and times

- **Spell out the month:** November 13, 2026. Don't use ordinals like "November 13th."
- **Avoid all-number dates** like 11/12/2026 in running text. Readers in different countries read them differently.
- **Times:** 3:00 PM. Use "noon" and "midnight," not "12:00 noon."
- **Time zones:** Include one for meetings and deadlines: "3:00 PM ET." For global teams, use Coordinated Universal Time (UTC).

> **Customize (C6):** Swap in your date format, 12- or 24-hour time, and default time zone.

## Citations and sources

When you borrow from another source, credit it. In most internal docs, a link is enough.

- **Link inline with descriptive text:** "See the [security team's password policy](#)."
- **For quotes or code snippets,** put the link right below them.
- **Link only to reputable sources.** [Add your approved sources or link-out policy from C9.]

> **Customize (C9, C12):** If you chose a formal citation style, name it here and link to its guide.

## Before you publish

Run through the editing checklist in §02. Have questions about this section? Contact [guide owner, from A2].

## Learn more

- [Microsoft Writing Style Guide: Person](https://learn.microsoft.com/en-us/style-guide/grammar/person)
- [Microsoft Writing Style Guide: Use contractions](https://learn.microsoft.com/en-us/style-guide/word-choice/use-contractions)
- [Microsoft Writing Style Guide: Acronyms](https://learn.microsoft.com/en-us/style-guide/acronyms)
- [Microsoft Writing Style Guide: Numbers](https://learn.microsoft.com/en-us/style-guide/numbers)
- [Microsoft Writing Style Guide: Date and time terms](https://learn.microsoft.com/en-us/style-guide/a-z-word-list-term-collections/term-collections/date-time-terms)
- [Microsoft Writing Style Guide: Units of measure](https://learn.microsoft.com/en-us/style-guide/a-z-word-list-term-collections/term-collections/units-of-measure-terms)
- [The Chicago Manual of Style Q&A](https://www.chicagomanualofstyle.org/qanda/latest.html)
