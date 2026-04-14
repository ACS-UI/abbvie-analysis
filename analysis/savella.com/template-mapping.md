# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **13** URLs; **9** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Savings Card**, **Sign Up**, **Error Page**. **47** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:26:06.720Z
- **Website**: https://www.savella.com/
- **Total Pages Analyzed**: 13
- **Total Templates Identified**: 9
- **Total Components Identified**: 47
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.SAVELLA.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Savings Card                         │    │ Sign Up                              │    │ Error Page                           │
│ (3 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Main Navigation {Unmapped}         │
│ • Savings Program Section {Unmapped} │    │ • Sign Up Form                       │    │ • Hero Section                       │
│ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Why Savella                          │    │ Fibromyalgia Basics                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • CTA Tiles {Unmapped}               │    │ • Save on Savella CTA {Unmapped}     │    │ • Link List Navigation {Unmapped}    │
│ • (+3 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │    │ • (+9 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.SAVELLA.COM — SUB-TEMPLATES TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Savings Resources                    │    │ Site Map                             │    │ Leave Warning Modal                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Modal Header                       │
│ • Primary Header Navigation {Unmapp… │    │ • Site Header {Unmapped}             │    │ • Modal Body Text                    │
│ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │    │ • CTA OK Button {Unmapped}           │
│ • Savings Program Information {Unma… │    │ • Hero Section                       │    │ • CTA Cancel Button {Unmapped}       │
│ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • Modal Footer Text                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Savings Card (`tpl_0`) — 3 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Savings Program Section {Unmapped}
- Program Description {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Sign Up (`tpl_1`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sign Up Form
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Error Page (`tpl_2`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Important Safety Information {Unmapped}
- Footer Section
- Back to Top Button {Unmapped}
- Modal Dialog

### Homepage (`tpl_3`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Tiles {Unmapped}
- Signup Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Why Savella (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Save on Savella CTA {Unmapped}
- Why Savella Section {Unmapped}
- Efficacy & Results Section {Unmapped}
- Taking Savella Section {Unmapped}
- Available Dosing Section {Unmapped}
- Continuing Treatment Section {Unmapped}
- Remember Savella Section {Unmapped}
- Most Common Side Effects Section {Unmapped}

### Fibromyalgia Basics (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Link List Navigation {Unmapped}
- Save on Savella CTA {Unmapped}
- Fibromyalgia Common Section {Unmapped}
- What is Fibromyalgia {Unmapped}
- Fibromyalgia Highlight {Unmapped}
- Other Facts About Fibromyalgia {Unmapped}
- Symptoms Section {Unmapped}
- Diagnosing Fibromyalgia {Unmapped}
- Causes Section {Unmapped}
- Living with Fibromyalgia {Unmapped}

### Savings Resources (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header Navigation {Unmapped}
- Hero Section {Unmapped}
- Savings Program Information {Unmapped}
- Patient Assistance Program {Unmapped}
- Developing a Treatment Plan {Unmapped}
- Updates and Support {Unmapped}
- Common Questions {Unmapped}
- Footer Section

### Site Map (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Site Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sitemap Links {Unmapped}
- Safety Information {Unmapped}
- Site Footer

### Leave Warning Modal (`tpl_8`) — 1 pages

- Modal Header
- Modal Body Text
- CTA OK Button {Unmapped}
- CTA Cancel Button {Unmapped}
- Modal Footer Text


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Important Safety Information {Unmapped} │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer                                  │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Primary Header {Unmapped}               │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}           │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}           │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Section                          │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Hero Section {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Save on Savella CTA {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Utility Navigation {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


### Template-specific components

```
┌─────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                   │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Available Dosing Section {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Causes Section {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Common Questions {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Continuing Treatment Section {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ CTA Cancel Button {Unmapped}                │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA OK Button {Unmapped}                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Tiles {Unmapped}                        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Developing a Treatment Plan {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Diagnosing Fibromyalgia {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Efficacy & Results Section {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Fibromyalgia Common Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Fibromyalgia Highlight {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Link List Navigation {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Living with Fibromyalgia {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└─────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Savings Card (3 pgs)                                                                              │
│ • Sign Up (2 pgs)                                                                                   │
│ • Error Page (2 pgs)                                                                                │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Why Savella (1 pgs)                                                                               │
│ • Fibromyalgia Basics (1 pgs)                                                                       │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Savings Resources (1 pgs)                                                                         │
│ • Site Map (1 pgs)                                                                                  │
│ • Leave Warning Modal (1 pgs)                                                                       │
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
| tpl_0 | Savings Card | Pages related to the savings card, including activation and terms. | https://www.savella.com/savella-savingscard, https://www.savella.com/savella-savingscard/terms, https://www.savella.com/savella-savingscard/activate | 3 |
| tpl_1 | Sign Up | Pages for user sign-up and confirmation. | https://www.savella.com/sign-up, https://www.savella.com/sign-up-confirmation | 2 |
| tpl_2 | Error Page | A template for displaying error messages to users. | https://www.savella.com/search-results, https://www.savella.com/301 | 2 |
| tpl_3 | Homepage | The main landing page of the website. | https://www.savella.com/ | 1 |
| tpl_4 | Why Savella | Information about the benefits of Savella. | https://www.savella.com/why-savella | 1 |
| tpl_5 | Fibromyalgia Basics | An informational page about fibromyalgia basics. | https://www.savella.com/fibromyalgia-basics | 1 |
| tpl_6 | Savings Resources | Resources and information about savings. | https://www.savella.com/savings-and-resources | 1 |
| tpl_7 | Site Map | A sitemap page listing all sections of the website. | https://www.savella.com/sitemap | 1 |
| tpl_8 | Leave Warning Modal | A modal warning users before they leave the site. | https://www.savella.com/site-modals/warn-on-leave-extra-help | 1 |
