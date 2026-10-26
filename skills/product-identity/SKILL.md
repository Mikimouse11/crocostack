---
name: product-identity
description: Rules for SKUs, GTINs (UPC, EAN, ISBN), MPNs, and finding duplicate products. Use when reviewing SKUs, barcodes, product identifiers, or duplicates.
---

# Product identity

- Every variant has a SKU. A SKU is unique across the store and is never reused, even after its product is deleted.
- SKUs are used to connect products between different databases (ecommerce platform, accounting, warehouse, etc) so don't change SKUs in any one place without explicit reason.
- A SKU may encode stable facts such as type, color, and size. It must not encode facts that change, such as price, supplier, or season.
- A GTIN comes from the barcode the manufacturer assigned. Never generate, guess, or copy one. For your own brand, buy GTINs from GS1.
- Each variant has its own GTIN. The same GTIN on two variants is a data error or a duplicate.
- Validate every GTIN: 8, 12, 13, or 14 digits and a correct check digit.
- Store GTINs as text. Spreadsheets drop leading zeros and turn long numbers into scientific notation.
- If no GTIN exists (handmade, custom, or vintage goods), leave the field empty. Never put the SKU in it. Use brand plus MPN where the manufacturer has an MPN.
- Two products with the same GTIN, or the same brand and MPN, are one product. Merge them.
