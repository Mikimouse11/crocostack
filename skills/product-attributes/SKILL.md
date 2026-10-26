---
name: product-attributes
description: Rules for structured product data such as material, dimensions, and color. Use when reviewing attributes, metafields, specs, or missing product data. Filters, titles, descriptions, and feeds all depend on this data.
---

# Product attributes

- Define one required attribute set for each product type. A T-shirt needs material, fit, and size. A lamp needs bulb type, wattage, and dimensions.
- Store attributes in structured fields, not in the description. Text inside a paragraph can't drive a filter, a feed, or a comparison.
- Give each attribute one name and one unit across the store. Add unit in the attribute name for clarity. Convert units when you display them, not in the data.
- Use strict data types whenever possible. A number or a fixed list of allowed values. Allow free text only for values that are truly open.
- Store numbers as numbers: "40", not "approx. 40cm".
- Values describe the product, not the pitch: "Cotton", not "Premium soft cotton".
- Put attributes that differ between variants (size, color) on the variant. Put shared attributes on the product.
- Report coverage for each required attribute and product type. Fill a gap from the supplier or the manufacturer, never by guessing.
