# Changelog

All notable changes to the Style Guide Content (the template sections and questionnaire) are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html), adapted for content:

- **Major:** a section is restructured, or the questionnaire YAML schema changes in a way that could break someone's adapted copy.
- **Minor:** new questions, options, or template sections.
- **Patch:** wording fixes, clarifications, and typo corrections.

## [Unreleased]

## [1.0.1] - 2026-11-20

### Added

- This changelog.
- A questionnaire map (`docs/questionnaire-map.md`) showing how each answer connects to the template sections, with a list of the template’s marker types.
- A basic release checklist (`RELEASING.md`).

### Changed 

- Clarified the scope of §11: it covers using AI tools to write docs, not general AI policy, and its title is now "Using AI tools to write docs." 
- Removed internal editing metadata (tags, status, and dates) from the section files. Only `title` remains.

## [1.0.0] - 2026-11-14

### Added

- First public release of the Internal Documentation Style Guide Template as 13 modular Markdown sections.
- The Style Guide Questionnaire as structured YAML: 40 questions (76 form fields) across five parts (A Setup, B Audience and voice, C Formatting, D Content policies, E Maintenance).
- Answer-to-section tagging, so every customizable rule names the question that decides it.
- Baseline references: Microsoft Writing Style Guide (primary), Chicago Manual of Style 18th edition (fallback), and Merriam-Webster (spelling).
- CC BY-SA 4.0 license.

[Unreleased]: https://github.com/katmoody/style-guide-content/compare/v1.0.1...HEAD
[1.0.1]: https://github.com/katmoody/style-guide-content/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/katmoody/style-guide-content/releases/tag/v1.0.0
