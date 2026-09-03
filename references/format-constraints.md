# Final Export Format Constraints

## Client Type First

Before exporting, classify the client as manufacturer or service provider using only real client-filled content. Template examples (`ABC Fan`), column D fill-in references, demo figures such as `USD 5000`, `10+ years`, and any prebuilt example cases are never evidence for classification.

## Hard Rules

The final exported workbook must strictly match one of these two templates:

- `assets/service-provider-nine-unit-template.xlsx`
- `assets/manufacturer-nine-unit-template.xlsx`

Choose the template by business type:

- Service provider: use the service-provider template.
- Manufacturer: use the manufacturer template.

Do not change any of the following:

- Sheet names.
- Sheet order.
- Column names.
- Column order.
- Number of sheets.
- Number of columns.
- Number of data rows required by the template.

Before writing client content, clear every `ABC Fan` example value from the template so the final workbook contains only client material. Each sheet keeps the official template structure: one header row plus one data row. If a service-provider sheet currently stores only a header row, still keep the header + data-row structure used by the manufacturer template.

Do not add any of the following inside the final workbook:

- Extra sheets.
- Extra columns.
- Extra rows.
- A `缺失提示` sheet.
- A Feishu link or supplemental-information sheet.

## Missing Values

- Leave unprovided fields blank.
- Do not write placeholder text such as "待补充", "TBD", "N/A", or "None" into final content cells.
- Do not invent facts, cases, testimonials, certifications, or metrics.

## Source Content Boundary

- Column C of the client form is the content to export.
- Column D (填写说明 / 填写参考 and similar) is instruction or example text. Never export it as final content.
- Preserve the client's original English wording in the English original export; do not "fix" or rewrite it.
- After the client type is chosen, use only the matching industry sheet; never merge content from the other industry sheet.
- Source fields that have no matching template column are not exported.
- Template columns without client data stay blank and go to the separate missing checklist.

## Supplemental Information

Missing and supplemental information is handled outside the final workbook:

- Create a separate table.
- Or create a Feishu doc with a missing-field checklist and use its link for client follow-up.

The supplemental link or table is never part of the final nine-unit export.

## Bilingual Deliverables

Every task exports two workbooks:

- English original: official Chinese sheet names and row-1 field titles; data cells contain the client's English content.
- Chinese analysis version: identical sheet names, row-1 field titles, and blank/non-blank structure; natural-language content is translated to Chinese.

Both versions must keep numbers, percentages, dimensions, models, series, certification numbers, standard numbers, dates, URLs, emails, phones, and units exactly as in the client source. The two files must have the same sheet order and the same filled/blank cells. The Chinese version is for internal reading: translate explanatory sentences, keep structured values and identifiers untouched, and never add figures or facts that are absent from the client source.

## Verification Before Delivery

1. Confirm the correct template is selected.
2. Confirm the client-type evidence is real client content.
3. Confirm the `ABC Fan` example row was cleared before filling.
4. Compare sheet names and sheet order.
5. Compare column names and column order.
6. Confirm there are no extra sheets or columns.
7. Confirm every missing cell is blank.
8. Confirm the missing checklist is outside the final workbook.
9. Compare the English original and Chinese analysis versions for identical structure and equivalent content.
