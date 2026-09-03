# Workflow

## 1. Direct Intake from the GEO Order Workbook (primary)

The primary input is the client-filled `国际版GEO下单表` workbook. It usually contains:

- `GEO项目下单表`: enterprise, contact, brand, product keywords, social accounts, blog URL, and other supplementary information.
- `制造行业-九大单元表`: a manufacturer-form sheet with A = unit, B = field name, C = content (English), D = instructions.
- `服务行业-九大单元表格资料`: a service-provider-form sheet with the same A/B/C/D layout.

The completed form may contain one or both industry sheets. Decide the client type only from real client-filled content:

- Manufacturer when the filled content uses factory language: production lines, OEM/ODM, raw materials, models and dimensions, MOQ, capacity, lead time, certifications, FOB/CIF, inspection.
- Service provider when the filled content uses service language: solutions, methodology, service process, consulting, delivery, cases, result metrics.
- Ignore template examples (`ABC Fan`), column D fill-in references, demo figures such as `USD 5000`, `10+ years`, and any example case content when classifying.

State the decision and its evidence briefly, then continue. Once the type is chosen, use only the matching client sheet; never mix content from the other industry sheet into the final nine units.

## 2. Template Selection and Row Clearing

- Manufacturer: `assets/manufacturer-nine-unit-template.xlsx` (8 sheets).
- Service provider: `assets/service-provider-nine-unit-template.xlsx` (9 sheets).

Both templates contain an `ABC Fan` example row on row 2 of the filled sheets. Clear row 2 completely before writing client content. Never add, delete, rename, or reorder sheets, columns, rows, or headers.

## 3. Field Mapping

Read the client sheet row by row. The unit is in column A (merged cells repeat the unit down the block), the field name is in column B, and the content to export is in column C. Column D is guidance only.

Match each B-column field name to the official template header of the same name and place C into that column. Fields in the source with no matching template column are not exported. Template columns without client data stay blank.

See [field-mapping.md](field-mapping.md) for manufacturer and service-provider field lists and for the small alias set used when source names differ from template headers.

## 4. Two Workbooks

Every task exports two structurally identical workbooks:

- English original: sheet names and row 1 headers keep the official Chinese template text; data cells copy the client's English content verbatim. If a client field mixes Chinese instruction text with English, only translate the explanatory part into English and keep all identifiers unchanged.
- Chinese analysis version: same sheet names, same headers, same cell positions; natural-language content is translated to Chinese. Numbers, percentages, dimensions, models, series, certification numbers, standard numbers, dates, URLs, emails, phones, units, and material codes remain byte-for-byte unchanged.

The two workbooks must have identical sheet order, row 1 headers, and identical filled/blank cell positions. The meaning of every exported field must be exactly equivalent.

## 5. Missing Checklist

Missing information is tracked outside the final nine-unit workbooks in a separate `XX_补充资料清单.xlsx` table or Feishu doc with columns: unit / missing field / what to ask the client to provide.

Inside the nine-unit workbooks, leave missing fields blank. Do not write `N/A`, `TBD`, `待补充`, or placeholders. Do not invent facts, figures, cases, certifications, or testimonials.

## 6. Final Verification

1. Recheck the client-type evidence.
2. Confirm the template sample row was cleared.
3. Compare the two exports: sheet order, sheet names, row 1 headers, and blank/non-blank cell positions.
4. Check that English content is copied, not rewritten, and Chinese content preserves all numbers and identifiers.
5. Confirm the missing checklist is not inside either nine-unit workbook.
6. Confirm only real client content is present.
