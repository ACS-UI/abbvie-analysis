# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **4** URLs; **3** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **PDF Resource**, **Home Page**, **Sitemap Page**. **19** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:46:48.113Z
- **Website**: https://www.donttakespasticity.com/
- **Total Pages Analyzed**: 4
- **Total Templates Identified**: 3
- **Total Components Identified**: 19
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DONTTAKESPASTICITY.COM TEMPLATES                                         │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ PDF Resource                         │    │ Home Page                            │    │ Sitemap Page                         │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • —                                  │    │ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • —                                  │    │ • Call-to-Action Columns {Unmapped}  │    │ • Sitemap Links {Unmapped}           │
│ • —                                  │    │ • (+9 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### PDF Resource (`tpl_0`) — 2 pages

- —

### Home Page (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Call-to-Action Columns {Unmapped}
- Testimonial Section {Unmapped}
- Causes Section {Unmapped}
- Signs Section {Unmapped}
- Care Team Section {Unmapped}
- Treatment Options Section {Unmapped}
- Impact Section {Unmapped}
- Guide Section {Unmapped}
- Video Section {Unmapped}
- Resources Section {Unmapped}

### Sitemap Page (`tpl_2`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sitemap Links {Unmapped}
- Footer Links
- Footer Legal Text
- Back to Top Button {Unmapped}
- Exit Modal {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┬─────┬─────┐
│ Component                    │ T1  │ T2  │ T3  │
├──────────────────────────────┼─────┼─────┼─────┤
│ (after blocks step)          │ —   │ —   │ —   │
└──────────────────────────────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌──────────────────────────────────────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │
├──────────────────────────────────────┼─────┼─────┼─────┤
│ Back to Top Button {Unmapped}        │ ❌   │ ❌   │ ✅   │
│ Call-to-Action Columns {Unmapped}    │ ❌   │ ✅   │ ❌   │
│ Care Team Section {Unmapped}         │ ❌   │ ✅   │ ❌   │
│ Causes Section {Unmapped}            │ ❌   │ ✅   │ ❌   │
│ Exit Modal {Unmapped}                │ ❌   │ ❌   │ ✅   │
│ Footer Legal Text                    │ ❌   │ ❌   │ ✅   │
│ Footer Links                         │ ❌   │ ❌   │ ✅   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ✅   │ ❌   │
│ Guide Section {Unmapped}             │ ❌   │ ✅   │ ❌   │
│ Hero Section                         │ ❌   │ ❌   │ ✅   │
│ Hero Section {Unmapped}              │ ❌   │ ✅   │ ❌   │
│ Impact Section {Unmapped}            │ ❌   │ ✅   │ ❌   │
│ Primary Header {Unmapped}            │ ❌   │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}        │ ❌   │ ❌   │ ✅   │
└──────────────────────────────────────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • PDF Resource (2 pgs)                                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Home Page (1 pgs)                                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap Page (1 pgs)                                                                              │
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
| tpl_0 | PDF Resource | Pages containing downloadable PDF resources. | https://www.donttakespasticity.com/content/dam/donttakespasticity/pdf/Don'tTakeSpasticity-DiscussionGuide.pdf, https://www.donttakespasticity.com/content/dam/donttakespasticity/pdf/adult-spasticity-discussion-guide-sheet.pdf | 2 |
| tpl_1 | Home Page | The main landing page of the website. | https://www.donttakespasticity.com/ | 1 |
| tpl_2 | Sitemap Page | A page displaying the website's sitemap. | https://www.donttakespasticity.com/sitemap | 1 |
