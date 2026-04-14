# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **26** URLs; **5** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Savings Program**, **Patient Resources**, **About Pages**. **27** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:44:39.554Z
- **Website**: https://www.viberzi.com/
- **Total Pages Analyzed**: 26
- **Total Templates Identified**: 5
- **Total Components Identified**: 27
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.VIBERZI.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Savings Program                      │    │ Patient Resources                    │    │ About Pages                          │
│ (7 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Strip Header               │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation Header          │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Main Content Region {Unmapped}     │    │ • Hero Section                       │
│ • Eligibility Section {Unmapped}     │    │ • Site Footer                        │    │ • Content Overview Links {Unmapped}  │
│ • (+4 more — see Blocks mapped per … │    │ • —                                  │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Site Map                             │    │ Home Page                            │
│ (2 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Hero Section                       │
│ • Sitemap Links {Unmapped}           │    │ • IBS-D Information                  │
│ • (+3 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Savings Program (`tpl_0`) — 7 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Eligibility Section {Unmapped}
- Signup Methods {Unmapped}
- Important Safety Information {Unmapped}
- Footer {Unmapped}
- Back to Top Button {Unmapped}

### Patient Resources (`tpl_1`) — 2 pages

- Utility Strip Header
- Primary Navigation Header
- Main Content Region {Unmapped}
- Site Footer

### About Pages (`tpl_2`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Overview Links {Unmapped}
- What is VIBERZI Section {Unmapped}
- How VIBERZI Works {Unmapped}
- Side Effects Section {Unmapped}
- Daily Dosing Section {Unmapped}
- Tips for Taking VIBERZI {Unmapped}
- Tips Carousel
- Important Risk Information {Unmapped}

### Site Map (`tpl_3`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sitemap Links {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Home Page (`tpl_4`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- IBS-D Information
- Provider Discussion Section
- VIBERZI Introduction
- Savings and FAQs
- Safety Information
- Footer Section
- Back to Top Button {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┤
│ Back to Top Button {Unmapped}           │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Hero Section                            │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}           │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Important Safety Information {Unmapped} │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌───────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┐
│ Component                             │ T1  │ T2  │ T3  │ T4  │ T5  │
├───────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┤
│ Content Overview Links {Unmapped}     │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Daily Dosing Section {Unmapped}       │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Eligibility Section {Unmapped}        │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer {Unmapped}                     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links                          │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Section                        │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Hero Section {Unmapped}               │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ How VIBERZI Works {Unmapped}          │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ IBS-D Information                     │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Important Risk Information {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Main Content Region {Unmapped}        │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Primary Navigation                    │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Primary Navigation Header             │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Provider Discussion Section           │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└───────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Savings Program (7 pgs)                                                                           │
│ • Patient Resources (2 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • About Pages (2 pgs)                                                                               │
│ • Site Map (2 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Home Page (1 pgs)                                                                                 │
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
| tpl_0 | Savings Program | Pages related to the savings program and its management. | https://www.viberzi.com/savings-program, https://www.viberzi.com/savings-program/activate, https://www.viberzi.com/savings-program/card-entry | 7 |
| tpl_1 | Patient Resources | Resources and guides for patients. | https://www.viberzi.com/patient-resources, https://www.viberzi.com/patient-resources/doctordiscussion-guide | 2 |
| tpl_2 | About Pages | Pages providing information about the company or product. | https://www.viberzi.com/about-viberzi, https://www.viberzi.com/about-ibsd | 2 |
| tpl_3 | Site Map | A map of the website's structure and pages. | https://www.viberzi.com/site-map, https://www.viberzi.com/sitemap | 2 |
| tpl_4 | Home Page | The main landing page of the website. | https://www.viberzi.com/ | 1 |
