# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **67** URLs; **29** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Homepage and General Overview**, **What Is Crohns Disease — group 17**, **Support And Resources — group 18**. **92** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:16:39.884Z
- **Website**: https://www.crohnsandcolitis.com/
- **Total Pages Analyzed**: 67
- **Total Templates Identified**: 29
- **Total Components Identified**: 92
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.CROHNSANDCOLITIS.COM TEMPLATES                                           │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage and General Overview        │    │ What Is Crohns Disease — group 17    │    │ Support And Resources — group 18     │
│ (3 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Main Navigation                    │    │ • Main Navigation {Unmapped}         │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Call-to-Action Section             │    │ • On This Page Links {Unmapped}      │    │ • On This Page CTAs {Unmapped}       │
│ • (+3 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+8 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Crohn's Disease Overview             │    │ Ulcerative Colitis Overview          │    │ Biologics for Crohn's Disease        │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header                     │    │ • Primary Header {Unmapped}          │    │ • Main Navigation {Unmapped}         │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │
│ • Main CTA Columns {Unmapped}        │    │ • Main Navigation {Unmapped}         │    │ • In-Page Navigation {Unmapped}      │
│ • (+3 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Targeted Treatments for Crohn's Dis… │    │ UC Severity and Progression          │    │ Treatment Options for Ulcerative Co… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Header {Unmapped}          │    │ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • On This Page CTAs {Unmapped}       │    │ • On This Page CTA {Unmapped}        │    │ • On This Page CTAs {Unmapped}       │
│ • (+4 more — see Blocks mapped per … │    │ • (+8 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Introduction to Ulcerative Colitis   │    │ Search Results Page                  │    │ Sign Up and Resources Access         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Header                      │    │ • Utility Strip {Unmapped}           │
│ • Primary Site Header {Unmapped}     │    │ • Search Box                         │    │ • Primary Header                     │
│ • Hero Banner {Unmapped}             │    │ • Hero Section                       │    │ • Main Navigation {Unmapped}         │
│ • Main Navigation Menu {Unmapped}    │    │ • Search Results {Unmapped}          │    │ • Hero Section                       │
│ • (+6 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Find a Gastroenterologist            │    │ Living with Ulcerative Colitis       │    │ Sitemap for Ulcerative Colitis       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation          │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • On This Page CTA {Unmapped}        │    │ • Main Call-to-Action Buttons {Unma… │    │ • Content Introduction {Unmapped}    │
│ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Crohn's Disease Sitemap              │    │ Stress and IBD                       │    │ Impact Tool for IBD                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Main Navigation                    │
│ • Main Navigation {Unmapped}         │    │ • Main Content Columns {Unmapped}    │    │ • Hero Section                       │
│ • (+5 more — see Blocks mapped per … │    │ • Footer Navigation                  │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap — group 19                   │    │ Treatment Options — group 20         │    │ Impact Of Ibd — group 21             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Primary Header {Unmapped}          │    │ • Primary Header                     │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • On This Page Links {Unmapped}      │    │ • Page Introduction {Unmapped}       │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.CROHNSANDCOLITIS.COM — SUB-TEMPLATES TEMPLATES                           │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Causes — group 22                    │    │ Site Map — group 23                  │    │ Find A Gastroenterologist — group 24 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Links Bar {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Page CTAs                          │    │ • Content Area {Unmapped}            │    │ • ZIP Code Search                    │
│ • (+4 more — see Blocks mapped per … │    │ • Footer Links                       │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Diet And Exercise — group 25         │    │ Appointment Preparation Page         │    │ Ulcerative Colitis Symptoms          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │    │ • Primary Header {Unmapped}          │
│ • On This Page CTAs {Unmapped}       │    │ • Hero Section                       │    │ • Mega Navigation {Unmapped}         │
│ • —                                  │    │ • Info and CTA Section {Unmapped}    │    │ • Hero Section                       │
│ • —                                  │    │ • (+8 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Crohn's Symptoms Overview            │    │ Causes of Crohn's Disease            │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section                       │
│ • On This Page Links {Unmapped}      │    │ • On This Page CTAs {Unmapped}       │
│ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Homepage and General Overview (`tpl_0`) — 3 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Call-to-Action Section
- Footer Section
- Back to Top Button {Unmapped}
- Modal Overlay

### What Is Crohns Disease — group 17 (`tpl_16`) — 2 pages

- Utility Navigation
- Main Navigation
- Hero Section
- On This Page Links {Unmapped}
- IBD vs IBS Section {Unmapped}
- Crohn's vs UC Section {Unmapped}
- Diagnosing Crohn's Section {Unmapped}
- Footer

### Support And Resources — group 18 (`tpl_17`) — 2 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section {Unmapped}
- On This Page CTAs {Unmapped}
- Support Networks Section {Unmapped}
- Social Media Section {Unmapped}
- Charities Section {Unmapped}
- Awareness and Advocacy Section {Unmapped}
- Recommended Topics {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Cookie Consent {Unmapped}

### Crohn's Disease Overview (`tpl_1`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Section
- Main CTA Columns {Unmapped}
- Information Section {Unmapped}
- Subscription CTA {Unmapped}
- Footer

### Ulcerative Colitis Overview (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Main Navigation {Unmapped}
- Call-to-Action Section {Unmapped}
- Informational Columns {Unmapped}
- Subscription Call-to-Action {Unmapped}
- Footer Social Links {Unmapped}
- Footer Navigation {Unmapped}

### Biologics for Crohn's Disease (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section {Unmapped}
- In-Page Navigation {Unmapped}

### Targeted Treatments for Crohn's Disease (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- On This Page CTAs {Unmapped}
- Biologics Section {Unmapped}
- Types of Biologics {Unmapped}
- Small Molecules Section {Unmapped}
- Recommended Topics {Unmapped}

### UC Severity and Progression (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header
- Hero Section
- On This Page CTA {Unmapped}
- Severity Levels {Unmapped}
- Inflammation Section {Unmapped}
- Progression Images {Unmapped}
- Complications Section {Unmapped}
- Accordion - More Info
- Symptoms Tracking Section {Unmapped}
- Recommended Topics {Unmapped}
- Footer

### Treatment Options for Ulcerative Colitis (`tpl_6`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- On This Page CTAs {Unmapped}
- Treatment Goals Section {Unmapped}
- Treatment Options Section {Unmapped}
- Footer

### Introduction to Ulcerative Colitis (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Site Header {Unmapped}
- Hero Banner {Unmapped}
- Main Navigation Menu {Unmapped}
- Introductory Content {Unmapped}
- Quick Navigation Links {Unmapped}
- IBD vs IBS Comparison {Unmapped}
- UC vs Crohn's Comparison {Unmapped}
- Diagnosing UC Information {Unmapped}
- Expandable Accordion

### Search Results Page (`tpl_8`) — 1 pages

- Global Header
- Search Box
- Hero Section
- Search Results {Unmapped}
- Footer
- Back to Top {Unmapped}

### Sign Up and Resources Access (`tpl_9`) — 1 pages

- Utility Strip {Unmapped}
- Primary Header
- Main Navigation {Unmapped}
- Hero Section
- Footer Section
- Back to Top Button {Unmapped}
- Modal Dialogs

### Find a Gastroenterologist (`tpl_10`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- On This Page CTA {Unmapped}
- Why See a Gastroenterologist {Unmapped}
- Larger Care Team {Unmapped}
- Recommended Topics {Unmapped}
- Footer Section
- Back to Top Button {Unmapped}

### Living with Ulcerative Colitis (`tpl_11`) — 1 pages

- Global Utility Navigation
- Primary Navigation
- Hero Section
- Main Call-to-Action Buttons {Unmapped}
- Information Section {Unmapped}
- Highlighted Tips Section
- Footer Links

### Sitemap for Ulcerative Colitis (`tpl_12`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Main Content Columns
- On This Page Links {Unmapped}
- Targeted Treatments Section {Unmapped}
- Small Molecules Section {Unmapped}
- Biologics Section {Unmapped}
- Treatment Options CTA {Unmapped}
- Recommended Topics {Unmapped}

### Crohn's Disease Sitemap (`tpl_13`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Main Navigation {Unmapped}
- Content Introduction {Unmapped}
- Rich Text Section {Unmapped}
- Image Gallery {Unmapped}
- CTA Buttons {Unmapped}
- Footer Section

### Stress and IBD (`tpl_14`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Columns {Unmapped}
- Footer Navigation

### Impact Tool for IBD (`tpl_15`) — 1 pages

- Utility Navigation
- Primary Header
- Main Navigation
- Hero Section
- Introduction Paragraph {Unmapped}
- On This Page Links {Unmapped}
- Stress Faces Section
- Support Groups Section {Unmapped}
- Recommended Topics
- Footer Social Share
- Footer Links

### Sitemap — group 19 (`tpl_18`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Main Content {Unmapped}
- Footer Links
- Social Media Links {Unmapped}
- Back to Top Button {Unmapped}
- Modal Dialogs

### Treatment Options — group 20 (`tpl_19`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- On This Page Links {Unmapped}
- Treatment Goals Section {Unmapped}
- Treatment Options Section {Unmapped}
- Complications Section {Unmapped}
- Inline Call-to-Action {Unmapped}

### Impact Of Ibd — group 21 (`tpl_20`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header
- Hero Section
- Page Introduction {Unmapped}
- Interactive Tool
- Footer Navigation
- Back to Top Button {Unmapped}
- Cookie Consent Modal {Unmapped}

### Causes — group 22 (`tpl_21`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Page CTAs
- Immune System Content
- Inflammation Content
- Causes Content
- Next Page Link

### Site Map — group 23 (`tpl_22`) — 1 pages

- Utility Links Bar {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Area {Unmapped}
- Footer Links

### Find A Gastroenterologist — group 24 (`tpl_23`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- ZIP Code Search
- Rich Text Introduction {Unmapped}
- Footer Section
- Back to Top Button {Unmapped}
- Terms and Conditions Modal

### Diet And Exercise — group 25 (`tpl_24`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- On This Page CTAs {Unmapped}

### Appointment Preparation Page (`tpl_25`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Info and CTA Section {Unmapped}
- Content Columns - Symptoms {Unmapped}
- Content Columns - Questions {Unmapped}
- Content Columns - Expectations {Unmapped}
- Content Columns - Communication {Unmapped}
- Additional Resources {Unmapped}
- Recommended Topics {Unmapped}
- Footer
- Back to Top {Unmapped}

### Ulcerative Colitis Symptoms (`tpl_26`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Mega Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Symptoms Section {Unmapped}
- Flare-Ups Section {Unmapped}
- Symptom Tracking Section {Unmapped}
- Recommended Topics {Unmapped}
- Footer

### Crohn's Symptoms Overview (`tpl_27`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- On This Page Links {Unmapped}
- Symptom Details {Unmapped}
- Flare-Ups Info {Unmapped}
- Symptom Tracker {Unmapped}
- Recommended Topics {Unmapped}
- Footer Links

### Causes of Crohn's Disease (`tpl_28`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- On This Page CTAs {Unmapped}
- Immune System Section {Unmapped}
- Inflammation Section {Unmapped}
- Tabs Interactive Tool {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                         │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped}        │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer                               │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Primary Navigation {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Recommended Topics {Unmapped}        │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Back to Top Button {Unmapped}        │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Main Navigation {Unmapped}           │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Primary Header {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Footer Links                         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Section                       │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ On This Page CTAs {Unmapped}         │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ On This Page Links {Unmapped}        │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Header                       │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T29 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                  │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion - More Info                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Additional Resources {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Awareness and Advocacy Section {Unmapped}  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section                     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Causes Content                             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Charities Section {Unmapped}               │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Area {Unmapped}                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns - Communication {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns - Expectations {Unmapped}  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns - Questions {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns - Symptoms {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Cookie Consent {Unmapped}                  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Cookie Consent Modal {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T29 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage and General Overview (3 pgs)                                                             │
│ • What Is Crohns Disease — group 17 (2 pgs)                                                         │
│ • Support And Resources — group 18 (2 pgs)                                                          │
│ • Crohn's Disease Overview (1 pgs)                                                                  │
│ • Ulcerative Colitis Overview (1 pgs)                                                               │
│ • Biologics for Crohn's Disease (1 pgs)                                                             │
│ • Targeted Treatments for Crohn's Disease (1 pgs)                                                   │
│ • UC Severity and Progression (1 pgs)                                                               │
│ • Treatment Options for Ulcerative Colitis (1 pgs)                                                  │
│ • Introduction to Ulcerative Colitis (1 pgs)                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Search Results Page (1 pgs)                                                                       │
│ • Sign Up and Resources Access (1 pgs)                                                              │
│ • Find a Gastroenterologist (1 pgs)                                                                 │
│ • Living with Ulcerative Colitis (1 pgs)                                                            │
│ • Sitemap for Ulcerative Colitis (1 pgs)                                                            │
│ • Crohn's Disease Sitemap (1 pgs)                                                                   │
│ • Stress and IBD (1 pgs)                                                                            │
│ • Impact Tool for IBD (1 pgs)                                                                       │
│ • Sitemap — group 19 (1 pgs)                                                                        │
│ • Treatment Options — group 20 (1 pgs)                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Impact Of Ibd — group 21 (1 pgs)                                                                  │
│ • Causes — group 22 (1 pgs)                                                                         │
│ • Site Map — group 23 (1 pgs)                                                                       │
│ • Find A Gastroenterologist — group 24 (1 pgs)                                                      │
│ • Diet And Exercise — group 25 (1 pgs)                                                              │
│ • Appointment Preparation Page (1 pgs)                                                              │
│ • Ulcerative Colitis Symptoms (1 pgs)                                                               │
│ • Crohn's Symptoms Overview (1 pgs)                                                                 │
│ • Causes of Crohn's Disease (1 pgs)                                                                 │
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
| tpl_0 | Homepage and General Overview | Includes the main landing page and general information about Crohn's and Colitis. | https://www.crohnsandcolitis.com/, https://www.crohnsandcolitis.com/personalization, https://www.crohnsandcolitis.com/ibd | 3 |
| tpl_1 | Crohn's Disease Overview | Detailed page about symptoms, causes, and treatment options for Crohn's Disease. | https://www.crohnsandcolitis.com/crohns | 1 |
| tpl_2 | Ulcerative Colitis Overview | Provides detailed information about symptoms, causes, and treatment options for Ulcerative Colitis. | https://www.crohnsandcolitis.com/ulcerative-colitis | 1 |
| tpl_3 | Biologics for Crohn's Disease | Explains biologic treatments for Crohn's, including how they work and their benefits. | https://www.crohnsandcolitis.com/crohns/biologics-for-crohns | 1 |
| tpl_4 | Targeted Treatments for Crohn's Disease | Discusses targeted oral small molecules and biologics for treating Crohn's Disease. | https://www.crohnsandcolitis.com/crohns/targeted-treatments | 1 |
| tpl_5 | UC Severity and Progression | Details the progression and severity levels of Ulcerative Colitis and their implications. | https://www.crohnsandcolitis.com/ulcerative-colitis/severity-and-progression | 1 |
| tpl_6 | Treatment Options for Ulcerative Colitis | Explains various treatment options available for Ulcerative Colitis, including biologics and corticosteroids. | https://www.crohnsandcolitis.com/ulcerative-colitis/treatment-options | 1 |
| tpl_7 | Introduction to Ulcerative Colitis | Basic informational page about what Ulcerative Colitis is and how it differs from other conditions. | https://www.crohnsandcolitis.com/ulcerative-colitis/what-is-ulcerative-colitis | 1 |
| tpl_8 | Search Results Page | Dedicated search functionality page to find content related to Crohn's and Colitis. | https://www.crohnsandcolitis.com/search-results | 1 |
| tpl_9 | Sign Up and Resources Access | Page for signing up to access resources and restroom access cards for Crohn's and Colitis patients. | https://www.crohnsandcolitis.com/sign-up | 1 |
| tpl_10 | Find a Gastroenterologist | Tool for locating a gastroenterologist specializing in Crohn's and Colitis. | https://www.crohnsandcolitis.com/you-and-your-doctor | 1 |
| tpl_11 | Living with Ulcerative Colitis | Content focused on managing life with UC, including lifestyle adjustments. | https://www.crohnsandcolitis.com/ulcerative-colitis/living-with-uc | 1 |
| tpl_12 | Sitemap for Ulcerative Colitis | Provides a sitemap and navigation for content related to Ulcerative Colitis. | https://www.crohnsandcolitis.com/ulcerative-colitis/targeted-treatments | 1 |
| tpl_13 | Crohn's Disease Sitemap | Detailed sitemap for navigating Crohn's Disease-related content. | https://www.crohnsandcolitis.com/crohns/severity-and-progression | 1 |
| tpl_14 | Stress and IBD | Information about the impact of stress on inflammatory bowel diseases. | https://www.crohnsandcolitis.com/crohns/site-map | 1 |
| tpl_15 | Impact Tool for IBD | Tool for measuring the impact of IBD on daily life and activities. | https://www.crohnsandcolitis.com/ibd/stress-and-ibd | 1 |
| tpl_16 | What Is Crohns Disease — group 17 | Same structural layout across 2 page(s) in the crawl. | https://www.crohnsandcolitis.com/crohns/what-is-crohns-disease, https://www.crohnsandcolitis.com/crohns/living-with-crohns | 2 |
| tpl_17 | Support And Resources — group 18 | Same structural layout across 2 page(s) in the crawl. | https://www.crohnsandcolitis.com/tools-and-support/support-and-resources, https://www.crohnsandcolitis.com/tools-and-support | 2 |
| tpl_18 | Sitemap — group 19 | Same structural layout across 1 page(s) in the crawl. | https://www.crohnsandcolitis.com/sitemap | 1 |
| tpl_19 | Treatment Options — group 20 | Same structural layout across 1 page(s) in the crawl. | https://www.crohnsandcolitis.com/crohns/treatment-options | 1 |
| tpl_20 | Impact Of Ibd — group 21 | Same structural layout across 1 page(s) in the crawl. | https://www.crohnsandcolitis.com/ibd/impact-of-ibd | 1 |
| tpl_21 | Causes — group 22 | Same structural layout across 1 page(s) in the crawl. | https://www.crohnsandcolitis.com/ulcerative-colitis/causes | 1 |
| tpl_22 | Site Map — group 23 | Same structural layout across 1 page(s) in the crawl. | https://www.crohnsandcolitis.com/ulcerative-colitis/site-map | 1 |
| tpl_23 | Find A Gastroenterologist — group 24 | Same structural layout across 1 page(s) in the crawl. | https://www.crohnsandcolitis.com/find-a-gastroenterologist | 1 |
| tpl_24 | Diet And Exercise — group 25 | Same structural layout across 1 page(s) in the crawl. | https://www.crohnsandcolitis.com/ibd/diet-and-exercise | 1 |
| tpl_25 | Appointment Preparation Page | A page designed to provide information and tips for patients preparing for their medical appointments. | https://www.crohnsandcolitis.com/prepare-for-your-appointment | 1 |
| tpl_26 | Ulcerative Colitis Symptoms | A detailed page explaining the symptoms associated with ulcerative colitis and guidance for managing flare-ups. | https://www.crohnsandcolitis.com/ulcerative-colitis/symptoms-flare-ups | 1 |
| tpl_27 | Crohn's Symptoms Overview | An informative page focusing on the symptoms and flare-ups related to Crohn's disease, including tips for symptom tracking and management. | https://www.crohnsandcolitis.com/crohns/symptoms-flare-ups | 1 |
| tpl_28 | Causes of Crohn's Disease | A resource page discussing the possible causes and contributing factors of Crohn's disease, aimed at educating patients. | https://www.crohnsandcolitis.com/crohns/causes | 1 |
