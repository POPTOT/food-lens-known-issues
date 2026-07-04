# Food Lens Known Issues

Public evidence database for Food Lens.

This repository stores documented product and brand red flags such as:

- lawsuits and court filings
- recalls and regulator notices
- independent lab findings
- contaminants such as PFAS, bromate, glyphosate, heavy metals, microplastics, acrylamide

The app can download `known_issues.json`, cache it on the phone, and match scanned products by barcode, brand, product name, and category.

## Main files

- `known_issues.json` - the database consumed by the app
- `known_issues.schema.json` - validation schema for database entries
- `SOURCE_POLICY.md` - rules for what can be included

## Wording rule

Food Lens can be direct, but each claim must be sourced.

Good:

- `Glyphosate was detected in independent lab testing.`
- `This brand was named in a lawsuit over acrylamide exposure.`
- `A regulator announced a recall for this product.`

Avoid:

- `This product causes cancer.`
- `The company poisoned people.`
- `This product is illegal.`

Unless the source says exactly that and the legal context is clear.
