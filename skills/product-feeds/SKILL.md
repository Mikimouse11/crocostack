---
name: product-feeds
description: Rules for sending catalog data to Google Shopping, Meta, and marketplaces. Use when reviewing product feeds, feed errors, disapprovals, or channel mapping.
---

# Product feeds

- A feed is a shared view of the product catalog. Main use cases are advertising (Google Shopping or Meta) or marketplaces.
- Fix the data in the catalog, not with feed rules. Use feed rules only where a channel needs a different format.
- Every item needs a unique ID, title, description, link, image, price, availability, brand, condition, and a GTIN or a flag that none exists. See `product-identity`.
- Send each variant as its own item, grouped under a shared item group ID.
- Feed titles can differ from storefront titles. Channels reward attributes in the title, so add color and size for each variant here, unlike on the storefront.
- Map products to the channel's own taxonomy (such as Google product category).
- Price, sale price, currency, and availability must match the landing page exactly.
- Leave out products you can't ship to the channel's region, and products with no image.
- Read channel diagnostics as an audit. Each rejection reason points to a gap in the catalog.
