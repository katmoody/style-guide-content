# Releasing 

Run this before every push. 

- [ ] Changed a question? Update `docs/questionnaire-map.md` in the same push
- [ ] Renamed a section? Search for the old title (YAML, §03 table, changelog)
- [ ] Don’t rename section files (the builder may look them up by filename)
- [ ] Changelog: move `[Unreleased]` items into a version with today’s date and pick major, minor or patch by your rules
- [ ] No stray `<!-- TODO -->` notes or empty sections
- [ ] After pushing: open `/guide` on the live site and check that the change shows up
