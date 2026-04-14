# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **62** URLs; **16** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Resource Documents**, **Healthcare Professional Resources**, **Transcripts**. **58** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:26:27.047Z
- **Website**: https://www.mavyret.com/
- **Total Pages Analyzed**: 62
- **Total Templates Identified**: 16
- **Total Components Identified**: 58
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.MAVYRET.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Resource Documents                   │    │ Healthcare Professional Resources    │    │ Transcripts                          │
│ (17 pages)                           │    │ (10 pages)                           │    │ (5 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Indication Information {Unmapped}  │    │ • Transcript Content {Unmapped}      │
│ • —                                  │    │ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Cost Information                     │    │ Treatment Details                    │    │ About Information                    │
│ (3 pages)                            │    │ (3 pages)                            │    │ (3 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Banner                        │    │ • Hero Section                       │
│ • Introduction Text {Unmapped}       │    │ • Call-to-Action Area {Unmapped}     │    │ • About Hep C Section {Unmapped}     │
│ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Search Results Pages                 │    │ Homepage                             │    │ Locator Pages                        │
│ (3 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Search Results                     │    │ • Highlighted Call-to-Action {Unmap… │    │ • Doctor Locator Form                │
│ • (+3 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Side Effects Information             │    │ Patient Support Resources            │    │ Patient Stories                      │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │
│ • Main Header {Unmapped}             │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Side Effects Summary {Unmapped}    │    │ • Carousel Section                   │    │ • Patient Story Videos {Unmapped}    │
│ • (+3 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.MAVYRET.COM — SUB-TEMPLATES TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap Pages                        │    │ Product Info                         │    │ Testing Info                         │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Utility Navigation                 │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Header {Unmapped}          │
│ • Hero Section {Unmapped}            │    │ • Hero Banner                        │    │ • Hero Section                       │
│ • Sitemap Links {Unmapped}           │    │ • Call to Action Cards               │    │ • Introduction Paragraph {Unmapped}  │
│ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Espanol Liver Transcription          │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Navigation                 │
│ • Primary Navigation                 │
│ • Hero Section                       │
│ • Video Transcription {Unmapped}     │
│ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Resource Documents (`tpl_0`) — 17 pages

- —

### Healthcare Professional Resources (`tpl_1`) — 10 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Indication Information {Unmapped}
- Ambassador Support {Unmapped}
- Enrollment Call-to-Action {Unmapped}
- Resources Call-to-Action {Unmapped}
- Safety Information {Unmapped}
- Footer Links

### Transcripts (`tpl_2`) — 5 pages

- Global Utility Navigation {Unmapped}
- Primary Header
- Hero Section
- Transcript Content {Unmapped}
- Safety Considerations {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Legal Disclaimer {Unmapped}

### Cost Information (`tpl_3`) — 3 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Introduction Text {Unmapped}
- Description Section {Unmapped}
- Cost Information {Unmapped}
- Insurance Support {Unmapped}
- Savings Program {Unmapped}
- Footer

### Treatment Details (`tpl_4`) — 3 pages

- Utility Navigation {Unmapped}
- Primary Header
- Hero Banner
- Call-to-Action Area {Unmapped}
- Routine Grid {Unmapped}
- Missed Dose Guide {Unmapped}
- Video Player {Unmapped}
- Support Cards
- Safety Information {Unmapped}

### About Information (`tpl_5`) — 3 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- About Hep C Section {Unmapped}
- Video Section
- Spread Information Section {Unmapped}
- Testing Information Section {Unmapped}
- Call-to-Action Section {Unmapped}
- Footer Safety Information

### Search Results Pages (`tpl_6`) — 3 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Search Results
- Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Homepage (`tpl_7`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Highlighted Call-to-Action {Unmapped}
- Information Section {Unmapped}
- Image and Text Block {Unmapped}
- Video Section {Unmapped}
- Card Grid Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer {Unmapped}

### Locator Pages (`tpl_8`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Doctor Locator Form
- Callout Section {Unmapped}
- Two Column Cards
- Important Safety Information {Unmapped}
- Footer Links {Unmapped}

### Side Effects Information (`tpl_9`) — 2 pages

- Utility Navigation {Unmapped}
- Main Header {Unmapped}
- Hero Section
- Side Effects Summary {Unmapped}
- Patient Quote
- Safety Information {Unmapped}
- Footer Section

### Patient Support Resources (`tpl_10`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Carousel Section
- Sign-Up Form
- Testimonial Section {Unmapped}
- Doctor Locator {Unmapped}
- Two Column CTA {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Patient Stories (`tpl_11`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Patient Story Videos {Unmapped}
- Share Your Story {Unmapped}
- Two Column CTAs {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links

### Sitemap Pages (`tpl_12`) — 2 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Sitemap Links {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Product Info (`tpl_13`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Banner
- Call to Action Cards
- Video Player
- Safety Information Section
- Page Footer

### Testing Info (`tpl_14`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Introduction Paragraph {Unmapped}
- Why Get Tested Section {Unmapped}
- Why Get Tested Columns
- Relief Section {Unmapped}
- Patient Story {Unmapped}
- Who Should Get Tested {Unmapped}
- Find a Doctor Section {Unmapped}
- Footer

### Espanol Liver Transcription (`tpl_15`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Video Transcription {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Important Safety Information {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Navigation {Unmapped}           │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Footer Links                            │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer                                  │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Safety Information {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Global Utility Strip {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Primary Header {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Hero Banner                             │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Primary Header                          │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Primary Navigation                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T16 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                             │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ About Hep C Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Ambassador Support {Unmapped}         │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Call to Action Cards                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Area {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Callout Section {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Card Grid Section {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Carousel Section                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Cost Information {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Description Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Doctor Locator {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Doctor Locator Form                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Enrollment Call-to-Action {Unmapped}  │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T16 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Resource Documents (17 pgs)                                                                       │
│ • Healthcare Professional Resources (10 pgs)                                                        │
│ • Transcripts (5 pgs)                                                                               │
│ • Cost Information (3 pgs)                                                                          │
│ • Treatment Details (3 pgs)                                                                         │
│ • About Information (3 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Search Results Pages (3 pgs)                                                                      │
│ • Homepage (2 pgs)                                                                                  │
│ • Locator Pages (2 pgs)                                                                             │
│ • Side Effects Information (2 pgs)                                                                  │
│ • Patient Support Resources (2 pgs)                                                                 │
│ • Patient Stories (2 pgs)                                                                           │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap Pages (2 pgs)                                                                             │
│ • Product Info (1 pgs)                                                                              │
│ • Testing Info (1 pgs)                                                                              │
│ • Espanol Liver Transcription (1 pgs)                                                               │
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
| tpl_0 | Resource Documents | PDFs and overview of available resources. | https://www.mavyret.com/content/dam/admpmavyret/es-us/pdf/Spanish-Conversation-Starter-Guide.pdf, https://www.mavyret.com/content/dam/admpmavyrethcp2/pdfs/Mavyret-Co-Pay-Card.pdf, https://www.mavyret.com/content/dam/admpmavyrethcp2/pdfs/Patient%20Support%20Enrollment%20Form%20-%20Digital.pdf | 17 |
| tpl_1 | Healthcare Professional Resources | Resources tailored for healthcare professionals. | https://www.mavyret.com/hcp/nurse-ambassador, https://www.mavyret.com/hcp/access, https://www.mavyret.com/hcp/about-hep-c | 10 |
| tpl_2 | Transcripts | Transcripts related to various topics. | https://www.mavyret.com/liver-under-attack-transcript, https://www.mavyret.com/why-ask-for-mavyret-transcript, https://www.mavyret.com/why-choose-mavyret-transcript | 5 |
| tpl_3 | Cost Information | Details regarding costs and financial aspects. | https://www.mavyret.com/cost, https://www.mavyret.com/espanol/costo, https://www.mavyret.com/what-does-it-cost-transcript | 3 |
| tpl_4 | Treatment Details | Details and transcripts related to treatments. | https://www.mavyret.com/hep-c-treatment, https://www.mavyret.com/espanol/tratamiento-para-hepatitis-c, https://www.mavyret.com/what-is-treatment-like-transcript | 3 |
| tpl_5 | About Information | Contains general and disease-specific information about the topic. | https://www.mavyret.com/about-hep-c, https://www.mavyret.com/espanol/acerca, https://www.mavyret.com/about | 3 |
| tpl_6 | Search Results Pages | Pages displaying search results. | https://www.mavyret.com/search-results, https://www.mavyret.com/espanol/search-results, https://www.mavyret.com/hcp/search-results | 3 |
| tpl_7 | Homepage | Main entry point for the website. | https://www.mavyret.com/, https://www.mavyret.com/espanol | 2 |
| tpl_8 | Locator Pages | Pages dedicated to locating services or facilities. | https://www.mavyret.com/locator, https://www.mavyret.com/espanol/localizador | 2 |
| tpl_9 | Side Effects Information | Information regarding potential side effects. | https://www.mavyret.com/side-effects, https://www.mavyret.com/espanol/efectos-secundarios | 2 |
| tpl_10 | Patient Support Resources | Support resources for patients. | https://www.mavyret.com/patient-support, https://www.mavyret.com/espanol/atencion-al-paciente | 2 |
| tpl_11 | Patient Stories | Narratives and testimonials from patients. | https://www.mavyret.com/patient-stories, https://www.mavyret.com/espanol/historias-de-pacientes | 2 |
| tpl_12 | Sitemap Pages | Website navigation and structure overview. | https://www.mavyret.com/sitemap, https://www.mavyret.com/espanol/sitemap | 2 |
| tpl_13 | Product Info | Template group "product_info" from agent grouping (no merge metadata). | https://www.mavyret.com/what-is-mavyret | 1 |
| tpl_14 | Testing Info | Template group "testing_info" from agent grouping (no merge metadata). | https://www.mavyret.com/hep-c-testing | 1 |
| tpl_15 | Espanol Liver Transcription | Template group "espanol_liver_transcription" from agent grouping (no merge metadata). | https://www.mavyret.com/espanol/hep-c-y-el-higado-video-transcripcion | 1 |
