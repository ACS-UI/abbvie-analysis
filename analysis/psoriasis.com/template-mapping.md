# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **82** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Error Page**, **Agent Unassigned Page**, **Content Article Page**. **26** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:08:26.327Z
- **Website**: https://www.psoriasis.com/
- **Total Pages Analyzed**: 82
- **Total Templates Identified**: 8
- **Total Components Identified**: 26
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.PSORIASIS.COM TEMPLATES                                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Error Page                           │    │ Agent Unassigned Page                │    │ Content Article Page                 │
│ (30 pages)                           │    │ (25 pages)                           │    │ (13 pages)                           │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Main Content Columns {Unmapped}    │    │ • Thank You Message {Unmapped}       │    │ • Introductory Content {Unmapped}    │
│ • (+5 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Generic Page                         │    │ Psoriasis Tips Page                  │    │ Inline Links Demo Page               │
│ (4 pages)                            │    │ (3 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Image and Text Component {Unmappe… │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Support Section {Unmapped}         │    │ • Content Columns {Unmapped}         │
│ • —                                  │    │ • (+4 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.PSORIASIS.COM — SUB-TEMPLATES TEMPLATES                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Search Results Page                  │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Search Bar                         │
│ • Quick Poll {Unmapped}              │    │ • Hero Section {Unmapped}            │
│ • (+3 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Error Page (`tpl_0`) — 30 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Columns {Unmapped}
- Quick Poll {Unmapped}
- Image and Text Block {Unmapped}
- Video Player {Unmapped}
- Side Navigation {Unmapped}
- Recommended Topics {Unmapped}

### Agent Unassigned Page (`tpl_1`) — 25 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Thank You Message {Unmapped}
- Recommended Topics {Unmapped}
- Footer Navigation {Unmapped}

### Content Article Page (`tpl_2`) — 13 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introductory Content {Unmapped}
- Image and Text Component {Unmapped}
- Accordion Section
- Footer

### Generic Page (`tpl_3`) — 4 pages

- Image and Text Component {Unmapped}

### Psoriasis Tips Page (`tpl_4`) — 3 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Support Section {Unmapped}
- Referral Section {Unmapped}
- Insurance Coverage Section {Unmapped}
- Recommended Topics {Unmapped}
- Footer

### Inline Links Demo Page (`tpl_5`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Thank You Section {Unmapped}
- Recommended Topics {Unmapped}
- Footer Links

### Homepage (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Quick Poll {Unmapped}
- Find Doctor CTA {Unmapped}
- Recommended Topics {Unmapped}
- Footer

### Search Results Page (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Search Bar
- Hero Section {Unmapped}
- Search Results {Unmapped}
- Footer Links


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}        │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Recommended Topics {Unmapped}        │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Utility Navigation {Unmapped}        │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Hero Section {Unmapped}              │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer                               │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Hero Section                         │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Footer Links                         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Image and Text Component {Unmapped}  │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Quick Poll {Unmapped}                │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                             │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Section                     │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Find Doctor CTA {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Navigation {Unmapped}          │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Image and Text Block {Unmapped}       │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Insurance Coverage Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Introductory Content {Unmapped}       │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Content Columns {Unmapped}       │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Header {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Referral Section {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Search Bar                            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Search Results {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Side Navigation {Unmapped}            │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Support Section {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└───────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Error Page (30 pgs)                                                                               │
│ • Agent Unassigned Page (25 pgs)                                                                    │
│ • Content Article Page (13 pgs)                                                                     │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Generic Page (4 pgs)                                                                              │
│ • Psoriasis Tips Page (3 pgs)                                                                       │
│ • Inline Links Demo Page (2 pgs)                                                                    │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Search Results Page (1 pgs)                                                                       │
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
| tpl_0 | Error Page | Pages showing error messages. | https://www.psoriasis.com/psoriasis-treatment-doctor/find-a-psoriasis-specialist, https://www.psoriasis.com/psoriasis-treatment-doctor/dermatologist-visit, https://www.psoriasis.com/about-psoriasis/psoriasis-severity | 30 |
| tpl_1 | Agent Unassigned Page | Pages indicating unassigned agents. | https://www.psoriasis.com/about-psoriasis/symptoms-quiz/results, https://www.psoriasis.com/about-psoriasis/psoriasis-causes/science-of-the-skin-transcript, https://www.psoriasis.com/psoriasis-patients/psoriasis-support | 25 |
| tpl_2 | Content Article Page | Pages displaying content articles. | https://www.psoriasis.com/about-psoriasis/psoriasis-types, https://www.psoriasis.com/about-psoriasis/what-is-psoriasis, https://www.psoriasis.com/about-psoriasis/psoriasis-symptoms | 13 |
| tpl_3 | Generic Page | Pages with generic content. | https://www.psoriasis.com/hidden-panels/hidden-panel-02, https://www.psoriasis.com/hidden-panels, https://www.psoriasis.com/hidden-panels/hidden-panel-021 | 4 |
| tpl_4 | Psoriasis Tips Page | Pages providing tips for psoriasis. | https://www.psoriasis.com/psoriasis-patients/tips/finding-psoriasis-doctor-dermatology-specialist, https://www.psoriasis.com/psoriasis-patients/tips/psoriasis-winter-tips, https://www.psoriasis.com/living-with-psoriasis/psoriasis-kit/example-test | 3 |
| tpl_5 | Inline Links Demo Page | Pages demonstrating inline links. | https://www.psoriasis.com/psoriasis-treatment-doctor/questions-to-ask-your-doctor-v2/results, https://www.psoriasis.com/inline-links-demo | 2 |
| tpl_6 | Homepage | The main landing page of the site. | https://www.psoriasis.com/ | 1 |
| tpl_7 | Search Results Page | Pages displaying search results. | https://www.psoriasis.com/search-results | 1 |
