# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **17** URLs; **12** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Patient Stories**, **Discussion Guide**, **Resources Download**. **61** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:42:26.642Z
- **Website**: https://www.elahere.com/
- **Total Pages Analyzed**: 17
- **Total Templates Identified**: 12
- **Total Components Identified**: 61
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ELAHERE.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Stories                      │    │ Discussion Guide                     │    │ Resources Download                   │
│ (4 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Global Header                      │    │ • Global Header                      │
│ • Skip to Main Content Link {Unmapp… │    │ • Skip to Main Content {Unmapped}    │    │ • Skip Link {Unmapped}               │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Jennifer's Story Section {Unmappe… │    │ • Introduction Content {Unmapped}    │    │ • Resources Cards                    │
│ • (+5 more — see Blocks mapped per … │    │ • (+8 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Results Summary                      │    │ Email Signup                         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Header                      │    │ • Global Header                      │
│ • Skip to Main Content {Unmapped}    │    │ • Skip to Main Content Link {Unmapp… │    │ • Email Signup Main {Unmapped}       │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Email Signup Heading {Unmapped}    │
│ • What is ELAHERE Section {Unmapped} │    │ • Anchor Navigation {Unmapped}       │    │ • Email Signup Form {Unmapped}       │
│ • (+5 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Eye Care Information                 │    │ Eligibility Check                    │    │ Safety Information                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Global Header                      │    │ • Primary Header                     │
│ • Skip to Main Content {Unmapped}    │    │ • Skip to Main Content Link {Unmapp… │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Side Effects Introduction {Unmapp… │
│ • Anchor Navigation {Unmapped}       │    │ • Eligibility Introduction {Unmappe… │    │ • Side Effects Cards                 │
│ • (+9 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ELAHERE.COM — SUB-TEMPLATES TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Starting Treatment                   │    │ Support Services                     │    │ Advocacy Support                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Header                        │    │ • Global Header                      │    │ • Global Header                      │
│ • Hero Section                       │    │ • Skip Link {Unmapped}               │    │ • Accessibility Link {Unmapped}      │
│ • Anchor Navigation {Unmapped}       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Before Starting Treatment {Unmapp… │    │ • Anchor Navigation {Unmapped}       │    │ • Advocacy Groups Cards              │
│ • (+5 more — see Blocks mapped per … │    │ • (+8 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Patient Stories (`tpl_0`) — 4 pages

- Global Header {Unmapped}
- Skip to Main Content Link {Unmapped}
- Hero Section {Unmapped}
- Jennifer's Story Section {Unmapped}
- Heidi's Story Section {Unmapped}
- Cindy's Story Section {Unmapped}
- Callout Section {Unmapped}
- Footer {Unmapped}
- Exit Modal {Unmapped}

### Discussion Guide (`tpl_1`) — 2 pages

- Global Header
- Skip to Main Content {Unmapped}
- Hero Section
- Introduction Content {Unmapped}
- Image with Caption {Unmapped}
- Discussion Guide CTA {Unmapped}
- Advocacy Groups Section {Unmapped}
- Starting ELAHERE Section {Unmapped}
- Newsletter Signup Section {Unmapped}
- Important Safety Information {Unmapped}
- Global Footer
- Exit Modal

### Resources Download (`tpl_2`) — 2 pages

- Global Header
- Skip Link {Unmapped}
- Hero Section
- Resources Cards
- Callout Section {Unmapped}
- Footer
- Exit Modal

### Homepage (`tpl_3`) — 1 pages

- Global Header
- Skip to Main Content {Unmapped}
- Hero Section
- What is ELAHERE Section {Unmapped}
- Stories Banner
- Callout CTAs {Unmapped}
- ISI Section {Unmapped}
- Global Footer
- Exit Modal

### Results Summary (`tpl_4`) — 1 pages

- Global Header
- Skip to Main Content Link {Unmapped}
- Hero Section
- Anchor Navigation {Unmapped}
- Progression-Free Survival Section {Unmapped}
- Overall Survival Section {Unmapped}
- Response Rates Section {Unmapped}
- Callout Cards
- Important Safety Information {Unmapped}
- Global Footer
- Exit Modal

### Email Signup (`tpl_5`) — 1 pages

- Global Header
- Email Signup Main {Unmapped}
- Email Signup Heading {Unmapped}
- Email Signup Form {Unmapped}
- Important Safety Information {Unmapped}
- Global Footer
- Exit Modal

### Eye Care Information (`tpl_6`) — 1 pages

- Global Header {Unmapped}
- Skip to Main Content {Unmapped}
- Hero Section
- Anchor Navigation {Unmapped}
- Side Effects Information {Unmapped}
- Caring for Your Eyes {Unmapped}
- Eye Drops Information {Unmapped}
- Managing Blurred Vision {Unmapped}
- Find an Eye Doctor {Unmapped}
- Callout Section {Unmapped}
- Footer
- Video Modal
- Exit Modal

### Eligibility Check (`tpl_7`) — 1 pages

- Global Header
- Skip to Main Content Link {Unmapped}
- Hero Section
- Eligibility Introduction {Unmapped}
- Eligibility Criteria Cards
- Eligibility Note {Unmapped}
- Discussion Guide Banner {Unmapped}
- Callout Cards
- Footer
- Exit Modal

### Safety Information (`tpl_8`) — 1 pages

- Primary Header
- Hero Section
- Side Effects Introduction {Unmapped}
- Side Effects Cards
- Common Side Effects List
- Side Effects Statistics {Unmapped}
- Eye Care Resources
- Additional Resources
- Important Safety Information
- Primary Footer
- Exit Modal

### Starting Treatment (`tpl_9`) — 1 pages

- Site Header
- Hero Section
- Anchor Navigation {Unmapped}
- Before Starting Treatment {Unmapped}
- Treatment Preparation {Unmapped}
- Medical Conditions {Unmapped}
- Treatment Schedule {Unmapped}
- Resources Banner {Unmapped}
- Page Footer

### Support Services (`tpl_10`) — 1 pages

- Global Header
- Skip Link {Unmapped}
- Hero Section
- Anchor Navigation {Unmapped}
- Support Services {Unmapped}
- Financial Assistance {Unmapped}
- FAQs Section
- Contact Us {Unmapped}
- Resources Section
- Footer
- Exit Modal
- Co-pay Terms Modal

### Advocacy Support (`tpl_11`) — 1 pages

- Global Header
- Accessibility Link {Unmapped}
- Hero Section
- Advocacy Groups Cards
- Callout Section {Unmapped}
- Global Footer
- Exit Modal


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Exit Modal                              │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Hero Section                            │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Global Header                           │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Global Footer                           │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Anchor Navigation {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Callout Section {Unmapped}              │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer                                  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Important Safety Information {Unmapped} │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Skip to Main Content {Unmapped}         │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Skip to Main Content Link {Unmapped}    │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Callout Cards                           │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Global Header {Unmapped}                │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Skip Link {Unmapped}                    │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


### Template-specific components

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accessibility Link {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Additional Resources                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Advocacy Groups Cards                │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Advocacy Groups Section {Unmapped}   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Before Starting Treatment {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Callout CTAs {Unmapped}              │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Caring for Your Eyes {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Cindy's Story Section {Unmapped}     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Co-pay Terms Modal                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Common Side Effects List             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Contact Us {Unmapped}                │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Discussion Guide Banner {Unmapped}   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Discussion Guide CTA {Unmapped}      │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Eligibility Criteria Cards           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Patient Stories (4 pgs)                                                                           │
│ • Discussion Guide (2 pgs)                                                                          │
│ • Resources Download (2 pgs)                                                                        │
│ • Homepage (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Results Summary (1 pgs)                                                                           │
│ • Email Signup (1 pgs)                                                                              │
│ • Eye Care Information (1 pgs)                                                                      │
│ • Eligibility Check (1 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Safety Information (1 pgs)                                                                        │
│ • Starting Treatment (1 pgs)                                                                        │
│ • Support Services (1 pgs)                                                                          │
│ • Advocacy Support (1 pgs)                                                                          │
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
| tpl_0 | Patient Stories | Template for showcasing patient stories and transcripts. | https://www.elahere.com/resources/elahere-stories, https://www.elahere.com/resources/elahere-stories/transcripts/jennifer, https://www.elahere.com/resources/elahere-stories/transcripts/cindy | 4 |
| tpl_1 | Discussion Guide | Template for creating and presenting discussion guides. | https://www.elahere.com/resources/talking-to-your-doctor, https://www.elahere.com/resources/discussion-guide-builder | 2 |
| tpl_2 | Resources Download | Template for downloading resources and materials. | https://www.elahere.com/resources/helpful-downloads, https://www.elahere.com/resources/helpful-downloads.html | 2 |
| tpl_3 | Homepage | Main landing page template. | https://www.elahere.com/ | 1 |
| tpl_4 | Results Summary | Template for summarizing and presenting results. | https://www.elahere.com/results | 1 |
| tpl_5 | Email Signup | Template for user email subscription forms. | https://www.elahere.com/sign-up/ | 1 |
| tpl_6 | Eye Care Information | Template for providing information on eye care. | https://www.elahere.com/eye-care | 1 |
| tpl_7 | Eligibility Check | Template for checking user eligibility for services. | https://www.elahere.com/about/is-elahere-right-for-me | 1 |
| tpl_8 | Safety Information | Template for providing safety-related information. | https://www.elahere.com/safety | 1 |
| tpl_9 | Starting Treatment | Template for guidance on beginning treatment. | https://www.elahere.com/starting-elahere | 1 |
| tpl_10 | Support Services | Template for detailing available support services. | https://www.elahere.com/resources/elahere-support-services | 1 |
| tpl_11 | Advocacy Support | Page template for advocacy and support resources. | https://www.elahere.com/resources/advocacy-groups | 1 |
