---
name: filters
description: Rules for choosing storefront filters and cleaning the attribute data behind them. Use when reviewing filters, facets, product attributes, or metafields used for filtering.
---

# Filters

- Filters show attribute data. A bad filter almost always means bad data, so fix the data before the filter settings.
- Choose filters per category: the 3 to 6 attributes shoppers decide on in that category. Price and availability apply almost everywhere.
- Drop a filter when fewer than about 70% of the products in the category have a value for it.
- Drop a filter when one value covers more than 90% of the products. It filters nothing.
- Normalize values to one unit, one spelling, and one case. "Navy", "navy blue", and "Dark Blue" become one value.
- For colors, filter on a color family ("Blue") and keep the specific name ("Navy") on the variant.
- Write values in the shopper's language, never supplier codes.
