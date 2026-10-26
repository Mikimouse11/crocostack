---
name: catalog-audit
description: Entry point for improving an ecommerce catalog. Use when asked to audit, review, clean up, or improve products, collections, or the catalog as a whole. Picks which other Crocostack skills to load.
---

# Catalog audit

Fix structure before content. Work in this order and load the matching skill for each step:

1. `product-variants`
2. `categories`
3. `product-titles`
4. `filters`
5. `product-descriptions`
6. `product-images`

A rewritten description is wasted on a product that should have been merged into another as a variant.

## Rules

- Judge from a sample that includes the top sellers, the newest products, and the long tail. Top sellers alone hide the mess.
- Report patterns, not instances. "212 titles start with the SKU" is one finding with one rule, followed by the edits.
- Rank findings by revenue at stake. Fix top sellers and the busiest categories first.
- Propose edits. Don't apply them. Show each edit as the current value, the proposed value, and the rule behind it.
- Never invent product facts. If material, dimensions, or compatibility is missing, flag the gap instead of filling it.
