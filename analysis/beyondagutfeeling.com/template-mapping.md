# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **1** URLs; **1** layout template were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Health Awareness Landing**. **10** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:38:41.348Z
- **Website**: https://www.beyondagutfeeling.com/
- **Total Pages Analyzed**: 1
- **Total Templates Identified**: 1
- **Total Components Identified**: 10
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BEYONDAGUTFEELING.COM TEMPLATES                                          │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Health Awareness Landing             │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │
│ • Hero Banner {Unmapped}             │
│ • Introduction Text {Unmapped}       │
│ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Health Awareness Landing (`tpl_0`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner {Unmapped}
- Introduction Text {Unmapped}
- Video Content {Unmapped}
- Accordion Component {Unmapped}
- Call-To-Action Grid {Unmapped}
- Goals Highlight {Unmapped}
- Understanding Content {Unmapped}
- Page Footer


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
┌──────────────────────────────────┬─────┐
│ Component                        │ T1  │
├──────────────────────────────────┼─────┤
│ Accordion Component {Unmapped}   │ ✅   │
│ Call-To-Action Grid {Unmapped}   │ ✅   │
│ Goals Highlight {Unmapped}       │ ✅   │
│ Hero Banner {Unmapped}           │ ✅   │
│ Introduction Text {Unmapped}     │ ✅   │
│ Page Footer                      │ ✅   │
│ Primary Navigation {Unmapped}    │ ✅   │
│ Understanding Content {Unmapped} │ ✅   │
│ Utility Navigation {Unmapped}    │ ✅   │
│ Video Content {Unmapped}         │ ✅   │
└──────────────────────────────────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Health Awareness Landing (1 pgs)                                                                  │
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
| tpl_0 | Health Awareness Landing | A landing page template for health awareness campaigns. | https://www.beyondagutfeeling.com/ | 1 |
