# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **1** URLs; **1** layout template were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Healthcare Expert Locator**. **9** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:23:28.770Z
- **Website**: https://www.amlexpertconnect.com/
- **Total Pages Analyzed**: 1
- **Total Templates Identified**: 1
- **Total Components Identified**: 9
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.AMLEXPERTCONNECT.COM TEMPLATES                                           │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Healthcare Expert Locator            │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Navigation and Branding {U… │
│ • Hero Section                       │
│ • Expert Locator Form                │
│ • Results Display {Unmapped}         │
│ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Healthcare Expert Locator (`tpl_0`) — 1 pages

- Global Navigation and Branding {Unmapped}
- Hero Section
- Expert Locator Form
- Results Display {Unmapped}
- Call-to-Action Section {Unmapped}
- Footer Section
- Back to Top Button {Unmapped}
- Terms and Conditions Modal
- Explore Treatment Modal


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┐
│ Component                    │ T1  │
├──────────────────────────────┼─────┤
│ (after blocks step)          │ —   │
└──────────────────────────────┴─────┘
```


### Template-specific components

```
┌───────────────────────────────────────────┬─────┐
│ Component                                 │ T1  │
├───────────────────────────────────────────┼─────┤
│ Back to Top Button {Unmapped}             │ ✅   │
│ Call-to-Action Section {Unmapped}         │ ✅   │
│ Expert Locator Form                       │ ✅   │
│ Explore Treatment Modal                   │ ✅   │
│ Footer Section                            │ ✅   │
│ Global Navigation and Branding {Unmapped} │ ✅   │
│ Hero Section                              │ ✅   │
│ Results Display {Unmapped}                │ ✅   │
│ Terms and Conditions Modal                │ ✅   │
└───────────────────────────────────────────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Healthcare Expert Locator (1 pgs)                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

*None in this tier.*


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
| tpl_0 | Healthcare Expert Locator | A template for locating healthcare experts. | https://www.amlexpertconnect.com/ | 1 |
