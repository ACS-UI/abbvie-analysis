# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **9** URLs; **5** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Informational Article**, **Sitemap**, **Homepage**. **27** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:10:27.293Z
- **Website**: https://www.latestagensclc.com/
- **Total Pages Analyzed**: 9
- **Total Templates Identified**: 5
- **Total Components Identified**: 27
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LATESTAGENSCLC.COM TEMPLATES                                             │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Informational Article                │    │ Sitemap                              │    │ Homepage                             │
│ (3 pages)                            │    │ (2 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header Navigation          │
│ • Content Columns                    │    │ • Hero Section {Unmapped}            │    │ • Homepage Hero Banner               │
│ • Main Content Region 1 {Unmapped}   │    │ • Sitemap Links {Unmapped}           │    │ • Biomarker Guide CTA {Unmapped}     │
│ • (+4 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Signup Page                          │    │ Resource Page                        │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │
│ • Hero Banner {Unmapped}             │    │ • Main Navigation {Unmapped}         │
│ • Signup Form                        │    │ • Hero Section {Unmapped}            │
│ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Informational Article (`tpl_0`) — 3 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Columns
- Main Content Region 1 {Unmapped}
- Main Content Region 2 {Unmapped}
- Main Content Region 3 {Unmapped}
- Main Content Region 4 {Unmapped}
- Site Footer

### Sitemap (`tpl_1`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Sitemap Links {Unmapped}
- Footer Main
- Footer Secondary
- Back to Top Button {Unmapped}

### Homepage (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header Navigation
- Homepage Hero Banner
- Biomarker Guide CTA {Unmapped}
- Stay Informed CTA {Unmapped}
- Testing Matters CTA {Unmapped}
- Advancements in NSCLC CTA {Unmapped}
- About Biomarkers CTA {Unmapped}
- Main Footer
- Back to Top Button {Unmapped}

### Signup Page (`tpl_3`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Banner {Unmapped}
- Signup Form
- Footer Main {Unmapped}
- Back to Top Button {Unmapped}

### Resource Page (`tpl_4`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content {Unmapped}
- Footer
- Back to Top {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────┬─────┬─────┬─────┬─────┬─────┐
│ Component                       │ T1  │ T2  │ T3  │ T4  │ T5  │
├─────────────────────────────────┼─────┼─────┼─────┼─────┼─────┤
│ Back to Top Button {Unmapped}   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Global Utility Strip {Unmapped} │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Hero Section {Unmapped}         │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Primary Header {Unmapped}       │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┤
│ About Biomarkers CTA {Unmapped}      │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Advancements in NSCLC CTA {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Back to Top {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Biomarker Guide CTA {Unmapped}       │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Content Columns                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer                               │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Main                          │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer Main {Unmapped}               │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Secondary                     │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Hero Banner {Unmapped}               │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Homepage Hero Banner                 │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Main Content {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Main Content Region 1 {Unmapped}     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Informational Article (3 pgs)                                                                     │
│ • Sitemap (2 pgs)                                                                                   │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Signup Page (1 pgs)                                                                               │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Resource Page (1 pgs)                                                                             │
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
| tpl_0 | Informational Article | Pages providing detailed information on specific topics. | https://www.latestagensclc.com/biomarker-testing, https://www.latestagensclc.com/advancements-in-late-stage-nsclc, https://www.latestagensclc.com/biomarker-facts | 3 |
| tpl_1 | Sitemap | Pages listing the structure and links of the website. | https://www.latestagensclc.com/sitemap, https://www.latestagensclc.com/site-map | 2 |
| tpl_2 | Homepage | The main landing page of the website. | https://www.latestagensclc.com/ | 1 |
| tpl_3 | Signup Page | Pages dedicated to user registration and account creation. | https://www.latestagensclc.com/sign-up | 1 |
| tpl_4 | Resource Page | Pages offering downloadable or interactive resources. | https://www.latestagensclc.com/conversation-guide | 1 |
