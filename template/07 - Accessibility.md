---
title: "07 - Accessibility"
---
# 07 - Accessibility

Accessible docs work for everyone, including people who use screen readers, magnifiers, captions, or keyboard-only navigation. Accessibility covers a wide range of disabilities: visual, auditory, physical, speech, cognitive, language, learning, and neurological. Most of the time, accessible writing is simply clear writing.

> **Template note:** Notes like this are instructions for whoever sets up the guide. **Delete them before you publish.** (How to customize: §00.)

## Our target

We follow the basics of the [Web Content Accessibility Guidelines (WCAG) 2.2](https://www.w3.org/TR/WCAG22/), Level AA. WCAG is written mostly for websites and apps. For docs, the rules below cover what writers need day to day.

> **Customize (D1):** If you have your own accessibility policy, link it here and note any differences.

## Structure

- **Use headings in order.** Don't skip levels (H2 to H4). Screen reader users jump between headings to find what they need.
- **Use real lists**, made with your tool's list button, not dashes or numbers typed by hand.
- **Write descriptive link text:** "See the expense policy," not "click here." Screen reader users often scan a list of links out of context.
- **Use tables for data, not layout,** and give every table a header row.

## Language

- **Use plain language.** Short sentences, common words, one idea per sentence (see §06 and §09).
- **Use emoji sparingly** (at most one per heading or message), and never in place of words. A string of emoji is hard to read for people with visual processing difficulties, and screen readers read each one aloud.
- **Avoid ALL CAPS and heavy bold.** Both are harder to read, and some screen readers spell out all-caps words letter by letter.

## Images and media

- **Add alt text to every meaningful image.** Describe what the image shows and why it matters: "Settings menu with **Notifications** highlighted." Mark purely decorative images as decorative.
- **Don't put important text only in an image.** Screenshots of text can't be searched, translated, or read aloud. Type it out too.
- **Add captions or a transcript** to video and audio.

## Color and contrast

- **Never use color as the only way to show meaning.** "The red items are urgent" fails readers who can't see red. Add a label or icon: "Items marked **Urgent**."
- **Keep text easy to see.** Use your tool's default text colors, and avoid light gray text or text over busy images.

## Check your work

- **Run your tool's built-in accessibility checker,** if it has one.
- **For web pages, use [WAVE](https://wave.webaim.org/),** a free checker from WebAIM.
- **Try three quick manual tests:** navigate with only your keyboard, zoom to 200%, and listen to a page with a screen reader (VoiceOver is built into Mac; [NVDA](https://www.nvaccess.org/) is free for Windows).

Automated checkers catch only some problems, so the manual tests matter.

> **Customize (D1):** List the checkers your team uses, and who to ask for help.

## Learn more

- [W3C: Introduction to web accessibility](https://www.w3.org/WAI/fundamentals/accessibility-intro/)
- [W3C: Writing for web accessibility](https://www.w3.org/WAI/tips/writing/)
- [WebAIM: WCAG 2 checklist](https://webaim.org/standards/wcag/checklist)
- [Google developer documentation style guide: Accessibility](https://developers.google.com/style/accessibility)
