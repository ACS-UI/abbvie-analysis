# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **40** URLs; **14** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Page layout group 1**, **Log In — group 2**, **Botox Account Sign Up — group 6**. **13** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T12:28:53.590Z
- **Website**: https://www.botox.com/
- **Total Pages Analyzed**: 40
- **Total Templates Identified**: 14
- **Total Components Identified**: 13
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BOTOX.COM TEMPLATES                                                      │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 1                  │    │ Log In — group 2                     │    │ Botox Account Sign Up — group 6      │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • carousel {Unmapped}                │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • (+8 more — see Blocks mapped per … │    │ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap — group 3                    │    │ Completeterms — group 4              │    │ Mobile Terms Conditions — group 5    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Botox Complete — group 7             │    │ Confirmation — group 8               │    │ Reset Password — group 9             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • (+4 more — see Blocks mapped per … │    │ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Botox Complete Sign Up — group 10    │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │
│ • Site footer {Unmapped}             │
└──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BOTOX.COM — SUB-TEMPLATES TEMPLATES                                      │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Frequently Asked Questions — group … │    │ Cost And Coverage — group 12         │    │ Confirmation — group 13              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • —                                  │    │ • Site footer {Unmapped}             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Account — group 14                   │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │
│ • Site footer {Unmapped}             │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Page layout group 1 (`tpl_0`) — 2 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- carousel {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- main region 7 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Log In — group 2 (`tpl_1`) — 2 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Botox Account Sign Up — group 6 (`tpl_5`) — 2 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Sitemap — group 3 (`tpl_2`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Completeterms — group 4 (`tpl_3`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Mobile Terms Conditions — group 5 (`tpl_4`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Botox Complete — group 7 (`tpl_6`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Site footer {Unmapped}

### Confirmation — group 8 (`tpl_7`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Reset Password — group 9 (`tpl_8`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Botox Complete Sign Up — group 10 (`tpl_9`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Frequently Asked Questions — group 11 (`tpl_10`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Cost And Coverage — group 12 (`tpl_11`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Confirmation — group 13 (`tpl_12`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Account — group 14 (`tpl_13`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌───────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                     │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Global utility bar {Unmapped}                 │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 0 {Unmapped}                      │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary site header and navigation {Unmapped} │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Site footer {Unmapped}                        │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 1 {Unmapped}                      │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │
│ main region 2 {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ main region 3 {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ main region 4 {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└───────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T14 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                      │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ carousel {Unmapped}            │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Form / subscription {Unmapped} │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 5 {Unmapped}       │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 6 {Unmapped}       │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 7 {Unmapped}       │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T14 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Page layout group 1 (2 pgs)                                                                       │
│ • Log In — group 2 (2 pgs)                                                                          │
│ • Botox Account Sign Up — group 6 (2 pgs)                                                           │
│ • Sitemap — group 3 (1 pgs)                                                                         │
│ • Completeterms — group 4 (1 pgs)                                                                   │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Mobile Terms Conditions — group 5 (1 pgs)                                                         │
│ • Botox Complete — group 7 (1 pgs)                                                                  │
│ • Confirmation — group 8 (1 pgs)                                                                    │
│ • Reset Password — group 9 (1 pgs)                                                                  │
│ • Botox Complete Sign Up — group 10 (1 pgs)                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Frequently Asked Questions — group 11 (1 pgs)                                                     │
│ • Cost And Coverage — group 12 (1 pgs)                                                              │
│ • Confirmation — group 13 (1 pgs)                                                                   │
│ • Account — group 14 (1 pgs)                                                                        │
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
| tpl_0 | Page layout group 1 | Same structural layout across 2 page(s) in the crawl. | https://www.botox.com/, https://www.botox.com/main | 2 |
| tpl_1 | Log In — group 2 | Same structural layout across 2 page(s) in the crawl. | https://www.botox.com/log-in, https://www.botox.com/forgot-password | 2 |
| tpl_2 | Sitemap — group 3 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/sitemap | 1 |
| tpl_3 | Completeterms — group 4 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/completeterms | 1 |
| tpl_4 | Mobile Terms Conditions — group 5 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/mobile-terms-conditions | 1 |
| tpl_5 | Botox Account Sign Up — group 6 | Same structural layout across 2 page(s) in the crawl. | https://www.botox.com/botox-account-sign-up, https://www.botox.com/reset-expired-password | 2 |
| tpl_6 | Botox Complete — group 7 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/resources/botox-complete | 1 |
| tpl_7 | Confirmation — group 8 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/botox-account-sign-up/confirmation | 1 |
| tpl_8 | Reset Password — group 9 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/reset-password | 1 |
| tpl_9 | Botox Complete Sign Up — group 10 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/botox-complete-sign-up | 1 |
| tpl_10 | Frequently Asked Questions — group 11 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/resources/frequently-asked-questions | 1 |
| tpl_11 | Cost And Coverage — group 12 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/cost-and-coverage | 1 |
| tpl_12 | Confirmation — group 13 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/botox-complete-sign-up/confirmation | 1 |
| tpl_13 | Account — group 14 | Same structural layout across 1 page(s) in the crawl. | https://www.botox.com/account | 1 |
