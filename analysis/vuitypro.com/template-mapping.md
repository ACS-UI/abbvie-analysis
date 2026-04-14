# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **25** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Downloadable PDF**, **FAQs Page**, **Sitemap**. **39** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:46:32.800Z
- **Website**: https://www.vuitypro.com/
- **Total Pages Analyzed**: 25
- **Total Templates Identified**: 8
- **Total Components Identified**: 39
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.VUITYPRO.COM TEMPLATES                                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Downloadable PDF                     │    │ FAQs Page                            │    │ Sitemap                              │
│ (12 pages)                           │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • —                                  │    │ • FAQ Section                        │    │ • Important Safety Information {Unm… │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Safety Page                          │    │ Efficacy Page                        │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Banner {Unmapped}             │    │ • Hero Banner                        │
│ • FDA Approval Highlight {Unmapped}  │    │ • Safety Statistics {Unmapped}       │    │ • Improved Vision Section {Unmapped} │
│ • (+8 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.VUITYPRO.COM — SUB-TEMPLATES TEMPLATES                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Access Prescribing                   │    │ Innovation Page                      │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Banner                        │
│ • Content Columns {Unmapped}         │    │ • Formulation Section                │
│ • (+7 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Downloadable PDF (`tpl_0`) — 12 pages

- —

### FAQs Page (`tpl_1`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- FAQ Section
- Important Safety Information {Unmapped}
- Footer

### Sitemap (`tpl_2`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Safety Bar {Unmapped}

### Homepage (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- FDA Approval Highlight {Unmapped}
- Formulation Section
- Technology Section {Unmapped}
- Efficacy Section {Unmapped}
- Carousel Section
- Safety Section {Unmapped}
- Prescribing Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Safety Page (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner {Unmapped}
- Safety Statistics {Unmapped}
- Adverse Events Section {Unmapped}
- Clinical Trials Section {Unmapped}
- Warnings and Precautions {Unmapped}
- Post-Marketing Data {Unmapped}
- Call to Action {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Efficacy Page (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Improved Vision Section {Unmapped}
- GEMINI Study Tabs
- DCNVA Chart Section {Unmapped}
- Intermediate Vision Section {Unmapped}
- Clinical Trials Section {Unmapped}
- Safety CTA {Unmapped}
- Important Safety Information {Unmapped}

### Access Prescribing (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Daily Treatment Section {Unmapped}
- FSA/HSA Section {Unmapped}
- Retail Pharmacies Section {Unmapped}
- Insurance Information {Unmapped}
- MVP Program Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Innovation Page (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Formulation Section
- Delivered with pHast Technology {Unmapped}
- pHast Technology Details {Unmapped}
- Mechanism of Action {Unmapped}
- Clinical Studies {Unmapped}
- Important Safety Information {Unmapped}
- References Section {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Important Safety Information {Unmapped} │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Footer                                  │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped}           │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Hero Section                            │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Clinical Trials Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Formulation Section                     │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Hero Banner                             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                  │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Adverse Events Section {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call to Action {Unmapped}                  │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Carousel Section                           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Clinical Studies {Unmapped}                │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Daily Treatment Section {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ DCNVA Chart Section {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Delivered with pHast Technology {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Efficacy Section {Unmapped}                │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ FAQ Section                                │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FDA Approval Highlight {Unmapped}          │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ FSA/HSA Section {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ GEMINI Study Tabs                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Hero Banner {Unmapped}                     │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Downloadable PDF (12 pgs)                                                                         │
│ • FAQs Page (2 pgs)                                                                                 │
│ • Sitemap (2 pgs)                                                                                   │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Safety Page (1 pgs)                                                                               │
│ • Efficacy Page (1 pgs)                                                                             │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Access Prescribing (1 pgs)                                                                        │
│ • Innovation Page (1 pgs)                                                                           │
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
| tpl_0 | Downloadable PDF | Template for pages offering downloadable PDF resources. | https://www.vuitypro.com/content/dam/vuitypro/pdf/presbyopia-access-flashcard-from-vuity.pdf, https://www.vuitypro.com/content/dam/vuitypro/pdf/take-home-chart.pdf, https://www.vuitypro.com/content/dam/vuitypro/pdf/presbyopia-my-vuity-points-mvp-loyalty-flashcard.pdf | 12 |
| tpl_1 | FAQs Page | Template for pages addressing frequently asked questions. | https://www.vuitypro.com/faqs, https://www.vuitypro.com/resources | 2 |
| tpl_2 | Sitemap | Template for pages providing a sitemap or navigation overview. | https://www.vuitypro.com/sitemap, https://www.vuitypro.com/site-map | 2 |
| tpl_3 | Homepage | Template for the main landing page of the website. | https://www.vuitypro.com/ | 1 |
| tpl_4 | Safety Page | Template for pages related to safety information. | https://www.vuitypro.com/safety | 1 |
| tpl_5 | Efficacy Page | Template for pages discussing efficacy information. | https://www.vuitypro.com/efficacy | 1 |
| tpl_6 | Access Prescribing | Template for pages related to prescribing access information. | https://www.vuitypro.com/access-and-prescribing | 1 |
| tpl_7 | Innovation Page | Template for pages showcasing innovation and advancements. | https://www.vuitypro.com/innovation | 1 |
