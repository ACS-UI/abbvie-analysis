# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **14** URLs; **9** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Homepage**, **PDF Document**, **Contact Page**. **21** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:30:17.770Z
- **Website**: https://www.savewithays.com/
- **Total Pages Analyzed**: 14
- **Total Templates Identified**: 9
- **Total Components Identified**: 21
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.SAVEWITHAYS.COM TEMPLATES                                                │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ PDF Document                         │    │ Contact Page                         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • —                                  │    │ • Global Utility Navigation {Unmapp… │
│ • Main Header                        │    │ • —                                  │    │ • Primary Header {Unmapped}          │
│ • Hero Section {Unmapped}            │    │ • —                                  │    │ • Main Navigation {Unmapped}         │
│ • Product Cards {Unmapped}           │    │ • —                                  │    │ • Hero Section                       │
│ • (+6 more — see Blocks mapped per … │    │ • —                                  │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap Page                         │    │ Confirmation Page                    │    │ Terms and Conditions Page            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Content Columns {Unmapped}         │    │ • Content Columns {Unmapped}         │    │ • Content Columns {Unmapped}         │
│ • (+2 more — see Blocks mapped per … │    │ • Footer Links                       │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.SAVEWITHAYS.COM — SUB-TEMPLATES TEMPLATES                                │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Savings Page                         │    │ Enrollment Page                      │    │ Unsubscribe Page                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • Main Navigation {Unmapped}         │    │ • Main Navigation {Unmapped}         │    │ • Hero Section {Unmapped}            │
│ • Hero Section                       │    │ • Content Columns {Unmapped}         │    │ • Unsubscribe Form {Unmapped}        │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Homepage (`tpl_0`) — 1 pages

- Utility Navigation
- Main Header
- Hero Section {Unmapped}
- Product Cards {Unmapped}
- Enrollment Call-to-Action {Unmapped}
- Terms and Conditions {Unmapped}
- Footer Links {Unmapped}
- Footer Legal {Unmapped}
- Enroll Now Modal {Unmapped}
- Demo Video Modal {Unmapped}

### PDF Document (`tpl_1`) — 1 pages

- —

### Contact Page (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Contact Information {Unmapped}
- Product Links Section {Unmapped}
- Footer Links
- Footer Legal Information

### Sitemap Page (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Footer Links
- Footer Legal Text

### Confirmation Page (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Footer Links

### Terms and Conditions Page (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Terms and Conditions {Unmapped}
- Footer Links

### Savings Page (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Product Cards
- Enrollment Section {Unmapped}
- Footer Navigation
- Footer Legal {Unmapped}

### Enrollment Page (`tpl_7`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Content Columns {Unmapped}
- Hero Section
- Enrollment Form
- Footer Navigation
- Footer Legal

### Unsubscribe Page (`tpl_8`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Unsubscribe Form {Unmapped}
- Footer Links {Unmapped}
- Footer Legal Text {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                         │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Content Columns {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Footer Links                         │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Main Navigation {Unmapped}           │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Primary Header {Unmapped}            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Footer Legal {Unmapped}              │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Links {Unmapped}              │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Navigation                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Hero Section {Unmapped}              │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Terms and Conditions {Unmapped}      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


### Template-specific components

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Contact Information {Unmapped}       │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Demo Video Modal {Unmapped}          │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Enroll Now Modal {Unmapped}          │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Enrollment Call-to-Action {Unmapped} │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Enrollment Form                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Enrollment Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Legal                         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Legal Information             │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Legal Text                    │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer Legal Text {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Header                          │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Product Cards                        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Product Cards {Unmapped}             │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Product Links Section {Unmapped}     │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • PDF Document (1 pgs)                                                                              │
│ • Contact Page (1 pgs)                                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap Page (1 pgs)                                                                              │
│ • Confirmation Page (1 pgs)                                                                         │
│ • Terms and Conditions Page (1 pgs)                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Savings Page (1 pgs)                                                                              │
│ • Enrollment Page (1 pgs)                                                                           │
│ • Unsubscribe Page (1 pgs)                                                                          │
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
| tpl_0 | Homepage | The main landing page of a website. | https://www.savewithays.com/ | 1 |
| tpl_1 | PDF Document | A downloadable or viewable PDF document. | https://www.savewithays.com/content/dam/savewithays/pdf/SaveWithAYSCard.pdf | 1 |
| tpl_2 | Contact Page | A page providing contact information or a contact form. | https://www.savewithays.com/contact | 1 |
| tpl_3 | Sitemap Page | A page listing the structure of the website. | https://www.savewithays.com/sitemap | 1 |
| tpl_4 | Confirmation Page | A page confirming an action or submission. | https://www.savewithays.com/unsubscribe-success | 1 |
| tpl_5 | Terms and Conditions Page | A page outlining the terms and conditions of the website. | https://www.savewithays.com/mobiletermsconditions | 1 |
| tpl_6 | Savings Page | A page detailing savings or discounts. | https://www.savewithays.com/savings | 1 |
| tpl_7 | Enrollment Page | A page for user enrollment or registration. | https://www.savewithays.com/enroll-now | 1 |
| tpl_8 | Unsubscribe Page | A page for unsubscribing from services or newsletters. | https://www.savewithays.com/unsubscribe | 1 |
