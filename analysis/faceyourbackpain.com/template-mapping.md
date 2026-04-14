# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **44** URLs; **20** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Before Diagnosis Transcript — group 11**, **Ankylosing Spondylitis Nraxspa Treatment — group 17**, **Homepage and Personalization**. **68** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:02:04.670Z
- **Website**: https://www.faceyourbackpain.com/
- **Total Pages Analyzed**: 44
- **Total Templates Identified**: 20
- **Total Components Identified**: 68
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.FACEYOURBACKPAIN.COM TEMPLATES                                           │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Before Diagnosis Transcript — group… │    │ Ankylosing Spondylitis Nraxspa Trea… │    │ Homepage and Personalization         │
│ (6 pages)                            │    │ (3 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Content Columns {Unmapped}         │    │ • Hero Section                       │    │ • Mega Navigation {Unmapped}         │
│ • Footer Links                       │    │ • Treatment Options Content {Unmapp… │    │ • Hero Section                       │
│ • Back to Top Button {Unmapped}      │    │ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Living with Ankylosing Spondylitis   │    │ Disease Diagnosis                    │    │ Symptoms Overview                    │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Strip {Unmapped}           │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Introduction Content {Unmapped}    │    │ • Introduction Paragraph {Unmapped}  │    │ • Content Columns {Unmapped}         │
│ • (+6 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Ankylosing Spondylitis Resources — … │    │ Find Rheumatologist — group 10       │    │ Page layout group 12                 │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header {Unmapped}          │    │ • Primary Header                     │    │ • Primary Header                     │
│ • Mega Navigation {Unmapped}         │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Footer Navigation                  │
│ • (+5 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 15                 │    │ Ankylosing Spondylitis Nraxspa — gr… │    │ Ankylosing Spondylitis Patient Stor… │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation          │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation                 │    │ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │
│ • Main Content Columns               │    │ • Hero Section                       │    │ • Video Section - Before Diagnosis   │
│ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Information Registration             │    │ Sitemap                              │    │ Search Results — group 8             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Footer Links                       │    │ • Site Logo {Unmapped}               │
│ • Information Introduction {Unmappe… │    │ • —                                  │    │ • Search Bar                         │
│ • (+4 more — see Blocks mapped per … │    │ • —                                  │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.FACEYOURBACKPAIN.COM — SUB-TEMPLATES TEMPLATES                           │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Take The Quiz — group 9              │    │ Site Map — group 13                  │    │ Doctor Discussion Guide — group 14   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • —                                  │    │ • Form Embed                         │
│ • Quiz Introduction {Unmapped}       │    │ • —                                  │    │ • Call to Action Section {Unmapped}  │
│ • (+6 more — see Blocks mapped per … │    │ • —                                  │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Why A Rheumatologist — group 18      │    │ Thank You Page — group 20            │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │
│ • Image and Text Columns {Unmapped}  │    │ • Main Content Columns {Unmapped}    │
│ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Before Diagnosis Transcript — group 11 (`tpl_10`) — 6 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Content Columns {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Ankylosing Spondylitis Nraxspa Treatment — group 17 (`tpl_16`) — 3 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Treatment Options Content {Unmapped}
- Facts Section {Unmapped}
- Call to Action {Unmapped}
- References Accordion
- Footer

### Homepage and Personalization (`tpl_0`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Mega Navigation {Unmapped}
- Hero Section
- Carousel Spotlight
- Information Tree {Unmapped}
- Three Column CTA {Unmapped}
- Real People Section {Unmapped}
- Connect with Others {Unmapped}
- Footer Navigation

### Living with Ankylosing Spondylitis (`tpl_2`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Content {Unmapped}
- Exercise Section {Unmapped}
- Wellness Book CTA {Unmapped}
- Face the Facts Section {Unmapped}
- Features Section {Unmapped}
- References Section {Unmapped}
- Footer

### Disease Diagnosis (`tpl_3`) — 2 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Paragraph {Unmapped}
- Diagnosis Steps {Unmapped}
- Diagnosis Images {Unmapped}
- Mechanical vs Inflammatory Comparison {Unmapped}
- Face the Facts Section {Unmapped}
- CTA: Take the Quiz {Unmapped}
- References Accordion
- Footer

### Symptoms Overview (`tpl_4`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Symptoms List {Unmapped}
- Comparison Table
- Interactive Hotspots {Unmapped}
- CTA: Assess Symptoms {Unmapped}
- Causes Section {Unmapped}
- Questionnaire Section {Unmapped}

### Ankylosing Spondylitis Resources — group 7 (`tpl_6`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Mega Navigation {Unmapped}
- Hero Section {Unmapped}
- Introductory Text {Unmapped}
- Resource Links Grid {Unmapped}
- Call-to-Action Section {Unmapped}
- Sidebar Promotion {Unmapped}
- Footer Navigation {Unmapped}

### Find Rheumatologist — group 10 (`tpl_9`) — 2 pages

- Utility Navigation
- Primary Header
- Primary Navigation
- Hero Section
- Introduction Text
- Doctor Locator
- Note Section
- Call-to-Action Section
- Footer Links
- Back to Top Button {Unmapped}

### Page layout group 12 (`tpl_11`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Header
- Primary Navigation {Unmapped}
- Footer Navigation

### Page layout group 15 (`tpl_14`) — 2 pages

- Global Utility Navigation
- Primary Navigation
- Hero Section
- Main Content Columns
- Info Tree Question
- Feature Section
- Call-to-Action Section {Unmapped}
- References Accordion
- Footer

### Ankylosing Spondylitis Nraxspa — group 16 (`tpl_15`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Header
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Columns {Unmapped}
- Comparison Section {Unmapped}
- Info Tree Question {Unmapped}
- Statistics Section {Unmapped}
- Footer

### Ankylosing Spondylitis Patient Stories — group 19 (`tpl_18`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Video Section - Before Diagnosis
- Video Section - Getting Diagnosed
- Video Section - Life After Diagnosis
- Connect Section {Unmapped}
- Feature Section {Unmapped}
- Footer

### Information Registration (`tpl_1`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Information Introduction {Unmapped}
- Image and Text Section
- Form Embed
- Footer Links
- Back to Top Button {Unmapped}

### Sitemap (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Footer Links

### Search Results — group 8 (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Site Logo {Unmapped}
- Search Bar
- Search Results {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}
- Modal Component

### Take The Quiz — group 9 (`tpl_8`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Quiz Introduction {Unmapped}
- Interactive Quiz Form {Unmapped}
- Disclaimer Section {Unmapped}
- Call-to-Action 1 {Unmapped}
- Call-to-Action 2 {Unmapped}
- References Accordion
- Site Footer

### Site Map — group 13 (`tpl_12`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}

### Doctor Discussion Guide — group 14 (`tpl_13`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Form Embed
- Call to Action Section {Unmapped}
- Feature Section {Unmapped}
- References Accordion
- Footer Links

### Why A Rheumatologist — group 18 (`tpl_17`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Image and Text Columns {Unmapped}
- CTA Section {Unmapped}
- Fact Box {Unmapped}
- Feature Highlights {Unmapped}
- Accordion References {Unmapped}
- Footer

### Thank You Page — group 20 (`tpl_19`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Columns {Unmapped}
- Patient Stories CTA {Unmapped}
- Features Section {Unmapped}
- Footer Links {Unmapped}
- Back to Top Button {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}        │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Hero Section                         │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Footer                               │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}        │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links                         │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}        │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}      │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Hero Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ References Accordion                 │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Primary Header                       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Header {Unmapped}            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Primary Navigation                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T20 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                         │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion References {Unmapped}   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action {Unmapped}         │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action 1 {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action 2 {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Carousel Spotlight                │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Causes Section {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Comparison Section {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Comparison Table                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Connect Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Connect with Others {Unmapped}    │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Section {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA: Assess Symptoms {Unmapped}   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└───────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T20 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Before Diagnosis Transcript — group 11 (6 pgs)                                                    │
│ • Ankylosing Spondylitis Nraxspa Treatment — group 17 (3 pgs)                                       │
│ • Homepage and Personalization (2 pgs)                                                              │
│ • Living with Ankylosing Spondylitis (2 pgs)                                                        │
│ • Disease Diagnosis (2 pgs)                                                                         │
│ • Symptoms Overview (2 pgs)                                                                         │
│ • Ankylosing Spondylitis Resources — group 7 (2 pgs)                                                │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Find Rheumatologist — group 10 (2 pgs)                                                            │
│ • Page layout group 12 (2 pgs)                                                                      │
│ • Page layout group 15 (2 pgs)                                                                      │
│ • Ankylosing Spondylitis Nraxspa — group 16 (2 pgs)                                                 │
│ • Ankylosing Spondylitis Patient Stories — group 19 (2 pgs)                                         │
│ • Information Registration (1 pgs)                                                                  │
│ • Sitemap (1 pgs)                                                                                   │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Search Results — group 8 (1 pgs)                                                                  │
│ • Take The Quiz — group 9 (1 pgs)                                                                   │
│ • Site Map — group 13 (1 pgs)                                                                       │
│ • Doctor Discussion Guide — group 14 (1 pgs)                                                        │
│ • Why A Rheumatologist — group 18 (1 pgs)                                                           │
│ • Thank You Page — group 20 (1 pgs)                                                                 │
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
| tpl_0 | Homepage and Personalization | The main landing pages of the site introducing Ankylosing Spondylitis and user personalization options. | https://www.faceyourbackpain.com/, https://www.faceyourbackpain.com/personalization | 2 |
| tpl_1 | Information Registration | Pages for users to sign up for free resources and information about Ankylosing Spondylitis. | https://www.faceyourbackpain.com/get-more-information | 1 |
| tpl_2 | Living with Ankylosing Spondylitis | Pages providing advice and resources for managing life with Ankylosing Spondylitis. | https://www.faceyourbackpain.com/living-with-ankylosing-spondylitis-nraxspa, https://www.faceyourbackpain.com/living-with-ankylosing-spondylitis | 2 |
| tpl_3 | Disease Diagnosis | Educational pages detailing the diagnosis process for Ankylosing Spondylitis and related conditions. | https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-diagnosis, https://www.faceyourbackpain.com/ankylosing-spondylitis-diagnosis | 2 |
| tpl_4 | Symptoms Overview | Detailed explanations of the symptoms associated with Ankylosing Spondylitis and related conditions. | https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-symptoms, https://www.faceyourbackpain.com/ankylosing-spondylitis-symptoms | 2 |
| tpl_5 | Sitemap | A navigational page listing all the sections and links available on the site. | https://www.faceyourbackpain.com/sitemap | 1 |
| tpl_6 | Ankylosing Spondylitis Resources — group 7 | Same structural layout across 2 page(s) in the crawl. | https://www.faceyourbackpain.com/ankylosing-spondylitis-resources, https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-resources | 2 |
| tpl_7 | Search Results — group 8 | Same structural layout across 1 page(s) in the crawl. | https://www.faceyourbackpain.com/search-results | 1 |
| tpl_8 | Take The Quiz — group 9 | Same structural layout across 1 page(s) in the crawl. | https://www.faceyourbackpain.com/take-the-quiz | 1 |
| tpl_9 | Find Rheumatologist — group 10 | Same structural layout across 2 page(s) in the crawl. | https://www.faceyourbackpain.com/find-rheumatologist, https://www.faceyourbackpain.com/find-rheumatologist.html | 2 |
| tpl_10 | Before Diagnosis Transcript — group 11 | Same structural layout across 6 page(s) in the crawl. | https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-patient-stories/before-diagnosis-transcript, https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-patient-stories/life-after-diagnosis-transcript, https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-patient-stories/getting-my-diagnosis-transcript | 6 |
| tpl_11 | Page layout group 12 | Same structural layout across 2 page(s) in the crawl. | https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-diet-and-exercise, https://www.faceyourbackpain.com/ankylosing-spondylitis-diet-and-exercise | 2 |
| tpl_12 | Site Map — group 13 | Same structural layout across 1 page(s) in the crawl. | https://www.faceyourbackpain.com/site-map | 1 |
| tpl_13 | Doctor Discussion Guide — group 14 | Same structural layout across 1 page(s) in the crawl. | https://www.faceyourbackpain.com/doctor-discussion-guide | 1 |
| tpl_14 | Page layout group 15 | Same structural layout across 2 page(s) in the crawl. | https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-in-women-vs-men, https://www.faceyourbackpain.com/ankylosing-spondylitis-in-women-vs-men | 2 |
| tpl_15 | Ankylosing Spondylitis Nraxspa — group 16 | Same structural layout across 2 page(s) in the crawl. | https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa, https://www.faceyourbackpain.com/ankylosing-spondylitis | 2 |
| tpl_16 | Ankylosing Spondylitis Nraxspa Treatment — group 17 | Same structural layout across 3 page(s) in the crawl. | https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-treatment, https://www.faceyourbackpain.com/ankylosing-spondylitis-treatment, https://www.faceyourbackpain.com/treatment-options | 3 |
| tpl_17 | Why A Rheumatologist — group 18 | Same structural layout across 1 page(s) in the crawl. | https://www.faceyourbackpain.com/why-a-rheumatologist | 1 |
| tpl_18 | Ankylosing Spondylitis Patient Stories — group 19 | Same structural layout across 2 page(s) in the crawl. | https://www.faceyourbackpain.com/ankylosing-spondylitis-patient-stories, https://www.faceyourbackpain.com/ankylosing-spondylitis-nraxspa-patient-stories | 2 |
| tpl_19 | Thank You Page — group 20 | Same structural layout across 1 page(s) in the crawl. | https://www.faceyourbackpain.com/thank_you_page | 1 |
