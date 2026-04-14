# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **41** URLs; **9** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Product Information**, **Informational Articles**, **Additional Resources**. **33** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:33:40.737Z
- **Website**: https://www.loloestrin.com/
- **Total Pages Analyzed**: 41
- **Total Templates Identified**: 9
- **Total Components Identified**: 33
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LOLOESTRIN.COM TEMPLATES                                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Product Information                  │    │ Informational Articles               │    │ Additional Resources                 │
│ (8 pages)                            │    │ (8 pages)                            │    │ (4 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • —                                  │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • —                                  │
│ • Hero Banner                        │    │ • Hero Section {Unmapped}            │    │ • —                                  │
│ • Savings Information {Unmapped}     │    │ • Content Columns {Unmapped}         │    │ • —                                  │
│ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap                              │    │ Modal Information                    │    │ Home Page                            │
│ (2 pages)                            │    │ (2 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Modal Title Section {Unmapped}     │    │ • Utility Navigation                 │
│ • Primary Navigation {Unmapped}      │    │ • Modal Terms and Conditions {Unmap… │    │ • Main Navigation                    │
│ • Hero Banner                        │    │ • Modal Footer                       │    │ • Hero Section                       │
│ • Sitemap Links {Unmapped}           │    │ • —                                  │    │ • Call-to-Action Columns             │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LOLOESTRIN.COM — SUB-TEMPLATES TEMPLATES                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Search Results                       │    │ FAQ Page                             │    │ Interactive Quiz                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Search Results {Unmapped}          │    │ • FAQ Categories Links               │    │ • Quiz Embed {Unmapped}              │
│ • (+6 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Product Information (`tpl_0`) — 8 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Savings Information {Unmapped}
- Call to Action {Unmapped}
- Additional Savings Information {Unmapped}
- Questions Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Informational Articles (`tpl_1`) — 8 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Columns {Unmapped}
- Important Safety Information {Unmapped}
- Footer {Unmapped}
- Back to Top Button {Unmapped}

### Additional Resources (`tpl_2`) — 4 pages

- —

### Sitemap (`tpl_3`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Sitemap Links {Unmapped}
- Safety Information {Unmapped}
- Footer
- Back to Top {Unmapped}

### Modal Information (`tpl_4`) — 2 pages

- Modal Title Section {Unmapped}
- Modal Terms and Conditions {Unmapped}
- Modal Footer

### Home Page (`tpl_5`) — 1 pages

- Utility Navigation
- Main Navigation
- Hero Section
- Call-to-Action Columns
- Low Dose Section
- Prescribed Section
- Savings Section
- Five Reasons Section

### Search Results (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Search Results {Unmapped}
- Safety Information {Unmapped}
- Footer Links
- Footer Legal Text {Unmapped}
- Back to Top Button {Unmapped}
- Modal Popup {Unmapped}
- Safety Bar {Unmapped}

### FAQ Page (`tpl_7`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- FAQ Categories Links
- FAQ Section: About
- FAQ Section: Getting Lo Loestrin Fe
- FAQ Section: Taking Lo Loestrin Fe
- Footer

### Interactive Quiz (`tpl_8`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Quiz Embed {Unmapped}
- Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}
- Modal Popup
- Safety Bar {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}           │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Back to Top Button {Unmapped}           │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped}           │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Footer Links                            │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Hero Section                            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Safety Information {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Footer                                  │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Hero Banner                             │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}                 │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Important Safety Information {Unmapped} │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Safety Bar {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Utility Navigation                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                 │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Additional Savings Information {Unmapped} │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top {Unmapped}                    │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Call to Action {Unmapped}                 │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Columns                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Content Columns {Unmapped}                │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Categories Links                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Section: About                        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Section: Getting Lo Loestrin Fe       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Section: Taking Lo Loestrin Fe        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Five Reasons Section                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer {Unmapped}                         │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Legal Text {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Global Utility Strip {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Low Dose Section                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└───────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Product Information (8 pgs)                                                                       │
│ • Informational Articles (8 pgs)                                                                    │
│ • Additional Resources (4 pgs)                                                                      │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap (2 pgs)                                                                                   │
│ • Modal Information (2 pgs)                                                                         │
│ • Home Page (1 pgs)                                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Search Results (1 pgs)                                                                            │
│ • FAQ Page (1 pgs)                                                                                  │
│ • Interactive Quiz (1 pgs)                                                                          │
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
| tpl_0 | Product Information | Pages detailing product features, pricing, and savings. | https://www.loloestrin.com/savings-card, https://www.loloestrin.com/about-lo-loestrin-fe/meet-lo-loestrin, https://www.loloestrin.com/about-lo-loestrin-fe/side-effects | 8 |
| tpl_1 | Informational Articles | Pages providing detailed information on specific topics. | https://www.loloestrin.com/get-the-facts/keeping-your-routine-between-the-seasons, https://www.loloestrin.com/about-lo-loestrin-fe/articles-and-advice, https://www.loloestrin.com/about-birth-control/birth-control-conversation-daughter | 8 |
| tpl_2 | Additional Resources | Pages offering downloadable content and resources. | https://www.loloestrin.com/content/dam/loloestrin/pdf/lo-loestrin-fe_pi.pdf, https://www.loloestrin.com/content/dam/loloestrin/pdf/understanding-health-insurance%20(1).pdf, https://www.loloestrin.com/mobile-wallet-landing-page | 4 |
| tpl_3 | Sitemap | A page listing the structure and links of the website. | https://www.loloestrin.com/lo-loestrin-site-map, https://www.loloestrin.com/sitemap | 2 |
| tpl_4 | Modal Information | Content displayed in modal pop-ups. | https://www.loloestrin.com/modal/pricing-information-modal, https://www.loloestrin.com/modal/sms-savings-program | 2 |
| tpl_5 | Home Page | The main landing page of the website. | https://www.loloestrin.com/ | 1 |
| tpl_6 | Search Results | Pages displaying the results of a search query. | https://www.loloestrin.com/search-results | 1 |
| tpl_7 | FAQ Page | A page containing frequently asked questions and their answers. | https://www.loloestrin.com/lo-loestrin-faqs | 1 |
| tpl_8 | Interactive Quiz | A page hosting quizzes for user engagement. | https://www.loloestrin.com/estrogen-pop-quiz | 1 |
