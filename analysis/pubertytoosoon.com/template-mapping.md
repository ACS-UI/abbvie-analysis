# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **27** URLs; **1** layout template were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Agent Unassigned Template**. **6** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:05:06.395Z
- **Website**: https://www.pubertytoosoon.com/
- **Total Pages Analyzed**: 27
- **Total Templates Identified**: 1
- **Total Components Identified**: 6
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.PUBERTYTOOSOON.COM TEMPLATES                                             │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Agent Unassigned Template            │
│ (25 pages)                           │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Site Header                        │
│ • Hero Section                       │
│ • Information Cards                  │
│ • Quote Section                      │
│ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Agent Unassigned Template (`tpl_0`) — 25 pages

- Site Header
- Hero Section
- Information Cards
- Quote Section
- Video Section
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
┌──────────────────────────────┬─────┐
│ Component                    │ T1  │
├──────────────────────────────┼─────┤
│ Hero Section                 │ ✅   │
│ Information Cards            │ ✅   │
│ Quote Section                │ ✅   │
│ Site Footer                  │ ✅   │
│ Site Header                  │ ✅   │
│ Video Section                │ ✅   │
└──────────────────────────────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Agent Unassigned Template (25 pgs)                                                                │
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
| tpl_0 | Agent Unassigned Template | This template is used for pages where agents are unassigned. | https://www.pubertytoosoon.com/, https://www.pubertytoosoon.com/content/dam/pubertytoosoon/pdf/growth_chart_boys.pdf, https://www.pubertytoosoon.com/content/dam/pubertytoosoon/pdf/growth_chart_girls.pdf | 25 |
