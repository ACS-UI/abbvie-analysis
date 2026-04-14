# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **85** URLs; **16** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Agent Unassigned**, **Wellness**, **Patient Experience**. **57** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:33:35.605Z
- **Website**: https://www.linzess.com/
- **Total Pages Analyzed**: 85
- **Total Templates Identified**: 16
- **Total Components Identified**: 57
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LINZESS.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Agent Unassigned                     │    │ Wellness                             │    │ Patient Experience                   │
│ (25 pages)                           │    │ (15 pages)                           │    │ (13 pages)                           │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Terms and Conditions Accordion     │    │ • Introduction Text {Unmapped}       │    │ • Main Content Transcripts {Unmappe… │
│ • (+3 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Support Program                      │    │ Understanding Constipation           │    │ Why Linzess                          │
│ (4 pages)                            │    │ (4 pages)                            │    │ (3 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Banner                        │
│ • Section Navigation {Unmapped}      │    │ • Section Navigation {Unmapped}      │    │ • Sticky Section Navigation {Unmapp… │
│ • (+3 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Savings Support                      │    │ Usage Information                    │    │ Community Support                    │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Banner                        │
│ • Section Navigation                 │    │ • Section Navigation {Unmapped}      │    │ • Section Navigation {Unmapped}      │
│ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Search Results                       │    │ Educational Content                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │
│ • Hero Section {Unmapped}            │    │ • Hero Banner                        │    │ • Hero Section                       │
│ • Call-to-Action Columns {Unmapped}  │    │ • Search Results                     │    │ • Section Navigation {Unmapped}      │
│ • (+2 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • Footer                             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LINZESS.COM — SUB-TEMPLATES TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Legal Disclaimer                     │    │ Language Selection                   │    │ Doctor Guidance                      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Legal Disclaimer Section {Unmappe… │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Call to Action Section {Unmapped}  │    │ • Section Navigation {Unmapped}      │
│ • —                                  │    │ • (+6 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Getting Started                      │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │
│ • Important Safety Information {Unm… │
│ • Footer                             │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Agent Unassigned (`tpl_0`) — 25 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Terms and Conditions Accordion
- Savings Program Form
- Important Safety Information {Unmapped}
- Footer

### Wellness (`tpl_1`) — 15 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- FODMAP Columns
- FODMAP Infographic {Unmapped}
- Related Articles {Unmapped}
- Footer Call-to-Action {Unmapped}

### Patient Experience (`tpl_2`) — 13 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Transcripts {Unmapped}
- Important Safety Information {Unmapped}
- Website Footer

### Support Program (`tpl_3`) — 4 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Section Navigation {Unmapped}
- Savings Section {Unmapped}
- Sign-Up Options {Unmapped}
- Footer Terms and Conditions {Unmapped}

### Understanding Constipation (`tpl_4`) — 4 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Section Navigation {Unmapped}
- Types of Constipation
- Bristol Stool Scale {Unmapped}
- IBS-C & CIC Section {Unmapped}
- Video Section
- Symptoms and Causes Comparison

### Why Linzess (`tpl_5`) — 3 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Banner
- Sticky Section Navigation {Unmapped}
- Informational Section {Unmapped}
- Mechanism of Action Section {Unmapped}
- Patient Stories {Unmapped}
- Side Effects Information {Unmapped}

### Savings Support (`tpl_6`) — 2 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Section Navigation
- Savings Section
- Sign-Up Options
- Terms and Conditions
- Accordion FAQ

### Usage Information (`tpl_7`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Section Navigation {Unmapped}
- Talk to a Doctor {Unmapped}
- Gut Check CTA {Unmapped}
- Doctor Video Section {Unmapped}
- How to Take Linzess {Unmapped}
- Prescribed Linzess Tips {Unmapped}
- Savings Card Section {Unmapped}

### Community Support (`tpl_8`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Section Navigation {Unmapped}
- Healthy Routines Content {Unmapped}
- Wellness Tips Content {Unmapped}
- Page Footer

### Homepage (`tpl_9`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Call-to-Action Columns {Unmapped}
- Statistics Flexbox {Unmapped}
- Patient Experiences {Unmapped}

### Search Results (`tpl_10`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Search Results
- Important Safety Information {Unmapped}
- Footer Links

### Educational Content (`tpl_11`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation
- Hero Section
- Section Navigation {Unmapped}
- Footer

### Legal Disclaimer (`tpl_12`) — 1 pages

- Legal Disclaimer Section {Unmapped}

### Language Selection (`tpl_13`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call to Action Section {Unmapped}
- Symptoms Section {Unmapped}
- Informative Section {Unmapped}
- Promotional Section {Unmapped}
- Accordion Terms
- Important Safety Information {Unmapped}
- Footer

### Doctor Guidance (`tpl_14`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Section Navigation {Unmapped}
- Talk to a Doctor Content {Unmapped}
- Gut Check CTA {Unmapped}
- Video Section - Right Doctor {Unmapped}
- How to Take LINZESS Content {Unmapped}
- Tips for Prescribed LINZESS {Unmapped}
- Savings Card CTA {Unmapped}
- Footer Section

### Getting Started (`tpl_15`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Important Safety Information {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}           │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Hero Section                            │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Section Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Important Safety Information {Unmapped} │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}           │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer                                  │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}         │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Hero Banner                             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Hero Section {Unmapped}                 │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Gut Check CTA {Unmapped}                │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Navigation                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T16 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                              │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion FAQ                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Accordion Terms                        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Bristol Stool Scale {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call to Action Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Columns {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Doctor Video Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FODMAP Columns                         │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FODMAP Infographic {Unmapped}          │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Call-to-Action {Unmapped}       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links                           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Section                         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Terms and Conditions {Unmapped} │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Healthy Routines Content {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ How to Take Linzess {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T16 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Agent Unassigned (25 pgs)                                                                         │
│ • Wellness (15 pgs)                                                                                 │
│ • Patient Experience (13 pgs)                                                                       │
│ • Support Program (4 pgs)                                                                           │
│ • Understanding Constipation (4 pgs)                                                                │
│ • Why Linzess (3 pgs)                                                                               │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Savings Support (2 pgs)                                                                           │
│ • Usage Information (2 pgs)                                                                         │
│ • Community Support (2 pgs)                                                                         │
│ • Homepage (1 pgs)                                                                                  │
│ • Search Results (1 pgs)                                                                            │
│ • Educational Content (1 pgs)                                                                       │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Legal Disclaimer (1 pgs)                                                                          │
│ • Language Selection (1 pgs)                                                                        │
│ • Doctor Guidance (1 pgs)                                                                           │
│ • Getting Started (1 pgs)                                                                           │
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
| tpl_0 | Agent Unassigned | Pages related to unassigned agent tasks. | https://www.linzess.com/savings-card, https://www.linzess.com/savings-and-support/reminder-terms-conditions, https://www.linzess.com/starting-linzess/reminder-terms-conditions | 25 |
| tpl_1 | Wellness | Pages focusing on wellness topics and articles. | https://www.linzess.com/starting-linzess/wellness-tips/your-map-to-a-low-fodmap-diet, https://www.linzess.com/starting-linzess/wellness-tips/good-for-your-gut-flavorful-food-swaps, https://www.linzess.com/understanding-constipation/tips-for-managing-constipation | 15 |
| tpl_2 | Patient Experience | Pages showcasing patient experiences and testimonials. | https://www.linzess.com/why-linzess/linzess-patient-experiences/getting-on-same-page-transcripts, https://www.linzess.com/why-linzess/linzess-patient-experiences/julie-transcripts, https://www.linzess.com/why-linzess/linzess-patient-experiences/dr-lucak-transcripts | 13 |
| tpl_3 | Support Program | Pages detailing support programs available. | https://www.linzess.com/savings-and-support/linzess-savings-program, https://www.linzess.com/savings-card/terms, https://www.linzess.com/savings-card/savings | 4 |
| tpl_4 | Understanding Constipation | Pages explaining constipation and related topics. | https://www.linzess.com/understanding-constipation/what-is-ibs-c, https://www.linzess.com/understanding-constipation/constipation-treatment-options, https://www.linzess.com/understanding-constipation/types-of-constipation | 4 |
| tpl_5 | Why Linzess | Pages explaining the benefits of Linzess. | https://www.linzess.com/why-linzess/how-linzess-can-help, https://www.linzess.com/why-linzess/side-effects-of-linzess, https://www.linzess.com/why-linzess/how-linzess-works | 3 |
| tpl_6 | Savings Support | Pages providing information and FAQs about savings. | https://www.linzess.com/savings-and-support, https://www.linzess.com/savings-and-support/faqs | 2 |
| tpl_7 | Usage Information | Pages providing information on usage. | https://www.linzess.com/savings-and-support/how-to-take-linzess, https://www.linzess.com/find-relief/how-to-take-linzess | 2 |
| tpl_8 | Community Support | Pages providing community support resources. | https://www.linzess.com/savings-and-support/community-resources, https://www.linzess.com/savings-and-support/community-support | 2 |
| tpl_9 | Homepage | The main entry page of the website. | https://www.linzess.com/ | 1 |
| tpl_10 | Search Results | Pages displaying search results. | https://www.linzess.com/search-results | 1 |
| tpl_11 | Educational Content | Pages containing educational materials. | https://www.linzess.com/understanding-constipation#typesofconstipation | 1 |
| tpl_12 | Legal Disclaimer | Pages displaying legal disclaimers. | https://www.linzess.com/reminder-terms-conditions | 1 |
| tpl_13 | Language Selection | Pages for selecting language preferences. | https://www.linzess.com/espanol | 1 |
| tpl_14 | Doctor Guidance | Pages offering guidance for doctors. | https://www.linzess.com/find-relief/talk-to-a-doctor | 1 |
| tpl_15 | Getting Started | Pages to help users begin using the service. | https://www.linzess.com/starting-linzess | 1 |
