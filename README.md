# Crocostack

Crocostack is a Cursor plugin of short skill files that tell an agent the non-obvious rules for improving an ecommerce catalog.

These skills exist so the agent loads the specific rules for the job at hand, such as categories, descriptions, images, titles, variants, or filters, judges the current catalog against those rules, and proposes the edits.

## Layout

```
.cursor-plugin/plugin.json
skills/
```

`.cursor-plugin/plugin.json` points `skills` at `./skills/`. Each skill is a directory with a `SKILL.md`: `skills/<name>/SKILL.md`.
