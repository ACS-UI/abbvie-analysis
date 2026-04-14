# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **34** URLs; **26** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Complete — group 21**, **Page layout group 1**, **Important Safety Information — group 2**. **12** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T11:16:24.162Z
- **Website**: https://www.ubrelvy.com/
- **Total Pages Analyzed**: 34
- **Total Templates Identified**: 26
- **Total Components Identified**: 12
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.UBRELVY.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Complete — group 21                  │    │ Page layout group 1                  │    │ Important Safety Information — grou… │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Search Results — group 3             │    │ Challenge — group 4                  │    │ Treating Migraine — group 5          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Challenge Terms — group 6            │    │ Signup Confirmation — group 7        │    │ Real Patient Stories — group 8       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • —                                  │    │ • —                                  │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Unsubscribe — group 9                │    │ Challenge Registration — group 10    │    │ Challenge Download — group 11        │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Traci Video Transcript — group 12    │    │ Early Migraine Signs — group 13      │    │ Sitemap — group 14                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • Site footer {Unmapped}             │    │ • (+6 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Savings — group 15                   │    │ Cost — group 16                      │    │ Sign Up — group 17                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Savings Terms — group 18             │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │
│ • —                                  │
└──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.UBRELVY.COM — SUB-TEMPLATES TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Laura Video Transcript — group 19    │    │ Challenge Activation — group 20      │    │ Resources — group 22                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • —                                  │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Savings Card Download — group 23     │    │ Challenge Ineligible — group 24      │    │ Why Ubrelvy — group 25               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • —                                  │    │ • —                                  │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Site Map — group 26                  │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │
│ • —                                  │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Complete — group 21 (`tpl_20`) — 2 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Page layout group 1 (`tpl_0`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}

### Important Safety Information — group 2 (`tpl_1`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Search Results — group 3 (`tpl_2`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Challenge — group 4 (`tpl_3`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}

### Treating Migraine — group 5 (`tpl_4`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- Site footer {Unmapped}

### Challenge Terms — group 6 (`tpl_5`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Signup Confirmation — group 7 (`tpl_6`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Real Patient Stories — group 8 (`tpl_7`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- Carousel / spotlight {Unmapped}
- Site footer {Unmapped}

### Unsubscribe — group 9 (`tpl_8`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Challenge Registration — group 10 (`tpl_9`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Challenge Download — group 11 (`tpl_10`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Traci Video Transcript — group 12 (`tpl_11`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Early Migraine Signs — group 13 (`tpl_12`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- Site footer {Unmapped}

### Sitemap — group 14 (`tpl_13`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Savings — group 15 (`tpl_14`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Cost — group 16 (`tpl_15`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}

### Sign Up — group 17 (`tpl_16`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Savings Terms — group 18 (`tpl_17`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Laura Video Transcript — group 19 (`tpl_18`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Challenge Activation — group 20 (`tpl_19`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Resources — group 22 (`tpl_21`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- Site footer {Unmapped}

### Savings Card Download — group 23 (`tpl_22`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Challenge Ineligible — group 24 (`tpl_23`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Why Ubrelvy — group 25 (`tpl_24`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Carousel / spotlight {Unmapped}
- Site footer {Unmapped}

### Site Map — group 26 (`tpl_25`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
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
│ main region 1 {Unmapped}                      │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ main region 2 {Unmapped}                      │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ main region 3 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ main region 4 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ main region 5 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ main region 6 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Carousel / spotlight {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T26 omitted from matrix width; see appendix.*


### Template-specific components

```
┌──────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                    │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ (after blocks step)          │ —   │ —   │ —   │ —   │ —   │ —   │ —   │
└──────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T26 omitted from matrix width; see appendix table.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Complete — group 21 (2 pgs)                                                                       │
│ • Page layout group 1 (1 pgs)                                                                       │
│ • Important Safety Information — group 2 (1 pgs)                                                    │
│ • Search Results — group 3 (1 pgs)                                                                  │
│ • Challenge — group 4 (1 pgs)                                                                       │
│ • Treating Migraine — group 5 (1 pgs)                                                               │
│ • Challenge Terms — group 6 (1 pgs)                                                                 │
│ • Signup Confirmation — group 7 (1 pgs)                                                             │
│ • Real Patient Stories — group 8 (1 pgs)                                                            │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Unsubscribe — group 9 (1 pgs)                                                                     │
│ • Challenge Registration — group 10 (1 pgs)                                                         │
│ • Challenge Download — group 11 (1 pgs)                                                             │
│ • Traci Video Transcript — group 12 (1 pgs)                                                         │
│ • Early Migraine Signs — group 13 (1 pgs)                                                           │
│ • Sitemap — group 14 (1 pgs)                                                                        │
│ • Savings — group 15 (1 pgs)                                                                        │
│ • Cost — group 16 (1 pgs)                                                                           │
│ • Sign Up — group 17 (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Savings Terms — group 18 (1 pgs)                                                                  │
│ • Laura Video Transcript — group 19 (1 pgs)                                                         │
│ • Challenge Activation — group 20 (1 pgs)                                                           │
│ • Resources — group 22 (1 pgs)                                                                      │
│ • Savings Card Download — group 23 (1 pgs)                                                          │
│ • Challenge Ineligible — group 24 (1 pgs)                                                           │
│ • Why Ubrelvy — group 25 (1 pgs)                                                                    │
│ • Site Map — group 26 (1 pgs)                                                                       │
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
| tpl_0 | Page layout group 1 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/ | 1 |
| tpl_1 | Important Safety Information — group 2 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/important-safety-information | 1 |
| tpl_2 | Search Results — group 3 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/search-results | 1 |
| tpl_3 | Challenge — group 4 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/challenge | 1 |
| tpl_4 | Treating Migraine — group 5 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/treating-migraine | 1 |
| tpl_5 | Challenge Terms — group 6 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/challenge-terms | 1 |
| tpl_6 | Signup Confirmation — group 7 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/signup-confirmation | 1 |
| tpl_7 | Real Patient Stories — group 8 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/real-patient-stories | 1 |
| tpl_8 | Unsubscribe — group 9 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/unsubscribe | 1 |
| tpl_9 | Challenge Registration — group 10 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/challenge-registration | 1 |
| tpl_10 | Challenge Download — group 11 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/challenge-download | 1 |
| tpl_11 | Traci Video Transcript — group 12 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/real-patient-stories/traci-video-transcript | 1 |
| tpl_12 | Early Migraine Signs — group 13 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/why-ubrelvy/early-migraine-signs | 1 |
| tpl_13 | Sitemap — group 14 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/sitemap | 1 |
| tpl_14 | Savings — group 15 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/savings | 1 |
| tpl_15 | Cost — group 16 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/cost | 1 |
| tpl_16 | Sign Up — group 17 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/sign-up | 1 |
| tpl_17 | Savings Terms — group 18 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/savings-terms | 1 |
| tpl_18 | Laura Video Transcript — group 19 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/real-patient-stories/laura-video-transcript | 1 |
| tpl_19 | Challenge Activation — group 20 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/challenge-activation | 1 |
| tpl_20 | Complete — group 21 | Same structural layout across 2 page(s) in the crawl. | https://www.ubrelvy.com/complete, https://www.ubrelvy.com/udemand | 2 |
| tpl_21 | Resources — group 22 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/resources | 1 |
| tpl_22 | Savings Card Download — group 23 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/savings-card-download | 1 |
| tpl_23 | Challenge Ineligible — group 24 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/challenge-ineligible | 1 |
| tpl_24 | Why Ubrelvy — group 25 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/why-ubrelvy | 1 |
| tpl_25 | Site Map — group 26 | Same structural layout across 1 page(s) in the crawl. | https://www.ubrelvy.com/site-map | 1 |
