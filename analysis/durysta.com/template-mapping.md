# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **5** URLs; **5** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Durysta Homepage**, **Durysta About Page**, **Durysta Sitemap**. **24** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:29:50.568Z
- **Website**: https://www.durysta.com/
- **Total Pages Analyzed**: 5
- **Total Templates Identified**: 5
- **Total Components Identified**: 24
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DURYSTA.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Durysta Homepage                     │    │ Durysta About Page                   │    │ Durysta Sitemap                      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Header                        │    │ • Page Header                        │    │ • Primary Header                     │
│ • Main Content Area {Unmapped}       │    │ • Hero Section                       │    │ • Sitemap Title {Unmapped}           │
│ • Secondary Content Area {Unmapped}  │    │ • Non-Drop Treatment {Unmapped}      │    │ • Sitemap Links {Unmapped}           │
│ • Savings Program Section {Unmapped} │    │ • Testimonials Section {Unmapped}    │    │ • ISI Fragment                       │
│ • (+2 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • Primary Footer                     │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Durysta Doctor Discussion            │    │ Durysta Why Section                  │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Hero Section                       │    │ • Hero Section                       │
│ • Introduction Text {Unmapped}       │    │ • People Who Section                 │
│ • Three Card Grid                    │    │ • Video Cards Section                │
│ • FAQ Section {Unmapped}             │    │ • Action Cards Section               │
│ • (+2 more — see Blocks mapped per … │    │ • ISI Fragment                       │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Durysta Homepage (`tpl_0`) — 1 pages

- Site Header
- Main Content Area {Unmapped}
- Secondary Content Area {Unmapped}
- Savings Program Section {Unmapped}
- Eligibility Criteria Section {Unmapped}
- Terms and Conditions Section {Unmapped}

### Durysta About Page (`tpl_1`) — 1 pages

- Page Header
- Hero Section
- Non-Drop Treatment {Unmapped}
- Testimonials Section {Unmapped}
- Why Consider DURYSTA {Unmapped}
- Action Cards
- ISI Fragment
- Page Footer

### Durysta Sitemap (`tpl_2`) — 1 pages

- Primary Header
- Sitemap Title {Unmapped}
- Sitemap Links {Unmapped}
- ISI Fragment
- Primary Footer

### Durysta Doctor Discussion (`tpl_3`) — 1 pages

- Hero Section
- Introduction Text {Unmapped}
- Three Card Grid
- FAQ Section {Unmapped}
- Action Cards {Unmapped}
- ISI Fragment {Unmapped}

### Durysta Why Section (`tpl_4`) — 1 pages

- Hero Section
- People Who Section
- Video Cards Section
- Action Cards Section
- ISI Fragment


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┬─────┬─────┬─────┬─────┐
│ Component                    │ T1  │ T2  │ T3  │ T4  │ T5  │
├──────────────────────────────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                 │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ ISI Fragment                 │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │
└──────────────────────────────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┤
│ Action Cards                            │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Action Cards {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Action Cards Section                    │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Eligibility Criteria Section {Unmapped} │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Section {Unmapped}                  │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Introduction Text {Unmapped}            │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ ISI Fragment {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Main Content Area {Unmapped}            │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Non-Drop Treatment {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Page Footer                             │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Page Header                             │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ People Who Section                      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Primary Footer                          │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Primary Header                          │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Durysta Homepage (1 pgs)                                                                          │
│ • Durysta About Page (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Durysta Sitemap (1 pgs)                                                                           │
│ • Durysta Doctor Discussion (1 pgs)                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Durysta Why Section (1 pgs)                                                                       │
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
| tpl_0 | Durysta Homepage | The main landing page for Durysta. | https://www.durysta.com/ | 1 |
| tpl_1 | Durysta About Page | Information about the Durysta product. | https://www.durysta.com/about | 1 |
| tpl_2 | Durysta Sitemap | The sitemap page for Durysta website navigation. | https://www.durysta.com/sitemap | 1 |
| tpl_3 | Durysta Doctor Discussion | Content for discussing Durysta with healthcare professionals. | https://www.durysta.com/talk-with-your-doctor | 1 |
| tpl_4 | Durysta Why Section | Section explaining the benefits and reasons to choose Durysta. | https://www.durysta.com/why-durysta | 1 |
