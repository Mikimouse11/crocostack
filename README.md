# Crocostack

Crocostack is a plugin of short skill files that tell an agent the non-obvious rules for improving an ecommerce catalog.

These skills exist so the agent loads the specific rules for the job at hand, such as categories, descriptions, images, titles, variants, or filters, judges the current catalog against those rules, and proposes the edits.

The plugin is Markdown skills only. It does not run commands, call APIs, or send catalog data anywhere. Claude reads the skill text in the conversation and works with the catalog files or admin tools you already have open.

## Use it

Install the plugin, then ask Claude to audit, clean up, or improve products, collections, or the catalog. Start with `catalog-audit` when you want a full pass; it loads the other skills in order. For a narrower job, ask about titles, variants, images, SEO, feeds, or filters and the matching skill is used.

## Layout

```
.claude-plugin/plugin.json
.cursor-plugin/plugin.json
LICENSE
README.md
skills/
```

`.claude-plugin/plugin.json` is the Claude Code and Claude directory manifest. `.cursor-plugin/plugin.json` points `skills` at `./skills/` for Cursor. Each skill is a directory with a `SKILL.md`: `skills/<name>/SKILL.md`.
