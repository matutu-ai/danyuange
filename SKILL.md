---
name: danyuange
description: Turn simple Chinese client input into bilingual international-edition nine content units, including simple feed templates, content analysis, missing-item prompts, and English output with unchanged numbers. Use when a client only provides basic company/product/service information and the final deliverable is the nine-unit workbook for GEO or overseas marketing.
---

# Danyuange

This skill turns a simple client intake form into the full nine content units used for international GEO or overseas marketing content.

## Workflow

1. Give the client `assets/simple-feed-template.xlsx`. The client fills the form in Chinese and leaves missing answers blank.
2. Analyze the fed content before expanding it. Identify brand words, business words, Q&A words, scenario words, covered fields, and missing fields.
3. Choose the correct standard nine-unit template:
   - Service provider: `assets/service-provider-nine-unit-template.xlsx`
   - Manufacturer: `assets/manufacturer-nine-unit-template.xlsx`
4. Generate a Chinese nine-unit workbook from the client's real information.
5. Generate an English-filled nine-unit workbook with the same Chinese sheet names and field titles, but English content in the data cells. Keep all numbers unchanged.
6. Add a final missing-information prompt sheet listing every field the client has not provided.

## Required Rules

- Client input stage: Chinese is allowed.
- Final nine-unit content: English.
- Sheet names and field titles: keep Chinese.
- Numbers, percentages, dimensions, years, models, and dates: unchanged.
- Missing content: leave blank. Do not invent facts, cases, testimonials, or metrics.
- Chinese and English versions must have the same structure and the same empty/non-empty cells.

## References

- Read [references/workflow.md](references/workflow.md) for the complete runnable process.
- Read [references/field-mapping.md](references/field-mapping.md) when mapping simple intake answers to the nine-unit fields.

## Assets

- `assets/simple-feed-template.xlsx`: blank 10-question client intake form.
- `assets/service-provider-nine-unit-template.xlsx`: standard service-provider nine-unit workbook.
- `assets/manufacturer-nine-unit-template.xlsx`: standard manufacturer nine-unit workbook.
