# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **14** URLs; **12** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Homepage and Welcome**, **Understanding Severe Sweating**, **Frequently Asked Questions**. **41** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:57:40.632Z
- **Website**: https://www.botoxseveresweating.com/
- **Total Pages Analyzed**: 14
- **Total Templates Identified**: 12
- **Total Components Identified**: 41
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BOTOXSEVERESWEATING.COM TEMPLATES                                        │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage and Welcome                 │    │ Understanding Severe Sweating        │    │ Frequently Asked Questions           │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │
│ • Hero Banner                        │    │ • Hero Banner {Unmapped}             │    │ • FAQ Hero Banner                    │
│ • Main Content {Unmapped}            │    │ • Main Navigation {Unmapped}         │    │ • FAQ Accordion                      │
│ • Footer Section                     │    │ • Content Introduction {Unmapped}    │    │ • Call-to-Action Columns             │
│ • (+2 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Website Sitemap                      │    │ Treatment Results                    │    │ Treatment Experience                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Header                        │    │ • Global Navigation {Unmapped}       │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Main Banner {Unmapped}             │    │ • Primary Navigation {Unmapped}      │
│ • Hero Banner                        │    │ • Treatment Results Section {Unmapp… │    │ • Hero Section                       │
│ • Sitemap Section {Unmapped}         │    │ • Call-to-Action Boxes {Unmapped}    │    │ • Content Columns {Unmapped}         │
│ • (+4 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Diagnosis Information                │    │ Mechanism of Botox                   │    │ Is Botox Right for Me?               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Hero Section {Unmapped}            │    │ • How Botox Works {Unmapped}         │    │ • Quiz Section {Unmapped}            │
│ • Content Introduction {Unmapped}    │    │ • Sweat Explanation {Unmapped}       │    │ • Quiz Results {Unmapped}            │
│ • (+7 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BOTOXSEVERESWEATING.COM — SUB-TEMPLATES TEMPLATES                        │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Find a Dermatologist                 │    │ Savings and Insurance                │    │ Contact Information                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Utility Strip               │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation                 │    │ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Main Navigation                    │    │ • Hero Section {Unmapped}            │
│ • Search Form                        │    │ • Hero Banner                        │    │ • CTA Columns {Unmapped}             │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Homepage and Welcome (`tpl_0`) — 2 pages

- Global Navigation {Unmapped}
- Hero Banner
- Main Content {Unmapped}
- Footer Section
- Floating ISI {Unmapped}
- Modal Popup

### Understanding Severe Sweating (`tpl_1`) — 1 pages

- Global Navigation {Unmapped}
- Hero Banner {Unmapped}
- Main Navigation {Unmapped}
- Content Introduction {Unmapped}
- Content Columns {Unmapped}
- Call-to-Action Boxes {Unmapped}
- Footer
- Important Safety Information {Unmapped}

### Frequently Asked Questions (`tpl_2`) — 1 pages

- Global Navigation {Unmapped}
- FAQ Hero Banner
- FAQ Accordion
- Call-to-Action Columns
- Safety Information Section {Unmapped}
- Footer

### Website Sitemap (`tpl_3`) — 1 pages

- Site Header
- Primary Navigation {Unmapped}
- Hero Banner
- Sitemap Section {Unmapped}
- Call-to-Action Boxes {Unmapped}
- Important Safety Information {Unmapped}
- Site Footer
- Floating Safety Information {Unmapped}

### Treatment Results (`tpl_4`) — 1 pages

- Global Navigation {Unmapped}
- Main Banner {Unmapped}
- Treatment Results Section {Unmapped}
- Call-to-Action Boxes {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Treatment Experience (`tpl_5`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Call-to-Action Boxes {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Diagnosis Information (`tpl_6`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Introduction {Unmapped}
- Consultation Information {Unmapped}
- Preparation for Appointment {Unmapped}
- Treatment Options {Unmapped}
- Call-to-Action Boxes {Unmapped}
- Popup Information {Unmapped}
- Important Safety Information {Unmapped}
- Footer {Unmapped}

### Mechanism of Botox (`tpl_7`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section {Unmapped}
- How Botox Works {Unmapped}
- Sweat Explanation {Unmapped}
- CTA Quiz {Unmapped}
- CTA Find Doctor {Unmapped}
- CTA Results {Unmapped}
- Important Safety Information {Unmapped}
- Footer Section {Unmapped}

### Is Botox Right for Me? (`tpl_8`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Quiz Section {Unmapped}
- Quiz Results {Unmapped}
- Call-to-Action Boxes {Unmapped}
- Footer
- Important Safety Information {Unmapped}
- Floating ISI {Unmapped}

### Find a Dermatologist (`tpl_9`) — 1 pages

- Global Header
- Primary Navigation
- Hero Section
- Search Form
- Search Results
- Terms Modal
- Footer
- Floating ISI

### Savings and Insurance (`tpl_10`) — 1 pages

- Global Utility Strip
- Primary Header
- Main Navigation
- Hero Banner
- Call to Action Section
- Information Section
- Important Safety Information
- Footer

### Contact Information (`tpl_11`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- CTA Columns {Unmapped}
- Safety Information {Unmapped}
- Footer
- Floating ISI {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Footer                                  │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Important Safety Information {Unmapped} │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Call-to-Action Boxes {Unmapped}         │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Global Navigation {Unmapped}            │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Primary Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Floating ISI {Unmapped}                 │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Banner                             │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Hero Section                            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Hero Section {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Content Columns {Unmapped}              │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Content Introduction {Unmapped}         │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Global Utility Strip {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                              │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Call to Action Section                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Columns                 │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Consultation Information {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ CTA Columns {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Find Doctor {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Quiz {Unmapped}                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Results {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Accordion                          │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Hero Banner                        │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Floating ISI                           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Floating Safety Information {Unmapped} │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Section                         │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage and Welcome (2 pgs)                                                                      │
│ • Understanding Severe Sweating (1 pgs)                                                             │
│ • Frequently Asked Questions (1 pgs)                                                                │
│ • Website Sitemap (1 pgs)                                                                           │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Treatment Results (1 pgs)                                                                         │
│ • Treatment Experience (1 pgs)                                                                      │
│ • Diagnosis Information (1 pgs)                                                                     │
│ • Mechanism of Botox (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Is Botox Right for Me? (1 pgs)                                                                    │
│ • Find a Dermatologist (1 pgs)                                                                      │
│ • Savings and Insurance (1 pgs)                                                                     │
│ • Contact Information (1 pgs)                                                                       │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


## Template Rationale Summary

### Why this template view helps

1. **Scalability**: New pages can be checked against existing template buckets.
2. **Consistency**: Grouping highlights shared layout patterns across sections.
3. **Maintainability**: Updates to a template concept apply to all URLs in that bucket.
4. **Performance**: Shared layouts suggest shared static assets and caching opportunities.
5. **Content operations**: Editors can map content types to template patterns.

### Next steps

- Tune AEM mappings in **block-mapping.csv** and re-run if the site uses custom blocks.
- Refine **human_name** / **description** via the template agent when using signature or agent grouping modes.

## Usage Instructions

1. **Diagram**: Template boxes reflect **page_count** from this run; names come from clustering + optional LLM labelling.
2. **Matrices**: Populated from extract-blocks + AEM catalog mapping.
3. **Phases**: Suggested prioritization by crawl traffic (page counts), not project schedule.
4. **Appendix**: Source-of-truth table for IDs, URLs, and counts.
5. **block-mapping.csv** (in the same output directory): stakeholder matrix aligned with `src/resources/block-mapping.csv` column headers.

## Appendix: Template index (table)

| template_id | human_name | description | example_urls | page_count |
| --- | --- | --- | --- | --- |
| tpl_0 | Homepage and Welcome | The main landing pages of the website, providing an overview and entry point. | https://www.botoxseveresweating.com/, https://www.botoxseveresweating.com/Home/index | 2 |
| tpl_1 | Understanding Severe Sweating | Pages explaining the condition, its implications, and introductory information for readers. | https://www.botoxseveresweating.com/about_severe_underarm_sweating/what_is | 1 |
| tpl_2 | Frequently Asked Questions | A section addressing common inquiries about severe sweating and its management. | https://www.botoxseveresweating.com/FAQ | 1 |
| tpl_3 | Website Sitemap | A sitemap page listing all navigable links and sections of the site. | https://www.botoxseveresweating.com/Site_map | 1 |
| tpl_4 | Treatment Results | Details and testimonials regarding the outcomes of Botox treatments. | https://www.botoxseveresweating.com/Can_botox_help/results | 1 |
| tpl_5 | Treatment Experience | Insights into the process and experiences of undergoing Botox treatments. | https://www.botoxseveresweating.com/Can_botox_help/treatment_experience | 1 |
| tpl_6 | Diagnosis Information | Guidance on how severe sweating is diagnosed. | https://www.botoxseveresweating.com/about_severe_underarm_sweating/how_diagnosed | 1 |
| tpl_7 | Mechanism of Botox | Explains how Botox works in treating severe sweating. | https://www.botoxseveresweating.com/Can_botox_help/how_works | 1 |
| tpl_8 | Is Botox Right for Me? | A quiz or assessment tool to determine the suitability of Botox treatment. | https://www.botoxseveresweating.com/Can_botox_help/is_botox_right_for_me | 1 |
| tpl_9 | Find a Dermatologist | Resources for locating a specialist for treatment. | https://www.botoxseveresweating.com/find_a_dermatologist | 1 |
| tpl_10 | Savings and Insurance | Information about financial assistance and insurance coverage for treatments. | https://www.botoxseveresweating.com/Can_botox_help/savings_insurance | 1 |
| tpl_11 | Contact Information | Contact details and forms for reaching out to the organization. | https://www.botoxseveresweating.com/contact_us | 1 |
