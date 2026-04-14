# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **9** URLs; **1** layout template were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Unknown Error**. **6** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:35:59.476Z
- **Website**: https://www.botoxblepharospasm.com/
- **Total Pages Analyzed**: 9
- **Total Templates Identified**: 1
- **Total Components Identified**: 6
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BOTOXBLEPHAROSPASM.COM TEMPLATES                                         │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Unknown Error                        │
│ (8 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Header                      │
│ • Hero Section                       │
│ • Navigation Column {Unmapped}       │
│ • Important Safety Information {Unm… │
│ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Unknown Error (`tpl_0`) — 8 pages

- Global Header
- Hero Section
- Navigation Column {Unmapped}
- Important Safety Information {Unmapped}
- Remediation Modal
- Site Footer


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
┌─────────────────────────────────────────┬─────┐
│ Component                               │ T1  │
├─────────────────────────────────────────┼─────┤
│ Global Header                           │ ✅   │
│ Hero Section                            │ ✅   │
│ Important Safety Information {Unmapped} │ ✅   │
│ Navigation Column {Unmapped}            │ ✅   │
│ Remediation Modal                       │ ✅   │
│ Site Footer                             │ ✅   │
└─────────────────────────────────────────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Unknown Error (8 pgs)                                                                             │
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
| tpl_0 | Unknown Error | Represents pages related to unspecified errors. | https://www.botoxblepharospasm.com/, https://www.botoxblepharospasm.com/about, https://www.botoxblepharospasm.com/why-botox | 8 |
