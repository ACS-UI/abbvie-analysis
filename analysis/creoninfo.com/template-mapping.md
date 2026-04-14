# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **70** URLs; **12** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Unassigned Agent Batch**, **Video Transcript**, **Creon Information**. **36** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:47:54.892Z
- **Website**: https://www.creoninfo.com/
- **Total Pages Analyzed**: 70
- **Total Templates Identified**: 12
- **Total Components Identified**: 36
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.CREONINFO.COM TEMPLATES                                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Unassigned Agent Batch               │    │ Video Transcript                     │    │ Creon Information                    │
│ (31 pages)                           │    │ (9 pages)                            │    │ (4 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Header {Unmapped}                  │
│ • —                                  │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Main Navigation {Unmapped}         │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Treatment Tracker                    │    │ Homepage                             │    │ PDF Document                         │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │    │ • —                                  │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • —                                  │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • —                                  │
│ • —                                  │    │ • CTA Banner {Unmapped}              │    │ • —                                  │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Associated Conditions                │    │ Treatment Information                │    │ Video Overview                       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Breadcrumb Navigation {Unmapped}   │
│ • Breadcrumb Navigation              │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Hero Section {Unmapped}            │
│ • (+2 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.CREONINFO.COM — SUB-TEMPLATES TEMPLATES                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Frequently Asked Questions           │    │ Diagnosis Information                │    │ Discussion Guide                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │    │ • Primary Navigation                 │
│ • Hero Section {Unmapped}            │    │ • Main Navigation                    │    │ • Hero Section                       │
│ • Breadcrumb Navigation {Unmapped}   │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Breadcrumb Navigation {Unmapped}   │
│ • FAQ Accordion {Unmapped}           │    │ • (+7 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Unassigned Agent Batch (`tpl_0`) — 31 pages

- —

### Video Transcript (`tpl_1`) — 9 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Hero Section
- Video Transcript {Unmapped}
- Important Safety Information {Unmapped}
- Footer Navigation {Unmapped}

### Creon Information (`tpl_2`) — 4 pages

- Utility Navigation {Unmapped}
- Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Breadcrumb {Unmapped}
- Resources Section {Unmapped}
- Support Features {Unmapped}
- Video Section {Unmapped}
- Next Best Message {Unmapped}
- Footer

### Treatment Tracker (`tpl_3`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}

### Homepage (`tpl_4`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Banner {Unmapped}
- Card Grid
- Info Tree {Unmapped}
- Footer

### PDF Document (`tpl_5`) — 1 pages

- —

### Associated Conditions (`tpl_6`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Breadcrumb Navigation
- Condition Details Accordion
- Page Footer

### Treatment Information (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section {Unmapped}
- Breadcrumb Navigation {Unmapped}
- PERT Information {Unmapped}
- Enzyme Cards {Unmapped}
- Spotlight Section {Unmapped}
- Diet and Lifestyle Callout {Unmapped}
- Sign-Up Call-to-Action {Unmapped}
- FAQ Accordion {Unmapped}

### Video Overview (`tpl_8`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Hero Section {Unmapped}
- Video Tabs {Unmapped}
- Footer Links {Unmapped}

### Frequently Asked Questions (`tpl_9`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Breadcrumb Navigation {Unmapped}
- FAQ Accordion {Unmapped}

### Diagnosis Information (`tpl_10`) — 1 pages

- Utility Navigation
- Primary Header
- Main Navigation
- Breadcrumb Navigation {Unmapped}
- Hero Section
- Diagnosis Information {Unmapped}
- Symptoms Quiz CTA {Unmapped}
- Spotlight Section {Unmapped}
- Diagnostic Tests
- Additional Resources {Unmapped}
- FAQ Accordion

### Discussion Guide (`tpl_11`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation
- Hero Section
- Breadcrumb Navigation {Unmapped}
- EPI Quiz {Unmapped}
- Discussion Guide Call-to-Action {Unmapped}
- Questions Section {Unmapped}
- Next Best Message {Unmapped}
- Safety Information {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                        │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Breadcrumb Navigation {Unmapped} │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section                     │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped}    │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Navigation {Unmapped}    │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Hero Section {Unmapped}          │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer                           │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ FAQ Accordion {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Navigation {Unmapped}       │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Next Best Message {Unmapped}     │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Navigation               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Spotlight Section {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└──────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                  │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Additional Resources {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Breadcrumb {Unmapped}                      │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Breadcrumb Navigation                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Card Grid                                  │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Condition Details Accordion                │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ CTA Banner {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Diagnosis Information {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Diagnostic Tests                           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Diet and Lifestyle Callout {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Discussion Guide Call-to-Action {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Enzyme Cards {Unmapped}                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ EPI Quiz {Unmapped}                        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Accordion                              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links {Unmapped}                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Unassigned Agent Batch (31 pgs)                                                                   │
│ • Video Transcript (9 pgs)                                                                          │
│ • Creon Information (4 pgs)                                                                         │
│ • Treatment Tracker (2 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • PDF Document (1 pgs)                                                                              │
│ • Associated Conditions (1 pgs)                                                                     │
│ • Treatment Information (1 pgs)                                                                     │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Video Overview (1 pgs)                                                                            │
│ • Frequently Asked Questions (1 pgs)                                                                │
│ • Diagnosis Information (1 pgs)                                                                     │
│ • Discussion Guide (1 pgs)                                                                          │
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
| tpl_0 | Unassigned Agent Batch | Pages grouped under unassigned agent category. | https://www.creoninfo.com/content/dam/creon/pdf/patient-education.pdf, https://www.creoninfo.com/content/dam/creon/pdf/creon-treatment-tracker.pdf, https://www.creoninfo.com/content/dam/creon/pdf/understanding-medicare-guide.pdf | 31 |
| tpl_1 | Video Transcript | Pages containing transcripts of videos. | https://www.creoninfo.com/videos/speaking-doctor-epi-transcript, https://www.creoninfo.com/videos/understanding-epi-creon-transcript, https://www.creoninfo.com/videos/taking-creon-with-food | 9 |
| tpl_2 | Creon Information | Pages related to Creon product details and transcripts. | https://www.creoninfo.com/creon-complete, https://www.creoninfo.com/creon-complete/non-cf-track-it-transcript, https://www.creoninfo.com/about-creon | 4 |
| tpl_3 | Treatment Tracker | Pages for tracking treatment progress. | https://www.creoninfo.com/staying-on-track, https://www.creoninfo.com/on-course | 2 |
| tpl_4 | Homepage | The main landing page of the website. | https://www.creoninfo.com/ | 1 |
| tpl_5 | PDF Document | Pages containing downloadable PDF documents. | https://www.creoninfo.com/content/dam/creon/pdf/creon-doctor-discussion-guide.pdf | 1 |
| tpl_6 | Associated Conditions | Pages describing conditions related to the topic. | https://www.creoninfo.com/associated-conditions | 1 |
| tpl_7 | Treatment Information | Pages providing details on treatments. | https://www.creoninfo.com/treating-epi | 1 |
| tpl_8 | Video Overview | Pages showcasing video summaries. | https://www.creoninfo.com/videos | 1 |
| tpl_9 | Frequently Asked Questions | Pages answering common questions. | https://www.creoninfo.com/faq | 1 |
| tpl_10 | Diagnosis Information | Pages providing diagnostic details. | https://www.creoninfo.com/epi-diagnosis | 1 |
| tpl_11 | Discussion Guide | Pages offering guides for discussions. | https://www.creoninfo.com/doctor-discussion-guide | 1 |
