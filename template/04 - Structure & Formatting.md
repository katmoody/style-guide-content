---
title: "04 - Structure & Formatting"
dateCreated: Tuesday, March 28th 2023, 7:07:58 pm
dateModified: Friday, November 13th 2026, 4:47:00 pm
tags:
  - theme/writing
  - theme/craft
status: draft-2026
---
# 04 - Structure & formatting

How you structure and format a doc decides whether people can find what they need. Good formatting makes docs easier to scan, follow, and update.

> **Template note:** Notes like this are instructions for whoever sets up the guide. **Delete them before you publish.** (How to customize: §00.)

## Titles and headings

<!-- choose C1 -->
<!-- option "Title Case" -->
- **Use Title Case for page titles:** "How to Reset Your Password." Capitalize the major words.
<!-- option * -->
- **Use sentence case for page titles:** "How to reset your password." Capitalize only the first word and proper nouns.
<!-- end choose -->
<!-- choose C1b -->
<!-- option "Title Case" -->
- **Use Title Case for headings inside a page.**
<!-- option "Same as page titles" -->
- **Capitalize headings the same way as page titles.**
<!-- option * -->
- **Use sentence case for headings inside a page.**
<!-- end choose -->
- **Make titles specific.** Readers should know what they'll get before they click: "Request time off," not "PTO stuff."
- **Use one H1 (the page title), then headings in order.** Don't skip levels (H2 to H4). Readers and screen readers use headings to navigate (see §07).
- **Put the most important words first** in a heading, so it's easy to scan.

> **Customize (C1):** If you chose Title Case, update the first rule and example.

## Lists

Lists break content into pieces that are easy to scan. But if everything on a page is a list, nothing is. Use paragraphs when ideas need explaining.

- **Use numbered lists for steps in order.** Use bullets for everything else.
- **Make items parallel.** If one item starts with a verb, they all should.
<!-- choose C2b -->
<!-- option "Yes" -->
- **Start each item with a capital letter.**
<!-- option "No" -->
- **Start items with a lowercase letter,** unless the first word is a proper noun.
<!-- end choose -->
<!-- choose C2 -->
<!-- option "Always use periods" -->
- **End every list item with a period.**
<!-- option "Never use periods" -->
- **Don't end list items with periods,** even when they're complete sentences.
<!-- option * -->
- **End items with periods only when they're complete sentences.**
<!-- end choose -->
- **Keep nesting to two levels.** If you need more, the content probably needs headings instead.

> **Customize (C2):** Update the punctuation and capitalization rules to match your answers.

## Steps

- **One action per step.**
- **Start each step with the action:** "Select **Save**."
- **Say where before what:** "In **Settings**, select **Notifications**."
- **Put conditions first:** "If you don't see the menu, refresh the page."
- **Tell readers what happens** when it isn't obvious: "A confirmation message appears."

For full step-by-step templates, see §05.

## Bold, italics, and emphasis

<!-- choose C4 -->
<!-- option "Our own rule" -->
- [Your team's rule for bold and italics, from C4.]
<!-- option * -->
- **Use bold** for UI labels and for warnings readers must not miss.
- **Use italics** for the titles of books, reports, and other works.
<!-- end choose -->
- **Don't underline text** that isn't a link. Readers will try to click it.
- **Don't use ALL CAPS** for emphasis. It reads like shouting and is harder to read.
<!-- choose B7 -->
<!-- option "Never" -->
- **Don't use emoji or GIFs** in docs.
<!-- option "Freely" -->
- **Emoji and GIFs are welcome,** but never in place of words, and never in a string (see §07).
<!-- option * -->
- **Use emoji sparingly:** at most one per heading or message, and never in place of words (see §07).
<!-- end choose -->

If everything is bold, nothing is. Save emphasis for what matters most.

> **Customize (C4, B7):** Update these rules if you chose your own bold and italics rule, or a different emoji policy.

## UI elements, code, and keyboard keys

<!-- choose C7 -->
<!-- option "Quotes" -->
- **Put the names of buttons, menus, and other on-screen labels in quotation marks,** and match the screen exactly: Select "Save changes."
<!-- option * -->
- **Bold the names of buttons, menus, and other on-screen labels,** and match the screen exactly: "Select **Save changes**."
<!-- end choose -->
- **Use "select"** for buttons and menu items. It works whether someone uses a mouse, touchscreen, or keyboard.
- **Use code formatting** for commands, file names, file paths, and variables: `config.yml`, `npm install`.
<!-- choose C7b -->
<!-- option "Ctrl + C" -->
- **Write keyboard shortcuts with spaces around the plus sign:** Ctrl + C (Windows), Command + C (Mac).
<!-- option "Ctrl+C" -->
- **Write keyboard shortcuts like this:** Ctrl+C (Windows), Command+C (Mac).
<!-- option * -->
- **Write keyboard shortcuts like this:** [your team's style, from C7].
<!-- end choose -->

> **Customize (C7):** Update these rules if you chose quotation marks for UI labels or a different shortcut style.

## Callouts: notes, tips, and warnings

Use callouts to set apart information that doesn't fit in the main text. As a rule of thumb, use no more than one per section. When every other paragraph is a note, readers stop reading them.

| Label | Use it for |
| --- | --- |
| **Note** | Helpful extra information |
| **Tip** | A shortcut or easier way to do something |
| **Important** | Something readers need to know to succeed |
| **Warning** | Anything that could lose data, break something, or create a security risk |

[Use your tool's built-in callout boxes, like Confluence panels or Notion callouts.]

> **Customize (C8):** Keep only the labels you chose, and name your tool's callout feature.

## Links

- **Write descriptive link text:** "See the onboarding checklist," not "click here."
- **Link to the source of truth,** not a copy of it.
- **Don't overdo it.** Too many links make a page hard to read. Link the first mention, not every mention.
<!-- choose C9 -->
<!-- option "Fine, when" -->
- **Linking outside the company:** link only to reputable sources: official vendor docs, standards bodies, and the sources in §13.
<!-- option "Approved sources only" -->
- **Linking outside the company:** link only to approved sources: [list them here or link to the list].
<!-- option "Ask the guide owner" -->
- **Linking outside the company:** ask [guide owner, from A2] first.
<!-- end choose -->
- [If your tool has a special link style, like Confluence smart links with the page icon and title, say when to use it.]

> **Customize (C9b):** Add your tool's link style, if it has one.

## Images, screenshots, and video

Use images and video to show what words can't, like where a button is or how a process flows. They should support the text, not replace it.

- **Add alt text** to every meaningful image (see §07).
- **Crop screenshots** to the part that matters.
- **Blur or crop anything sensitive,** like customer names, emails, or passwords (see §10).
- **Choose the right format:** a short GIF or video to show an action, a screenshot to show where something is.
- **Get permission** to use images or media from outside sources. Yes, even internally.
- **Update screenshots** when the screen changes. An outdated screenshot causes more confusion than none at all.

**Our image settings:** [maximum width, file formats, and highlight or arrow style, from C10.]

> **Customize (C10):** Add your image sizes, formats, and annotation style.

## Tables

- **Use tables for data you want to compare,** not for page layout.
- **Always include a header row.**
- **Keep them simple.** If a table needs scrolling in every direction, split it up or use a list.

## Color

- **Never use color as the only way to show meaning** (see §07).
- [Brand colors for highlights, tables, or diagrams, if you use them, from C11.]

> **Customize (C11):** Add brand colors if you chose to use them. Otherwise, delete that line.
