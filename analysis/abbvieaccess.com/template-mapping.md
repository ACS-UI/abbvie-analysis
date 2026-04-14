# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **111** URLs; **15** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Agent Unassigned**, **Brand Page**, **Representative Request**. **43** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:57:34.602Z
- **Website**: https://www.abbvieaccess.com/
- **Total Pages Analyzed**: 111
- **Total Templates Identified**: 15
- **Total Components Identified**: 43
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ABBVIEACCESS.COM TEMPLATES                                               │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Agent Unassigned                     │    │ Brand Page                           │    │ Representative Request               │
│ (57 pages)                           │    │ (23 pages)                           │    │ (7 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Main Navigation {Unmapped}         │
│ • Call to Action Section {Unmapped}  │    │ • Call-to-Action Buttons {Unmapped}  │    │ • Hero Section                       │
│ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Category Homepage                    │    │ Homepage                             │    │ HCP Registration                     │
│ (6 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • CTA Grid {Unmapped}                │    │ • Call-to-Action Buttons {Unmapped}  │    │ • CTA Grid {Unmapped}                │
│ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Preference Center                    │    │ Search Results                       │    │ Resource Request                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation                 │    │ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Search Box                         │    │ • Hero Section                       │
│ • Call-to-Action Section             │    │ • Hero Section                       │    │ • CTA Links {Unmapped}               │
│ • (+6 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Enrollment Forms                     │    │ Formulary Coverage                   │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Header                      │
│ • Primary Navigation                 │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Call-to-Action Section {Unmapped}  │
│ • CTA Links                          │    │ • Product Cards {Unmapped}           │
│ • (+4 more — see Blocks mapped per … │    │ • Footer                             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ABBVIEACCESS.COM — SUB-TEMPLATES TEMPLATES                               │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Resources                    │    │ Reimbursement Program                │    │ Patient Assistance                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Call-to-Action Section {Unmapped}  │    │ • CTA Links {Unmapped}               │    │ • CTA Buttons {Unmapped}             │
│ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Prior Authorization                  │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │
│ • CTA Buttons {Unmapped}             │
│ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Agent Unassigned (`tpl_0`) — 57 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Call to Action Section {Unmapped}
- Card Grid: Support & Education {Unmapped}
- Footer Links {Unmapped}
- Back to Top Button {Unmapped}
- Exit Site Modal {Unmapped}

### Brand Page (`tpl_1`) — 23 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Buttons {Unmapped}
- Secondary Links {Unmapped}
- Card Grid
- Footer Section
- Back to Top Button {Unmapped}
- Exit Site Modal

### Representative Request (`tpl_2`) — 7 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- CTA Section {Unmapped}
- Product Cards
- Footer

### Category Homepage (`tpl_3`) — 6 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- CTA Grid {Unmapped}
- Content Grid {Unmapped}
- Footer Section {Unmapped}
- Back to Top Button {Unmapped}
- Subscribe Modal {Unmapped}

### Homepage (`tpl_4`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Call-to-Action Buttons {Unmapped}
- Content Grid {Unmapped}
- Footer Links {Unmapped}
- Footer Legal Text {Unmapped}
- Back to Top Button {Unmapped}
- Subscribe Modal {Unmapped}

### HCP Registration (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Grid {Unmapped}
- Form Section
- Footer
- Back to Top Button {Unmapped}
- Exit Site Modal

### Preference Center (`tpl_6`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Call-to-Action Section
- Preferences Introduction {Unmapped}
- Preferences CTAs
- Footer Section
- Back to Top Button {Unmapped}
- Exit Site Modal
- Subscribe for News Modal

### Search Results (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Search Box
- Hero Section
- Search Results {Unmapped}
- Footer Navigation
- Back to Top Button {Unmapped}
- Exit Modal
- Subscribe Modal

### Resource Request (`tpl_8`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Links {Unmapped}
- Secondary CTA Links {Unmapped}
- Product Cards
- Footer

### Enrollment Forms (`tpl_9`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- CTA Links
- Content Cards
- Footer Links
- Back to Top Button {Unmapped}
- Exit Modal

### Formulary Coverage (`tpl_10`) — 1 pages

- Global Header
- Hero Section
- Call-to-Action Section {Unmapped}
- Product Cards {Unmapped}
- Footer

### Patient Resources (`tpl_11`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Section {Unmapped}
- Product Cards
- Contact Information {Unmapped}
- Footer Section

### Reimbursement Program (`tpl_12`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- CTA Links {Unmapped}
- Product Cards {Unmapped}
- Contact Information {Unmapped}
- Footer Links {Unmapped}

### Patient Assistance (`tpl_13`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Buttons {Unmapped}
- Introductory Text {Unmapped}
- Interactive Image {Unmapped}
- Footer Links
- Footer Legal Text
- Back to Top Button {Unmapped}
- Exit Site Modal
- Subscribe Modal

### Prior Authorization (`tpl_14`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Buttons {Unmapped}
- Video Modal
- Image and Text Section {Unmapped}
- Product Cards


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                         │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}        │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Back to Top Button {Unmapped}        │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Utility Navigation {Unmapped}        │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Exit Site Modal                      │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Footer                               │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Hero Section {Unmapped}              │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Product Cards                        │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links {Unmapped}              │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Section                       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Global Utility Navigation {Unmapped} │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Global Utility Strip {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call-to-Action Buttons {Unmapped}    │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T15 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                 │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Call to Action Section {Unmapped}         │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Card Grid                                 │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Card Grid: Support & Education {Unmapped} │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Cards                             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Links                                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Section {Unmapped}                    │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Exit Site Modal {Unmapped}                │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Legal Text                         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Legal Text {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Navigation                         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Section {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Form Section                              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Global Header                             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T15 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Agent Unassigned (57 pgs)                                                                         │
│ • Brand Page (23 pgs)                                                                               │
│ • Representative Request (7 pgs)                                                                    │
│ • Category Homepage (6 pgs)                                                                         │
│ • Homepage (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • HCP Registration (1 pgs)                                                                          │
│ • Preference Center (1 pgs)                                                                         │
│ • Search Results (1 pgs)                                                                            │
│ • Resource Request (1 pgs)                                                                          │
│ • Enrollment Forms (1 pgs)                                                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Formulary Coverage (1 pgs)                                                                        │
│ • Patient Resources (1 pgs)                                                                         │
│ • Reimbursement Program (1 pgs)                                                                     │
│ • Patient Assistance (1 pgs)                                                                        │
│ • Prior Authorization (1 pgs)                                                                       │
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
| tpl_0 | Agent Unassigned | Pages that are not assigned to specific categories. | https://www.abbvieaccess.com/brand/lupron-men, https://www.abbvieaccess.com/brand/liletta, https://www.abbvieaccess.com/brand/viibryd | 57 |
| tpl_1 | Brand Page | Pages dedicated to specific brands. | https://www.abbvieaccess.com/brand/combigan, https://www.abbvieaccess.com/brand/creon, https://www.abbvieaccess.com/brand/lastacaft | 23 |
| tpl_2 | Representative Request | Pages for requesting representatives. | https://www.abbvieaccess.com/request-a-rep, https://www.abbvieaccess.com/request-a-rep/avycaz, https://www.abbvieaccess.com/exit-site-mynavcare | 7 |
| tpl_3 | Category Homepage | Main pages for content categories. | https://www.abbvieaccess.com/womens-health, https://www.abbvieaccess.com/anti-infectives, https://www.abbvieaccess.com/central-nervous-system | 6 |
| tpl_4 | Homepage | The main page of the website. | https://www.abbvieaccess.com/ | 1 |
| tpl_5 | HCP Registration | Healthcare professional registration pages. | https://www.abbvieaccess.com/hcp-registration/abbvieaccess-registration | 1 |
| tpl_6 | Preference Center | Pages for managing user preferences. | https://www.abbvieaccess.com/preference-center | 1 |
| tpl_7 | Search Results | Pages displaying search results. | https://www.abbvieaccess.com/search-results | 1 |
| tpl_8 | Resource Request | Pages for requesting resources. | https://www.abbvieaccess.com/resource-request | 1 |
| tpl_9 | Enrollment Forms | Pages for user enrollment forms. | https://www.abbvieaccess.com/enrollment-forms | 1 |
| tpl_10 | Formulary Coverage | Pages detailing formulary coverage information. | https://www.abbvieaccess.com/formulary-coverage | 1 |
| tpl_11 | Patient Resources | Resources available for patients. | https://www.abbvieaccess.com/patient-resources | 1 |
| tpl_12 | Reimbursement Program | Information on reimbursement programs. | https://www.abbvieaccess.com/reimbursement-program | 1 |
| tpl_13 | Patient Assistance | Pages offering assistance to patients. | https://www.abbvieaccess.com/patient-assistance | 1 |
| tpl_14 | Prior Authorization | Pages for prior authorization processes. | https://www.abbvieaccess.com/prior-authorization | 1 |
