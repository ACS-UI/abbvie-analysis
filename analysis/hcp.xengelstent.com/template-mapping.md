# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **22** URLs; **3** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Resource Page**, **Homepage**, **Contact Page**. **19** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:35:56.504Z
- **Website**: https://hcp.xengelstent.com/
- **Total Pages Analyzed**: 22
- **Total Templates Identified**: 3
- **Total Components Identified**: 19
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│HCP.XENGELSTENT.COM TEMPLATES                                                │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Resource Page                        │    │ Homepage                             │    │ Contact Page                         │
│ (9 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Reimbursement Information {Unmapp… │    │ • Main Navigation {Unmapped}         │    │ • Request Updates {Unmapped}         │
│ • (+2 more — see Blocks mapped per … │    │ • (+8 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Resource Page (`tpl_0`) — 9 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Reimbursement Information {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Homepage (`tpl_1`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header
- Hero Section
- Main Navigation {Unmapped}
- Home Characteristics {Unmapped}
- Designed for Efficacy {Unmapped}
- Patient Selection {Unmapped}
- Documented Outcomes {Unmapped}
- Proven Safety Data {Unmapped}
- Request Updates {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Contact Page (`tpl_2`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Request Updates {Unmapped}
- User Form
- Safety Information {Unmapped}
- Footer
- Expandable Safety Bar {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │
├─────────────────────────────────────────┼─────┼─────┼─────┤
│ Footer                                  │ ✅   │ ✅   │ ✅   │
│ Hero Section                            │ ❌   │ ✅   │ ✅   │
│ Important Safety Information {Unmapped} │ ✅   │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}           │ ✅   │ ❌   │ ✅   │
│ Request Updates {Unmapped}              │ ❌   │ ✅   │ ✅   │
│ Utility Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │
└─────────────────────────────────────────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌──────────────────────────────────────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │
├──────────────────────────────────────┼─────┼─────┼─────┤
│ Designed for Efficacy {Unmapped}     │ ❌   │ ✅   │ ❌   │
│ Documented Outcomes {Unmapped}       │ ❌   │ ✅   │ ❌   │
│ Expandable Safety Bar {Unmapped}     │ ❌   │ ❌   │ ✅   │
│ Global Utility Navigation {Unmapped} │ ✅   │ ❌   │ ❌   │
│ Hero Section {Unmapped}              │ ✅   │ ❌   │ ❌   │
│ Home Characteristics {Unmapped}      │ ❌   │ ✅   │ ❌   │
│ Main Navigation {Unmapped}           │ ❌   │ ✅   │ ❌   │
│ Patient Selection {Unmapped}         │ ❌   │ ✅   │ ❌   │
│ Primary Header                       │ ❌   │ ✅   │ ❌   │
│ Proven Safety Data {Unmapped}        │ ❌   │ ✅   │ ❌   │
│ Reimbursement Information {Unmapped} │ ✅   │ ❌   │ ❌   │
│ Safety Information {Unmapped}        │ ❌   │ ❌   │ ✅   │
│ User Form                            │ ❌   │ ❌   │ ✅   │
└──────────────────────────────────────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Resource Page (9 pgs)                                                                             │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Contact Page (1 pgs)                                                                              │
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
| tpl_0 | Resource Page | A template for listing and detailing resources. | https://hcp.xengelstent.com/reimbursement, https://hcp.xengelstent.com/clinical-efficacy, https://hcp.xengelstent.com/patient-selection | 9 |
| tpl_1 | Homepage | The main landing page of the website. | https://hcp.xengelstent.com/ | 1 |
| tpl_2 | Contact Page | A template for contact information and forms. | https://hcp.xengelstent.com/healthcare-professionals | 1 |
