# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **73** URLs; **12** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Article Pages**, **Agent Unassigned Batch 2**, **Resource Documents**. **46** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:06:29.490Z
- **Website**: https://www.nobsabouths.com/
- **Total Pages Analyzed**: 73
- **Total Templates Identified**: 12
- **Total Components Identified**: 46
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.NOBSABOUTHS.COM TEMPLATES                                                │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Article Pages                        │    │ Agent Unassigned Batch 2             │    │ Resource Documents                   │
│ (10 pages)                           │    │ (9 pages)                            │    │ (8 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • AdChoices Modal                    │    │ • —                                  │
│ • Primary Navigation {Unmapped}      │    │ • Facebook Modal                     │    │ • —                                  │
│ • Hero Section                       │    │ • YouTube Modal                      │    │ • —                                  │
│ • Content Columns {Unmapped}         │    │ • Instagram Modal                    │    │ • —                                  │
│ • (+3 more — see Blocks mapped per … │    │ • Back to Top Button {Unmapped}      │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Interactive Tools                    │    │ Homepage Variants                    │    │ Personalization Features             │
│ (4 pages)                            │    │ (3 pages)                            │    │ (3 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Personalized CTAs Section {Unmapp… │
│ • Primary Navigation                 │    │ • Primary Header {Unmapped}          │    │ • —                                  │
│ • Hero Section                       │    │ • Hero Section                       │    │ • —                                  │
│ • Introductory Text {Unmapped}       │    │ • Content Columns {Unmapped}         │    │ • —                                  │
│ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Overview Pages                       │    │ Search Results                       │    │ Reference Glossaries                 │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Header {Unmapped}           │    │ • Global Utility Navigation {Unmapp… │
│ • Main Header {Unmapped}             │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Mega Navigation Menu {Unmapped}    │    │ • Search Box                         │    │ • Hero Section {Unmapped}            │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Glossary Content {Unmapped}        │
│ • (+8 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.NOBSABOUTHS.COM — SUB-TEMPLATES TEMPLATES                                │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Navigation Pages                     │    │ Feedback Pages                       │    │ Engagement Pages                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │
│ • Hero Title {Unmapped}              │    │ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │
│ • Sitemap Columns {Unmapped}         │    │ • Mega Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │
│ • Footer                             │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • (+2 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Article Pages (`tpl_0`) — 10 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Video Player
- Inline Callouts {Unmapped}
- Footer

### Agent Unassigned Batch 2 (`tpl_1`) — 9 pages

- AdChoices Modal
- Facebook Modal
- YouTube Modal
- Instagram Modal
- Back to Top Button {Unmapped}

### Resource Documents (`tpl_2`) — 8 pages

- —

### Interactive Tools (`tpl_3`) — 4 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Introductory Text {Unmapped}
- Dermatologist Locator Tool
- Side Navigation
- Side Tout
- Footer Links
- Back to Top Button {Unmapped}

### Homepage Variants (`tpl_4`) — 3 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Call to Action {Unmapped}
- Footer Links
- Back to Top {Unmapped}
- Cookie Consent {Unmapped}
- Search Bar {Unmapped}

### Personalization Features (`tpl_5`) — 3 pages

- Personalized CTAs Section {Unmapped}

### Overview Pages (`tpl_6`) — 2 pages

- Global Utility Navigation {Unmapped}
- Main Header {Unmapped}
- Mega Navigation Menu {Unmapped}
- Hero Section
- CTA Links {Unmapped}
- Page Title {Unmapped}
- Introductory Text {Unmapped}
- Image with Description {Unmapped}
- Detailed Content {Unmapped}
- Affected Areas {Unmapped}
- Interactive Quiz {Unmapped}
- Footer

### Search Results (`tpl_7`) — 1 pages

- Global Header {Unmapped}
- Primary Navigation {Unmapped}
- Search Box
- Hero Section {Unmapped}
- Search Results {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Modal Dialogs {Unmapped}

### Reference Glossaries (`tpl_8`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Glossary Content {Unmapped}
- Footer Links {Unmapped}
- Back to Top Button {Unmapped}

### Navigation Pages (`tpl_9`) — 1 pages

- Global Header {Unmapped}
- Hero Title {Unmapped}
- Sitemap Columns {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Modal Overlays {Unmapped}

### Feedback Pages (`tpl_10`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Mega Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Columns {Unmapped}
- Call-to-Action Section {Unmapped}
- Social Links {Unmapped}
- Footer Navigation {Unmapped}
- Back to Top Button {Unmapped}
- Modal Overlays {Unmapped}

### Engagement Pages (`tpl_11`) — 1 pages

- Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns - Diagnosis Info {Unmapped}
- Submission Form
- Footer Links
- Back to Top Button {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Back to Top Button {Unmapped}        │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Hero Section                         │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Footer                               │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Primary Navigation {Unmapped}        │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns {Unmapped}           │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Links                         │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Hero Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Header {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Global Header {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Introductory Text {Unmapped}         │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Modal Overlays {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}        │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


### Template-specific components

```
┌─────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                   │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ AdChoices Modal                             │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Affected Areas {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Back to Top {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call to Action {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns - Diagnosis Info {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Cookie Consent {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ CTA Links {Unmapped}                        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Dermatologist Locator Tool                  │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Detailed Content {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Facebook Modal                              │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links {Unmapped}                     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Navigation {Unmapped}                │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Article Pages (10 pgs)                                                                            │
│ • Agent Unassigned Batch 2 (9 pgs)                                                                  │
│ • Resource Documents (8 pgs)                                                                        │
│ • Interactive Tools (4 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage Variants (3 pgs)                                                                         │
│ • Personalization Features (3 pgs)                                                                  │
│ • Overview Pages (2 pgs)                                                                            │
│ • Search Results (1 pgs)                                                                            │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Reference Glossaries (1 pgs)                                                                      │
│ • Navigation Pages (1 pgs)                                                                          │
│ • Feedback Pages (1 pgs)                                                                            │
│ • Engagement Pages (1 pgs)                                                                          │
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
| tpl_0 | Article Pages | Templates for articles, including educational content and patient stories. | https://www.nobsabouths.com/what-is-hidradenitis-suppurativa/what-causes-hs, https://www.nobsabouths.com/hs-patient-stories/meetpreshus-transcript, https://www.nobsabouths.com/treat-hidradenitis-suppurativa/treatment-options | 10 |
| tpl_1 | Agent Unassigned Batch 2 | Template group "agent_unassigned_batch_2" from agent grouping (no merge metadata). | https://www.nobsabouths.com/hs-patient-stories/meetsterling-transcript, https://www.nobsabouths.com/hs-awareness, https://www.nobsabouths.com/hs-patient-stories/meettara-transcript2 | 9 |
| tpl_2 | Resource Documents | Templates for downloadable resources and guides. | https://www.nobsabouths.com/content/dam/nobsabouthsivy/docs/ConversationGuide_DownloadPDF_Spouse.pdf, https://www.nobsabouths.com/content/dam/nobsabouthsivy/docs/ConversationGuide_DownloadPDF_FF.pdf, https://www.nobsabouths.com/content/dam/nobsabouthsivy/docs/ConversationGuide_DownloadPDF_Self.pdf | 8 |
| tpl_3 | Interactive Tools | Templates for tools that provide interactive functionalities. | https://www.nobsabouths.com/treat-hidradenitis-suppurativa/dermatologist-near-me, https://www.nobsabouths.com/what-is-hidradenitis-suppurativa/check-my-symptoms, https://www.nobsabouths.com/hs-symptom-quiz | 4 |
| tpl_4 | Homepage Variants | Templates representing variations of the homepage for different contexts. | https://www.nobsabouths.com/, https://www.nobsabouths.com/rootpage-alt, https://www.nobsabouths.com/personalization | 3 |
| tpl_5 | Personalization Features | Templates for personalization elements and callouts. | https://www.nobsabouths.com/personalization/callouts, https://www.nobsabouths.com/personalization/recommended-for-you, https://www.nobsabouths.com/personalization/left-rail-touts | 3 |
| tpl_6 | Overview Pages | Templates providing overviews of topics or sections. | https://www.nobsabouths.com/what-is-hidradenitis-suppurativa, https://www.nobsabouths.com/treat-hidradenitis-suppurativa | 2 |
| tpl_7 | Search Results | Templates for displaying search results. | https://www.nobsabouths.com/search-results | 1 |
| tpl_8 | Reference Glossaries | Templates for glossary and reference content. | https://www.nobsabouths.com/glossary | 1 |
| tpl_9 | Navigation Pages | Templates for site navigation structures. | https://www.nobsabouths.com/sitemap | 1 |
| tpl_10 | Feedback Pages | Templates for user feedback submission pages. | https://www.nobsabouths.com/thanks-for-the-answer | 1 |
| tpl_11 | Engagement Pages | Templates designed to foster user engagement. | https://www.nobsabouths.com/share-your-voice | 1 |
