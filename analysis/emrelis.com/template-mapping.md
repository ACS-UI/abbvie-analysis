# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **4** URLs; **4** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Homepage Information**, **Sitemap Navigation**, **Policy Terms**. **22** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:25:29.977Z
- **Website**: https://www.emrelis.com/
- **Total Pages Analyzed**: 4
- **Total Templates Identified**: 4
- **Total Components Identified**: 22
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.EMRELIS.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage Information                 │    │ Sitemap Navigation                   │    │ Policy Terms                         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Main Navigation {Unmapped}         │
│ • About Section {Unmapped}           │    │ • CTA Links {Unmapped}               │    │ • Hero Section                       │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Sign Up Form                         │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │
│ • Sign Up Form                       │
│ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Homepage Information (`tpl_0`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- About Section {Unmapped}
- Clinical Trial Results {Unmapped}
- Side Effects Section {Unmapped}
- How It Works Section {Unmapped}
- Taking EMRELIS Section {Unmapped}

### Sitemap Navigation (`tpl_1`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- CTA Links {Unmapped}
- Safety Information {Unmapped}
- Footer Links {Unmapped}
- Back to Top {Unmapped}
- Safety Bar {Unmapped}

### Policy Terms (`tpl_2`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Main Navigation {Unmapped}
- Hero Section
- About Section {Unmapped}
- Results Section {Unmapped}
- Side Effects Section {Unmapped}
- How It Works Section {Unmapped}
- Taking EMRELIS Section {Unmapped}

### Sign Up Form (`tpl_3`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sign Up Form
- Important Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}
- Cookie Settings {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌───────────────────────────────────┬─────┬─────┬─────┬─────┐
│ Component                         │ T1  │ T2  │ T3  │ T4  │
├───────────────────────────────────┼─────┼─────┼─────┼─────┤
│ Hero Section                      │ ✅   │ ❌   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}     │ ✅   │ ✅   │ ❌   │ ✅   │
│ About Section {Unmapped}          │ ✅   │ ❌   │ ✅   │ ❌   │
│ How It Works Section {Unmapped}   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Side Effects Section {Unmapped}   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Taking EMRELIS Section {Unmapped} │ ✅   │ ❌   │ ✅   │ ❌   │
│ Utility Navigation {Unmapped}     │ ✅   │ ✅   │ ❌   │ ❌   │
└───────────────────────────────────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┤
│ Back to Top {Unmapped}                  │ ❌   │ ✅   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │
│ Clinical Trial Results {Unmapped}       │ ✅   │ ❌   │ ❌   │ ❌   │
│ Cookie Settings {Unmapped}              │ ❌   │ ❌   │ ❌   │ ✅   │
│ CTA Links {Unmapped}                    │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Links                            │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Links {Unmapped}                 │ ❌   │ ✅   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ❌   │ ✅   │
│ Global Utility Strip {Unmapped}         │ ❌   │ ❌   │ ✅   │ ❌   │
│ Hero Section {Unmapped}                 │ ❌   │ ✅   │ ❌   │ ❌   │
│ Important Safety Information {Unmapped} │ ❌   │ ❌   │ ❌   │ ✅   │
│ Main Navigation {Unmapped}              │ ❌   │ ❌   │ ✅   │ ❌   │
│ Primary Header                          │ ❌   │ ❌   │ ✅   │ ❌   │
│ Results Section {Unmapped}              │ ❌   │ ❌   │ ✅   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage Information (1 pgs)                                                                      │
│ • Sitemap Navigation (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Policy Terms (1 pgs)                                                                              │
│ • Sign Up Form (1 pgs)                                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

*None in this tier.*


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
| tpl_0 | Homepage Information | Template for displaying the main homepage content. | https://www.emrelis.com/ | 1 |
| tpl_1 | Sitemap Navigation | Template for displaying site navigation and sitemap. | https://www.emrelis.com/sitemap | 1 |
| tpl_2 | Policy Terms | Template for displaying terms and policy information. | https://www.emrelis.com/copayterms | 1 |
| tpl_3 | Sign Up Form | Template for user registration forms. | https://www.emrelis.com/sign-up | 1 |
