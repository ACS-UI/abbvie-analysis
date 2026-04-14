# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **36** URLs; **5** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Condition Information Pages**, **General Information Pages**, **Cost and Savings Pages**. **16** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:14:36.127Z
- **Website**: https://www.humira.com/
- **Total Pages Analyzed**: 36
- **Total Templates Identified**: 5
- **Total Components Identified**: 16
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.HUMIRA.COM TEMPLATES                                                     │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Condition Information Pages          │    │ General Information Pages            │    │ Cost and Savings Pages               │
│ (11 pages)                           │    │ (3 pages)                            │    │ (3 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • What is HUMIRA? {Unmapped}         │    │ • Condition Selector {Unmapped}      │    │ • Page Introduction {Unmapped}       │
│ • (+3 more — see Blocks mapped per … │    │ • Promotional Section {Unmapped}     │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ User Registration Pages              │    │ Application Injection Pages          │
│ (2 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Important Safety Information {Unm… │
│ • Interactive Form                   │    │ • Footer                             │
│ • Safety Information {Unmapped}      │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Condition Information Pages (`tpl_0`) — 11 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- What is HUMIRA? {Unmapped}
- Clinical Study Graphics {Unmapped}
- Common Side Effects {Unmapped}
- Footer

### General Information Pages (`tpl_1`) — 3 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Condition Selector {Unmapped}
- Promotional Section {Unmapped}

### Cost and Savings Pages (`tpl_2`) — 3 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Page Introduction {Unmapped}
- On This Page CTAs {Unmapped}
- HUMIRA List Price {Unmapped}
- Insurance Information {Unmapped}
- Footer

### User Registration Pages (`tpl_3`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Interactive Form
- Safety Information {Unmapped}

### Application Injection Pages (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Important Safety Information {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌───────────────────────────────┬─────┬─────┬─────┬─────┬─────┐
│ Component                     │ T1  │ T2  │ T3  │ T4  │ T5  │
├───────────────────────────────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped} │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Hero Section                  │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Utility Navigation {Unmapped} │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Footer                        │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │
└───────────────────────────────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┤
│ Clinical Study Graphics {Unmapped}      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Common Side Effects {Unmapped}          │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Condition Selector {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ HUMIRA List Price {Unmapped}            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Important Safety Information {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Insurance Information {Unmapped}        │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Interactive Form                        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ On This Page CTAs {Unmapped}            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Page Introduction {Unmapped}            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Promotional Section {Unmapped}          │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Safety Information {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ What is HUMIRA? {Unmapped}              │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Condition Information Pages (11 pgs)                                                              │
│ • General Information Pages (3 pgs)                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Cost and Savings Pages (3 pgs)                                                                    │
│ • User Registration Pages (2 pgs)                                                                   │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Application Injection Pages (1 pgs)                                                               │
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
| tpl_0 | Condition Information Pages | Templates describing various medical conditions and their details. | https://www.humira.com/crohns, https://www.humira.com/psoriasis, https://www.humira.com/rheumatoid-arthritis | 11 |
| tpl_1 | General Information Pages | Templates for general site navigation and FAQs. | https://www.humira.com/, https://www.humira.com/global/sitemap, https://www.humira.com/global/frequently-asked-questions | 3 |
| tpl_2 | Cost and Savings Pages | Templates providing cost-related information and savings options. | https://www.humira.com/cost, https://www.humira.com/humira-complete/cost-and-copay, https://www.humira.com/humira-complete/cost-and-copay/transcript_savings | 3 |
| tpl_3 | User Registration Pages | Templates for user registration and account creation. | https://www.humira.com/humira-complete/sign-up, https://www.humira.com/humira-complete/register | 2 |
| tpl_4 | Application Injection Pages | Templates related to application injection detection. | https://www.humira.com/humira-complete/landing/app-injection-detect | 1 |
