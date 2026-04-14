# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **61** URLs; **46** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Understanding Eczema Overview**, **Homepage and Personalization**, **Specialist Locator Tool**. **114** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:32:29.265Z
- **Website**: https://www.eczemaheadquarters.com/
- **Total Pages Analyzed**: 61
- **Total Templates Identified**: 46
- **Total Components Identified**: 114
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ECZEMAHEADQUARTERS.COM TEMPLATES                                         │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Understanding Eczema Overview        │    │ Homepage and Personalization         │    │ Specialist Locator Tool              │
│ (6 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Top Utility Bar {Unmapped}         │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │    │ • Main Navigation {Unmapped}         │
│ • Footer                             │    │ • Mega Navigation {Unmapped}         │    │ • Hero Banner                        │
│ • Back to Top Button {Unmapped}      │    │ • Footer Section                     │    │ • Specialist Locator {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sign-Up Page                         │    │ Search Results                       │    │ Eczema Comorbidities                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │
│ • —                                  │    │ • Search Bar                         │    │ • Hero Section                       │
│ • —                                  │    │ • Hero Section                       │    │ • Introduction Text {Unmapped}       │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Types of Eczema                      │    │ Causes of Eczema                     │    │ Severity and Impact                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Site Header                        │    │ • Primary Header                     │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Eczema Details {Unmapped}          │    │ • Intro Content {Unmapped}           │    │ • Main Content Columns {Unmapped}    │
│ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage Experience                  │    │ Footer Touts - Personalized          │    │ Inline Touts                         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Hero Section                       │    │ • Footer Tout                        │    │ • Personalization Introduction {Unm… │
│ • Quick Poll {Unmapped}              │    │ • —                                  │    │ • Inline Tout: What is Eczema? {Unm… │
│ • Hero Callout                       │    │ • —                                  │    │ • Inline Tout: Types of Eczema {Unm… │
│ • —                                  │    │ • —                                  │    │ • Inline Tout: Symptoms and Picture… │
│ • —                                  │    │ • —                                  │    │ • (+13 more — see Blocks mapped per… │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Default Inline Touts                 │    │ Default Footer Touts                 │    │ What Is Eczema                       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Default Inline Tout Title 1 {Unma… │    │ • Footer Tout 1                      │    │ • Utility Navigation {Unmapped}      │
│ • Default Inline Tout Title 2 {Unma… │    │ • Footer Tout 2                      │    │ • Site Header                        │
│ • —                                  │    │ • Footer Tout 3                      │    │ • Site Footer                        │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Eczema Symptoms and Pictures         │    │ Eczema Experience Tool               │    │ Scratch Cycle Video Transcript       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Mega Navigation {Unmapped}         │
│ • Symptoms Report {Unmapped}         │    │ • Introduction Text {Unmapped}       │    │ • Hero Section                       │
│ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Doctor Partnership Guide             │    │ Eczema Itch Insights                 │    │ Trigger Words Activity               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation                 │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation                 │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Social Share                       │    │ • Social Share                       │    │ • Video Player                       │
│ • (+6 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Dermatologist Reacts Activity        │    │ Home Remedies                        │    │ Living With Eczema Stories           │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation                 │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Header and Branding {Unma… │    │ • Primary Navigation                 │    │ • Primary Header                     │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Mega Navigation {Unmapped}         │
│ • Social Share Section {Unmapped}    │    │ • Social Share                       │    │ • Hero Section                       │
│ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap                              │    │ Eczema Specialist Locator            │    │ Doctor Discussion Guide              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Sitemap Title {Unmapped}           │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Sitemap Links Section {Unmapped}   │    │ • Promo Drawer {Unmapped}            │    │ • Hero Section                       │
│ • Global Footer {Unmapped}           │    │ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Thank You Page                       │    │ Invisible Impact Article             │    │ Eczema Emotional Health              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │    │ • Utility Navigation                 │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │    │ • Primary Navigation                 │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Main Message {Unmapped}            │    │ • Social Share {Unmapped}            │    │ • Introduction Text {Unmapped}       │
│ • (+2 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Stay Tuned Page                      │    │ Personalized Homepage                │    │ Eczema Diet Insights                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Content Columns {Unmapped}         │    │ • Information Tree {Unmapped}        │    │ • Social Sharing Buttons {Unmapped}  │
│ • (+2 more — see Blocks mapped per … │    │ • Footer                             │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Stress and Eczema                    │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │
│ • Main Content Columns {Unmapped}    │
│ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ECZEMAHEADQUARTERS.COM — SUB-TEMPLATES TEMPLATES                         │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ VOC Survey Page                      │    │ Eczema Treatment Options             │    │ Eczema Routine Guide                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation                 │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation                 │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Feedback Form                      │    │ • Introduction Content {Unmapped}    │    │ • Promo Drawer {Unmapped}            │
│ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Winter Eczema Insights               │    │ Treatment Video Transcript           │    │ Eczema Treatment Overview            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Site Header {Unmapped}             │    │ • Site Header                        │
│ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │    │ • Mega Navigation {Unmapped}         │
│ • Social Share {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Supporting Eczema Teens              │    │ Connect With Us                      │    │ Eczema Stories Transcript            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • Site Header {Unmapped}             │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │
│ • Hero Banner {Unmapped}             │    │ • Hero Section                       │    │ • Mega Navigation {Unmapped}         │
│ • Social Sharing {Unmapped}          │    │ • Promo Drawer {Unmapped}            │    │ • Hero Section                       │
│ • (+4 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Support and Resources                │    │ Learnings from the Lab               │    │ Sign-Up Confirmation                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │    │ • Global Header {Unmapped}           │
│ • Main Navigation {Unmapped}         │    │ • Primary Navigation                 │    │ • Hero Section {Unmapped}            │
│ • Hero Carousel                      │    │ • Hero Section                       │    │ • Confirmation Message {Unmapped}    │
│ • Footer Section                     │    │ • Content Introduction {Unmapped}    │    │ • Quick Poll 1 {Unmapped}            │
│ • Back to Top {Unmapped}             │    │ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Understanding Eczema Overview (`tpl_20`) — 6 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Homepage and Personalization (`tpl_0`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Mega Navigation {Unmapped}
- Footer Section

### Specialist Locator Tool (`tpl_42`) — 2 pages

- Top Utility Bar {Unmapped}
- Main Navigation {Unmapped}
- Hero Banner
- Specialist Locator {Unmapped}
- Introduction Text {Unmapped}
- Footer Links

### Sign-Up Page (`tpl_1`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}

### Search Results (`tpl_2`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Search Bar
- Hero Section
- Footer Links
- Back to Top Button {Unmapped}
- Modal Windows

### Eczema Comorbidities (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Atopic March Highlight {Unmapped}
- Mental Health Info {Unmapped}
- Recommended Topics {Unmapped}

### Types of Eczema (`tpl_4`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Eczema Details {Unmapped}
- Email Signup {Unmapped}
- Quick Poll {Unmapped}
- Comparison Section {Unmapped}
- Recommended Topics {Unmapped}

### Causes of Eczema (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Site Header
- Hero Section
- Intro Content {Unmapped}
- Main Visual {Unmapped}
- Root Cause Details {Unmapped}
- Inflammation Insights {Unmapped}
- User Poll {Unmapped}
- Page Footer

### Severity and Impact (`tpl_6`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Section
- Main Content Columns {Unmapped}
- Accordion Section
- Next Page CTA {Unmapped}
- Recommended Topics {Unmapped}

### Homepage Experience (`tpl_7`) — 1 pages

- Hero Section
- Quick Poll {Unmapped}
- Hero Callout

### Footer Touts - Personalized (`tpl_8`) — 1 pages

- Footer Tout

### Inline Touts (`tpl_9`) — 1 pages

- Personalization Introduction {Unmapped}
- Inline Tout: What is Eczema? {Unmapped}
- Inline Tout: Types of Eczema {Unmapped}
- Inline Tout: Symptoms and Pictures {Unmapped}
- Inline Tout: Causes of Eczema {Unmapped}
- Inline Tout: Understanding the Itch {Unmapped}
- Inline Tout: Severity and Impact {Unmapped}
- Inline Tout: Sharing Your Experience {Unmapped}
- Inline Tout: Related Conditions {Unmapped}
- Inline Tout: Treatments {Unmapped}
- Inline Tout: Biologics and Small Molecules {Unmapped}
- Inline Tout: Doctor Discussion Guide {Unmapped}
- Inline Tout: Eczema Specialists {Unmapped}
- Inline Tout: Find a Specialist {Unmapped}
- Inline Tout: Eczema Routines {Unmapped}
- Inline Tout: Stress and Eczema {Unmapped}
- Inline Tout: Emotional Well-Being {Unmapped}

### Default Inline Touts (`tpl_10`) — 1 pages

- Default Inline Tout Title 1 {Unmapped}
- Default Inline Tout Title 2 {Unmapped}

### Default Footer Touts (`tpl_11`) — 1 pages

- Footer Tout 1
- Footer Tout 2
- Footer Tout 3

### What Is Eczema (`tpl_12`) — 1 pages

- Utility Navigation {Unmapped}
- Site Header
- Site Footer

### Eczema Symptoms and Pictures (`tpl_13`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Symptoms Report {Unmapped}
- Eczema Image Library {Unmapped}
- Hands Carousel
- Feet Carousel
- Legs Carousel
- Arms Carousel

### Eczema Experience Tool (`tpl_14`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Experience Tool Section {Unmapped}
- Social Share {Unmapped}
- Download Tool CTA {Unmapped}
- Footer Links

### Scratch Cycle Video Transcript (`tpl_15`) — 1 pages

- Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Mega Navigation {Unmapped}
- Hero Section
- Social Share {Unmapped}
- Video Player
- Transcript Text {Unmapped}
- Next Page CTA {Unmapped}
- Recommended Topics {Unmapped}
- Footer

### Doctor Partnership Guide (`tpl_16`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Social Share
- Content Introduction
- Image and Text Component
- First Content Section
- Second Content Section
- Third Content Section
- Recommended Topics

### Eczema Itch Insights (`tpl_17`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Social Share
- Video Player
- Main Content Columns
- Quick Poll
- Background Video Section
- Recommended Topics
- Footer Call-to-Action

### Trigger Words Activity (`tpl_18`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Video Player
- Transcript Content {Unmapped}
- Recommended Topics {Unmapped}
- Footer

### Dermatologist Reacts Activity (`tpl_19`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header and Branding {Unmapped}
- Hero Section
- Social Share Section {Unmapped}
- Video Player
- Transcript Content {Unmapped}
- Recommended Topics {Unmapped}
- Footer

### Home Remedies (`tpl_21`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Social Share
- Content Introduction
- Sunflower Oil Section
- Turmeric Section
- Alternative Methods Section
- Recommended Topics

### Living With Eczema Stories (`tpl_22`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Mega Navigation {Unmapped}
- Hero Section
- Introduction Paragraph {Unmapped}
- Trigger Words Section
- Fill in the Blank Section
- Dermatologist Reacts Section
- Share Your Story CTA {Unmapped}
- Next Page CTA {Unmapped}

### Sitemap (`tpl_23`) — 1 pages

- Global Header {Unmapped}
- Primary Navigation {Unmapped}
- Sitemap Title {Unmapped}
- Sitemap Links Section {Unmapped}
- Global Footer {Unmapped}

### Eczema Specialist Locator (`tpl_24`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Promo Drawer {Unmapped}
- Specialist Introduction {Unmapped}
- Quick Poll {Unmapped}
- Next Page CTA {Unmapped}
- Recommended Topics {Unmapped}

### Doctor Discussion Guide (`tpl_25`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Social Share {Unmapped}
- Embedded Form
- Call-to-Action Section {Unmapped}
- Footer Links {Unmapped}

### Thank You Page (`tpl_26`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Message {Unmapped}
- Recommended Topics {Unmapped}
- Footer

### Invisible Impact Article (`tpl_27`) — 1 pages

- Utility Navigation
- Primary Header
- Hero Section
- Social Share {Unmapped}
- Main Content Columns
- Quote Section A
- Finding A Section
- Footer Section

### Eczema Emotional Health (`tpl_28`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Introduction Text {Unmapped}
- Main Content Columns
- Quick Poll
- Call to Action Section {Unmapped}
- Recommended Topics

### Stay Tuned Page (`tpl_29`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Columns {Unmapped}
- Recommended Topics {Unmapped}
- Footer {Unmapped}

### Personalized Homepage (`tpl_30`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Information Tree {Unmapped}
- Footer

### Eczema Diet Insights (`tpl_31`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Social Sharing Buttons {Unmapped}
- Diet Advice Call-to-Action {Unmapped}
- Recommended Topics Section {Unmapped}

### Stress and Eczema (`tpl_32`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Columns {Unmapped}
- Stress Busters Section {Unmapped}
- Recommended Topics {Unmapped}

### VOC Survey Page (`tpl_33`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Feedback Form
- Footer Links
- Back to Top Button {Unmapped}

### Eczema Treatment Options (`tpl_34`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Introduction Content {Unmapped}
- Next Page CTA {Unmapped}
- Recommended Topics
- Site Footer

### Eczema Routine Guide (`tpl_35`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Promo Drawer {Unmapped}
- Introduction Columns {Unmapped}
- Tips Section {Unmapped}
- Quick Poll {Unmapped}
- Inline Call to Action {Unmapped}
- Recommended Topics {Unmapped}

### Winter Eczema Insights (`tpl_36`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Social Share {Unmapped}
- Main Content Introduction {Unmapped}
- Image with Text {Unmapped}
- Scientific Takeaway {Unmapped}
- Recommended Topics {Unmapped}

### Treatment Video Transcript (`tpl_37`) — 1 pages

- Utility Navigation {Unmapped}
- Site Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Social Sharing {Unmapped}
- Video Player
- Transcript Content {Unmapped}
- Recommended Topics {Unmapped}
- Footer

### Eczema Treatment Overview (`tpl_38`) — 1 pages

- Utility Navigation {Unmapped}
- Site Header
- Mega Navigation {Unmapped}
- Hero Section
- Introductory Text {Unmapped}
- Social Share {Unmapped}
- Video Player
- Treatment Options Accordion
- Reactive and Proactive Section {Unmapped}

### Supporting Eczema Teens (`tpl_39`) — 1 pages

- Utility Navigation {Unmapped}
- Site Header {Unmapped}
- Hero Banner {Unmapped}
- Social Sharing {Unmapped}
- Introduction Section {Unmapped}
- Multi-Column Content {Unmapped}
- Tips Section {Unmapped}
- Topics Recommendation {Unmapped}

### Connect With Us (`tpl_40`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Promo Drawer {Unmapped}
- Social Media CTAs {Unmapped}
- Recommended Topics {Unmapped}
- Footer Links

### Eczema Stories Transcript (`tpl_41`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header
- Mega Navigation {Unmapped}
- Hero Section
- Video Player
- Transcript Text {Unmapped}
- Recommended Topics {Unmapped}
- Footer Links

### Support and Resources (`tpl_43`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Carousel
- Footer Section
- Back to Top {Unmapped}

### Learnings from the Lab (`tpl_44`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Content Introduction {Unmapped}
- Featured Articles
- Footer

### Sign-Up Confirmation (`tpl_45`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Confirmation Message {Unmapped}
- Quick Poll 1 {Unmapped}
- Quick Poll 2 {Unmapped}
- Recommended Topics {Unmapped}
- Footer Section {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                       │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                    │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Recommended Topics {Unmapped}   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Global Utility Strip {Unmapped} │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped}   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Footer                          │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Primary Navigation              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Video Player                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links                    │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Social Share {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Introduction Text {Unmapped}    │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Mega Navigation {Unmapped}      │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T46 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                              │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Section                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Alternative Methods Section            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Arms Carousel                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Atopic March Highlight {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Back to Top {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Background Video Section               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Comparison Section {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Confirmation Message {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Introduction {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Default Inline Tout Title 1 {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Default Inline Tout Title 2 {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T46 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Understanding Eczema Overview (6 pgs)                                                             │
│ • Homepage and Personalization (2 pgs)                                                              │
│ • Specialist Locator Tool (2 pgs)                                                                   │
│ • Sign-Up Page (1 pgs)                                                                              │
│ • Search Results (1 pgs)                                                                            │
│ • Eczema Comorbidities (1 pgs)                                                                      │
│ • Types of Eczema (1 pgs)                                                                           │
│ • Causes of Eczema (1 pgs)                                                                          │
│ • Severity and Impact (1 pgs)                                                                       │
│ • Homepage Experience (1 pgs)                                                                       │
│ • Footer Touts - Personalized (1 pgs)                                                               │
│ • Inline Touts (1 pgs)                                                                              │
│ • Default Inline Touts (1 pgs)                                                                      │
│ • Default Footer Touts (1 pgs)                                                                      │
│ • What Is Eczema (1 pgs)                                                                            │
│ • Eczema Symptoms and Pictures (1 pgs)                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Eczema Experience Tool (1 pgs)                                                                    │
│ • Scratch Cycle Video Transcript (1 pgs)                                                            │
│ • Doctor Partnership Guide (1 pgs)                                                                  │
│ • Eczema Itch Insights (1 pgs)                                                                      │
│ • Trigger Words Activity (1 pgs)                                                                    │
│ • Dermatologist Reacts Activity (1 pgs)                                                             │
│ • Home Remedies (1 pgs)                                                                             │
│ • Living With Eczema Stories (1 pgs)                                                                │
│ • Sitemap (1 pgs)                                                                                   │
│ • Eczema Specialist Locator (1 pgs)                                                                 │
│ • Doctor Discussion Guide (1 pgs)                                                                   │
│ • Thank You Page (1 pgs)                                                                            │
│ • Invisible Impact Article (1 pgs)                                                                  │
│ • Eczema Emotional Health (1 pgs)                                                                   │
│ • Stay Tuned Page (1 pgs)                                                                           │
│ • Personalized Homepage (1 pgs)                                                                     │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Eczema Diet Insights (1 pgs)                                                                      │
│ • Stress and Eczema (1 pgs)                                                                         │
│ • VOC Survey Page (1 pgs)                                                                           │
│ • Eczema Treatment Options (1 pgs)                                                                  │
│ • Eczema Routine Guide (1 pgs)                                                                      │
│ • Winter Eczema Insights (1 pgs)                                                                    │
│ • Treatment Video Transcript (1 pgs)                                                                │
│ • Eczema Treatment Overview (1 pgs)                                                                 │
│ • Supporting Eczema Teens (1 pgs)                                                                   │
│ • Connect With Us (1 pgs)                                                                           │
│ • Eczema Stories Transcript (1 pgs)                                                                 │
│ • Support and Resources (1 pgs)                                                                     │
│ • Learnings from the Lab (1 pgs)                                                                    │
│ • Sign-Up Confirmation (1 pgs)                                                                      │
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
| tpl_0 | Homepage and Personalization | This template includes the homepage and personalization features, presenting introductory information about eczema and resources for users, including links to detailed topics and sign-up options. | https://www.eczemaheadquarters.com/, https://www.eczemaheadquarters.com/personalization | 2 |
| tpl_1 | Sign-Up Page | This page is dedicated to user registration for updates, offering fields for personal information and preferences to tailor communications. | https://www.eczemaheadquarters.com/sign-up | 1 |
| tpl_2 | Search Results | A search results page displaying links and summaries of content relevant to user queries, with filtering options. | https://www.eczemaheadquarters.com/search-results | 1 |
| tpl_3 | Eczema Comorbidities | Explores conditions related to eczema, such as asthma and allergies, including detailed explanations and mental health resources. | https://www.eczemaheadquarters.com/understanding-eczema/eczema-comorbidities | 1 |
| tpl_4 | Types of Eczema | Provides detailed descriptions of various eczema types, symptoms, and triggers, along with comparative information about psoriasis. | https://www.eczemaheadquarters.com/about-eczema/types-of-eczema | 1 |
| tpl_5 | Causes of Eczema | Focuses on the potential causes of eczema, including genetic factors, immune system overactivity, and environmental triggers. | https://www.eczemaheadquarters.com/understanding-eczema/what-causes-eczema | 1 |
| tpl_6 | Severity and Impact | Discusses how eczema severity is assessed, including itch intensity, affected body area, and life impact, with preparation tips for doctor visits. | https://www.eczemaheadquarters.com/understanding-eczema/eczema-severity-and-impact | 1 |
| tpl_7 | Homepage Experience | Localized or personalized homepage view tailored to returning visitors, emphasizing introductory and navigation elements. | https://www.eczemaheadquarters.com/personalization/homepage-experience | 1 |
| tpl_8 | Footer Touts - Personalized | Personalized footer content offering quick links to topics like eczema types, symptoms, treatments, and related conditions. | https://www.eczemaheadquarters.com/personalization/footer-touts | 1 |
| tpl_9 | Inline Touts | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/personalization/inline-touts | 1 |
| tpl_10 | Default Inline Touts | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/personalization/default-content/inline-touts | 1 |
| tpl_11 | Default Footer Touts | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/personalization/default-content/footer-touts | 1 |
| tpl_12 | What Is Eczema | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/about-eczema/what-is-eczema | 1 |
| tpl_13 | Eczema Symptoms and Pictures | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/about-eczema/eczema-symptoms-and-pictures | 1 |
| tpl_14 | Eczema Experience Tool | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/understanding-eczema/eczema-experience-tool | 1 |
| tpl_15 | Scratch Cycle Video Transcript | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/understanding-eczema/eczema-itch-pruritus/scratch-cycle-video-transcript | 1 |
| tpl_16 | Doctor Partnership Guide | Discusses how to build a strong relationship with your doctor, emphasizing communication and mutual understanding for better eczema management. | https://www.eczemaheadquarters.com/learnings-from-the-lab/partnering-with-your-doctor | 1 |
| tpl_17 | Eczema Itch Insights | Explores the causes and impact of eczema-related itching, focusing on the itch-scratch cycle and management strategies. | https://www.eczemaheadquarters.com/understanding-eczema/eczema-itch-pruritus | 1 |
| tpl_18 | Trigger Words Activity | Shares experiences from individuals living with eczema through interactive activities, aiming to foster connection and awareness. | https://www.eczemaheadquarters.com/living-with-eczema/eczema-stories/trigger-words-transcript | 1 |
| tpl_19 | Dermatologist Reacts Activity | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/living-with-eczema/eczema-stories/derm-reacts-transcript | 1 |
| tpl_20 | Understanding Eczema Overview | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/understanding-eczema, https://www.eczemaheadquarters.com/living-with-eczema, https://www.eczemaheadquarters.com/landing | 6 |
| tpl_21 | Home Remedies | Failed to load page; cannot describe template. | https://www.eczemaheadquarters.com/learnings-from-the-lab/home-remedies | 1 |
| tpl_22 | Living With Eczema Stories | Highlights personal stories of individuals living with eczema, including activities and shared experiences to raise awareness. | https://www.eczemaheadquarters.com/living-with-eczema/eczema-stories | 1 |
| tpl_23 | Sitemap | Provides navigation links and an overview of available content on the site for easy access. | https://www.eczemaheadquarters.com/sitemap | 1 |
| tpl_24 | Eczema Specialist Locator | Facilitates finding eczema specialists nearby, such as dermatologists and allergists, for professional consultation and care. | https://www.eczemaheadquarters.com/treating-eczema/eczema-specialists | 1 |
| tpl_25 | Doctor Discussion Guide | A page providing resources and advice for discussing eczema with healthcare providers. | https://www.eczemaheadquarters.com/treating-eczema/doctor-discussion-guide | 1 |
| tpl_26 | Thank You Page | A confirmation page that users see after completing an action or form submission. | https://www.eczemaheadquarters.com/landing/thanks | 1 |
| tpl_27 | Invisible Impact Article | An article exploring unseen effects and implications of eczema. | https://www.eczemaheadquarters.com/learnings-from-the-lab/invisible-impact | 1 |
| tpl_28 | Eczema Emotional Health | Insights into the emotional and mental health impacts of living with eczema. | https://www.eczemaheadquarters.com/living-with-eczema/eczema-and-emotional-health | 1 |
| tpl_29 | Stay Tuned Page | A placeholder page indicating updates or upcoming content related to eczema. | https://www.eczemaheadquarters.com/landing/stay-tuned | 1 |
| tpl_30 | Personalized Homepage | A homepage tailored for individual user experiences within eczema-related content. | https://www.eczemaheadquarters.com/personalization/homepage-experience-full | 1 |
| tpl_31 | Eczema Diet Insights | A detailed exploration of dietary influences on eczema management. | https://www.eczemaheadquarters.com/learnings-from-the-lab/eczema-diets | 1 |
| tpl_32 | Stress and Eczema | Content delving into the relationship between stress and eczema symptoms. | https://www.eczemaheadquarters.com/living-with-eczema/eczema-and-stress | 1 |
| tpl_33 | VOC Survey Page | A page inviting users to participate in a survey for improving site resources and support. | https://www.eczemaheadquarters.com/eczema-support-and-resources/voc-survey | 1 |
| tpl_34 | Eczema Treatment Options | Overview of available treatments for eczema, including biologics and oral molecules. | https://www.eczemaheadquarters.com/treating-eczema/eczema-treatment-options | 1 |
| tpl_35 | Eczema Routine Guide | Guidance for establishing effective daily routines to manage eczema symptoms. | https://www.eczemaheadquarters.com/living-with-eczema/eczema-routine | 1 |
| tpl_36 | Winter Eczema Insights | Tips and insights for managing eczema during the winter season. | https://www.eczemaheadquarters.com/learnings-from-the-lab/winter-eczema | 1 |
| tpl_37 | Treatment Video Transcript | A transcript accompanying video resources on eczema treatment options. | https://www.eczemaheadquarters.com/treating-eczema/options-for-eczema-treatment/treatment-video-transcript | 1 |
| tpl_38 | Eczema Treatment Overview | Comprehensive details about various treatments for eczema. | https://www.eczemaheadquarters.com/treating-eczema/options-for-eczema-treatment | 1 |
| tpl_39 | Supporting Eczema Teens | Resources and articles focusing on the challenges teens face with eczema. | https://www.eczemaheadquarters.com/learnings-from-the-lab/supporting-eczema-teens | 1 |
| tpl_40 | Connect With Us | A page encouraging social media engagement and community building for eczema awareness. | https://www.eczemaheadquarters.com/connect-with-us | 1 |
| tpl_41 | Eczema Stories Transcript | Transcripts of real-life stories shared by individuals living with eczema. | https://www.eczemaheadquarters.com/living-with-eczema/eczema-stories/fill-in-the-blank-transcript | 1 |
| tpl_42 | Specialist Locator Tool | A tool to find eczema specialists near the user for personalized care. | https://www.eczemaheadquarters.com/treating-eczema/doctor-near-me, https://www.eczemaheadquarters.com/treating-eczema/eczema-specialist-near-me | 2 |
| tpl_43 | Support and Resources | A hub for accessing various resources and support for managing eczema. | https://www.eczemaheadquarters.com/eczema-support-and-resources | 1 |
| tpl_44 | Learnings from the Lab | Scientific insights and recent discoveries related to eczema research. | https://www.eczemaheadquarters.com/learnings-from-the-lab | 1 |
| tpl_45 | Sign-Up Confirmation | A confirmation page following registration for newsletters or programs. | https://www.eczemaheadquarters.com/sign-up/confirmation | 1 |
