# Source Policy

Food Lens can speak directly, but every red flag must be tied to a source.

## Allowed source types

Strong sources:

- regulator notices and recall databases
- court filings and official case records
- published lab reports with product/brand names
- peer-reviewed studies when the product/category match is clear
- reputable investigative reports that link to primary evidence

Use with caution:

- news articles without primary documents
- social posts summarizing another source
- broad category studies that do not name a product or brand

Do not use:

- anonymous claims
- unsourced screenshots
- viral captions with no source
- claims that name a product but link only to generic health content

## Wording levels

### Confirmed product finding

Use when a source identifies a specific product or barcode.

Example:

`Glyphosate was detected in independent lab testing of this product.`

### Brand issue

Use when the source identifies a brand or product line, but not the exact scanned barcode.

Example:

`This brand has documented glyphosate findings in third-party testing.`

### Category risk

Use when the source is about a product category, not a specific brand.

Example:

`Bottled water is a category with documented microplastic contamination risk.`

## Lawsuit wording

Lawsuits are allegations unless there is a judgment or settlement admission.

Allowed:

- `This brand was named in a lawsuit over acrylamide exposure.`
- `A lawsuit alleged that the product exposed consumers to acrylamide.`

Avoid:

- `This product causes cancer.`
- `The company knowingly poisoned consumers.`

## Severity guidance

- `critical`: recall, regulator violation, confirmed severe contaminant over limit
- `high`: named product lab finding, serious lawsuit, high-risk contaminant
- `medium`: brand-level finding or category finding with strong evidence
- `low`: weak match, broad category issue, historical issue with limited current relevance

## Score penalty guidance

- 0-5: category warning, low confidence
- 5-15: brand-level documented issue
- 15-30: product-level lab finding or serious lawsuit
- 30-60: recall, legal limit exceedance, severe contaminant finding

## Update rule

Every active issue must have at least one source URL. If a source is removed, moved, or contradicted by newer evidence, archive or update the issue.
