---
name: danyuange
description: Turn simple Chinese client input or an official website into bilingual international-edition nine content units, including website analysis, simple feed templates, content analysis, missing-item prompts, and English output with unchanged numbers. Use when a client provides basic company/product/service information or a website URL and the final deliverable is the nine-unit workbook for GEO or overseas marketing.
---

# Danyuange

This skill turns a simple client intake form into the full nine content units used for international GEO or overseas marketing content.

## Workflow

1. Give the client `assets/simple-feed-template.xlsx`, or accept an official website URL. The client fills the form in Chinese and leaves missing answers blank.
2. If an official website is provided, open and analyze the relevant pages before expanding. Extract company background, products/services, customers, cases, certifications, contact details, and trust signals.
3. Analyze all collected content before expanding it. Identify brand words, business words, Q&A words, scenario words, covered fields, and missing fields.
4. Choose the correct standard nine-unit template:
   - Service provider: `assets/service-provider-nine-unit-template.xlsx`
   - Manufacturer: `assets/manufacturer-nine-unit-template.xlsx`
5. Generate a Chinese nine-unit workbook from the client's real information.
6. Generate an English-filled nine-unit workbook with the same Chinese sheet names and field titles, but English content in the data cells. Keep all numbers unchanged.
7. Add a final missing-information prompt sheet listing every field the client has not provided.

## Required Rules

- Client input stage: Chinese is allowed.
- Final nine-unit content: English.
- Sheet names and field titles: keep Chinese.
- Numbers, percentages, dimensions, years, models, and dates: unchanged.
- Missing content: leave blank. Do not invent facts, cases, testimonials, or metrics.
- Website content is client-provided source material only when it is accessible and belongs to the client. Do not use unrelated third-party claims.
- Chinese and English versions must have the same structure and the same empty/non-empty cells.
- Final export must strictly match one of the two standard templates. Do not add, remove, rename, or reorder sheets, columns, or rows. Do not add a missing-prompt sheet inside the final workbook.
- Missing and supplemental information belongs in a separate intermediate channel, not inside the final nine-unit workbook. When a Feishu integration is available, create a Feishu doc with the missing-field checklist and use its link for client follow-up.

## References

- Read [references/workflow.md](references/workflow.md) for the complete runnable process.
- Read [references/field-mapping.md](references/field-mapping.md) when mapping simple intake answers to the nine-unit fields.
- Read [references/format-constraints.md](references/format-constraints.md) before producing any final export.

## Assets

- `assets/simple-feed-template.xlsx`: blank client intake form, including official website/online store.
- `assets/service-provider-nine-unit-template.xlsx`: standard service-provider nine-unit workbook.
- `assets/manufacturer-nine-unit-template.xlsx`: standard manufacturer nine-unit workbook.
