# Workflow

## 1. Simple Intake

Use `assets/simple-feed-template.xlsx` as the first deliverable. The client does not need to understand the nine units.

Accept one or both of these sources:

- Completed simple intake form.
- Official website or online store URL.

The intake questions are:

1. Company name.
2. One-sentence description of what the company does.
3. Main products or services.
4. Target customers.
5. Main customer pain points.
6. Three differentiators, preferably with numbers.
7. Service process from consultation to after-sales.
8. Real cases and outcomes.
9. Official website or online store.
10. Address, phone, WhatsApp, email.
11. Photos, certificates, and authorizations.

## 2. Website Analysis

When an official website is provided, open the relevant pages before expanding:

- Home page: positioning, slogan, main products/services.
- About page: company background, history, scale, certifications.
- Products or services pages: categories, specifications, use scenarios, features.
- Cases or projects page: real customers, project context, outcomes.
- Contact page: address, phone, WhatsApp, email, online store.

Treat website content as source material. If the website is inaccessible or does not belong to the client, stop and ask for an alternative source before guessing.

## 3. Content Analysis

Before generating the nine units, produce a short analysis:

- Brand words.
- Business/search words (without region in the words themselves).
- Q&A words.
- Scenario-intent words.
- Covered content.
- Missing content.

## 4. Nine-Unit Generation

Choose the template by business type:

- Service provider: `assets/service-provider-nine-unit-template.xlsx`
- Manufacturer: `assets/manufacturer-nine-unit-template.xlsx`

Fill only from the client's real material. Leave every unprovided field blank.

## 5. Chinese and English Deliverables

Produce two workbooks:

- Chinese version: Chinese sheet names, Chinese field titles, Chinese content.
- English-filled version: same Chinese sheet names and field titles, but content cells in English.

Both workbooks must have identical sheet order, headers, and empty/non-empty cell positions.

## 6. Language and Number Rules

- Client input: Chinese.
- Final content: English.
- Sheet names and field titles: Chinese.
- Numbers and units: unchanged.
- Missing values: blank.

## 7. Missing Prompt

Do not add a missing-prompt sheet inside the final nine-unit workbook. Instead, produce a separate missing-information table or Feishu doc that lists:

- The missing unit or general material.
- The missing field.
- What the client needs to provide.

Keep prompting only for real missing information. Do not create substitute data.

When a Feishu integration is available, create a Feishu doc for the missing checklist and give the client its link. When Feishu is not available, use a separate local spreadsheet.

## 8. Strict Final Export

Before delivery, verify the final export against `assets/service-provider-nine-unit-template.xlsx` or `assets/manufacturer-nine-unit-template.xlsx`:

- The correct template must be selected by business type.
- Sheet names, sheet order, column names, and column order must match exactly.
- No extra sheets, no extra columns, no extra rows, and no removed fields.
- No `缺失提示` sheet inside the final workbook.
- Missing values stay blank.

See [format-constraints.md](format-constraints.md) for the complete immutable-format checklist.
