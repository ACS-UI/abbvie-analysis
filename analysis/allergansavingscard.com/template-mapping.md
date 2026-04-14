# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **355** URLs; **313** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **AbbVie Foundation Overview**, **Corporate Home Pages**, **Leadership Profiles**. **153** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T18:31:31.290Z
- **Website**: https://www.abbvie.com/allergan.html
- **Total Pages Analyzed**: 355
- **Total Templates Identified**: 313
- **Total Components Identified**: 153
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ABBVIE.COM TEMPLATES                                                     │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ AbbVie Foundation Overview           │    │ Corporate Home Pages                 │    │ Leadership Profiles                  │
│ (5 pages)                            │    │ (3 pages)                            │    │ (3 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Hero Section                       │
│ • Content Section - Who We Are {Unm… │    │ • —                                  │    │ • Leadership Profiles Grid {Unmappe… │
│ • Content Section - Science {Unmapp… │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Pipeline Insights                    │    │ Science Overview                     │    │ Terms of Use                         │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Bar {Unmapped}             │    │ • Utility Navigation Strip {Unmappe… │    │ • Primary Navigation {Unmapped}      │
│ • Main Navigation {Unmapped}         │    │ • Primary Site Navigation {Unmapped} │    │ • Header Logo {Unmapped}             │
│ • Hero Banner {Unmapped}             │    │ • Main Call-to-Action {Unmapped}     │    │ • Hero Section                       │
│ • Call to Action {Unmapped}          │    │ • Featured Stories Display {Unmappe… │    │ • Footer Links                       │
│ • Card Grid {Unmapped}               │    │ • Statistics Showcase {Unmapped}     │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ RD Leadership Overview               │    │ Brand Partnerships - MLB             │    │ AI and Data Convergence              │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Navigation {Unmapped}         │    │ • Main Content Section {Unmapped}    │    │ • Hero Section                       │
│ • Content Cards                      │    │ • Footer Section {Unmapped}          │    │ • Content Cards                      │
│ • —                                  │    │ • —                                  │    │ • Back to Top Button {Unmapped}      │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Assistance Overview          │    │ Research Collaborative Initiatives   │    │ Student and Graduate Programs        │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • —                                  │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Call-to-Action Columns {Unmapped}  │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Allergan Overview                    │    │ Code of Conduct                      │    │ Leadership Profile: Liz Shea         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation Header           │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Global Footer                      │
│ • Introduction Text {Unmapped}       │    │ • Hero Section                       │    │ • —                                  │
│ • Products Section {Unmapped}        │    │ • —                                  │    │ • —                                  │
│ • (+4 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Leadership Profile: Alberto Colzi    │    │ Leadership Profile: Jeffrey Stewart  │    │ Leadership Profile: Tracie Haas      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Content Area {Unmapped}    │
│ • —                                  │    │ • Main Content {Unmapped}            │    │ • Related Links Section {Unmapped}   │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Leadership Profile: Jason Smith      │    │ Leadership Profile: Robert Michael   │    │ Join AbbVie                          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Primary Navigation {Unmapped}      │    │ • Global Utility Bar {Unmapped}      │
│ • Hero Section                       │    │ • —                                  │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • Site Search {Unmapped}             │
│ • —                                  │    │ • —                                  │    │ • Cookie Preferences {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Transparency in Payments             │    │ Leadership Profile: Nicholas Donogh… │    │ Leadership Profile: Jerome Bouyer    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Primary Navigation {Unmapped}      │    │ • Utility Strip {Unmapped}           │
│ • Hero Section                       │    │ • —                                  │    │ • Primary Navigation {Unmapped}      │
│ • Main Navigation {Unmapped}         │    │ • —                                  │    │ • —                                  │
│ • Content Introduction {Unmapped}    │    │ • —                                  │    │ • —                                  │
│ • Card Grid                          │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Contact Center                       │    │ Leadership Profile: Roopal Thakkar   │    │ Equity and Inclusion Principles      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Primary Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Leader Biography {Unmapped}        │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Related Links {Unmapped}           │    │ • Main Content Introduction {Unmapp… │
│ • Card Grid                          │    │ • —                                  │    │ • CTA Button Section {Unmapped}      │
│ • Content Columns {Unmapped}         │    │ • —                                  │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Partnering in Science                │    │ Protecting Human Rights              │    │ Leadership Profile: Nisha Patel Bur… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Bar {Unmapped}             │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Search Bar {Unmapped}              │    │ • Hero Section                       │    │ • —                                  │
│ • Cookie Preferences {Unmapped}      │    │ • Content Introduction {Unmapped}    │    │ • —                                  │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Leadership Profile: Scott Reents     │    │ Positions and Views                  │    │ Leadership Profile: Jag Dosanjh      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Primary Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Footer Navigation                  │
│ • —                                  │    │ • Content Columns {Unmapped}         │    │ • —                                  │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Leadership Profile: Perry Siatis     │    │ Leadership Profile                   │    │ Principles Overview                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Main Navigation {Unmapped}         │
│ • Footer                             │    │ • Leadership Profile {Unmapped}      │    │ • CTA Grid {Unmapped}                │
│ • Back to Top Button {Unmapped}      │    │ • Back to Top Button {Unmapped}      │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Transparency Inquiry                 │    │ Accessibility Statement              │    │ Leadership Profile                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Main Content {Unmapped}            │    │ • —                                  │
│ • Content Card Grid                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Leadership Profile                   │    │ Magnified Story                      │    │ Key Facts Overview                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Key Facts Overview {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • Content Cards                      │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patients Information                 │    │ Leadership Profile                   │    │ Who We Are Overview                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Related Links {Unmapped}           │    │ • Hero Section {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • Introduction Text {Unmapped}       │
│ • —                                  │    │ • —                                  │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Inside Dream Initiative              │    │ Living with Illness                  │    │ Leadership Profile                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Header {Unmapped}           │    │ • Global Navigation Header           │
│ • Hero Section                       │    │ • Main Hero Section                  │    │ • Leadership Profile Hero            │
│ • Primary Call to Action {Unmapped}  │    │ • Navigation Menu {Unmapped}         │    │ • —                                  │
│ • Content Cards                      │    │ • Content Introduction {Unmapped}    │    │ • —                                  │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Support Resources            │    │ Leadership Profile                   │    │ Leadership Profile                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Navigation {Unmapped}       │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │    │ • —                                  │
│ • Hero Section {Unmapped}            │    │ • Leader Biography {Unmapped}        │    │ • —                                  │
│ • CTA Grid {Unmapped}                │    │ • Related Links {Unmapped}           │    │ • —                                  │
│ • Card Grid {Unmapped}               │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Supplier Resources                   │    │ Medicine Discovery Insights          │    │ Ethical Research Commitment          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Content Introduction {Unmapped}    │    │ • Content Introduction {Unmapped}    │    │ • Content Introduction {Unmapped}    │
│ • Content Card Grid                  │    │ • Featured Card {Unmapped}           │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sustainability Overview              │    │ Magnified Story                      │    │ Magnified Story                      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Content Columns {Unmapped}         │    │ • Primary Navigation {Unmapped}      │    │ • Main Story Content {Unmapped}      │
│ • Card Grid                          │    │ • Main Content {Unmapped}            │    │ • Related Links {Unmapped}           │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Leadership Profile Page              │    │ FAQ on Payments Transparency         │    │ Responsible Supply Chain Overview    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation Header           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Site Footer                        │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • Hero Section {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • Data Highlight Card {Unmapped}     │
│ • —                                  │    │ • —                                  │    │ • Back to Top Button {Unmapped}      │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Scientific Innovation Story          │    │ Equity and Inclusion Impact          │    │ Operating with Integrity Overview    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Main Content Area {Unmapped}       │    │ • Hero Section {Unmapped}            │
│ • Main Content Area {Unmapped}       │    │ • Footer Section                     │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Website Sitemap                      │    │ Payment Transparency Overview        │    │ Our Stories Landing Page             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Bar {Unmapped}             │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Site Map {Unmapped}                │    │ • Content Columns                    │    │ • Content Cards                      │
│ • Footer Section                     │    │ • Footer                             │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Policies and Disclosures             │    │ Product Information Page             │    │ Engineer Diversity Profile           │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Convergence of Minds Story           │    │ Nonprofit Partnership Impact         │    │ Magnified Series Feature             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Footer                             │    │ • Main Content {Unmapped}            │    │ • Footer Links                       │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ AI Innovation Story                  │    │ Eye Disease Research Focus           │    │ Environmental Sustainability Efforts │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Main Navigation                    │
│ • Content Teasers {Unmapped}         │    │ • Main Content {Unmapped}            │    │ • Story Highlight                    │
│ • Dashboard Cards                    │    │ • —                                  │    │ • Fact Highlight                     │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Perseverance Story           │    │ Green Chemistry Innovations          │    │ Human Factors Engineering Insight    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │    │ • Utility Links {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Site Navigation {Unmapped}         │
│ • Hero Section {Unmapped}            │    │ • —                                  │    │ • Content Area {Unmapped}            │
│ • Story Cards {Unmapped}             │    │ • —                                  │    │ • Scroll Button {Unmapped}           │
│ • (+2 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Real-World Data Utilization          │    │ Alzheimer's Disease Challenges       │    │ IBD Patient Story                    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Content {Unmapped}         │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • —                                  │    │ • Back to Top Button {Unmapped}      │
│ • Main Content Area {Unmapped}       │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Data Science Impact                  │    │ Migraine Analysis Story              │    │ Patient-Centric Packaging            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Footer                             │    │ • Site Search                        │    │ • —                                  │
│ • —                                  │    │ • Cookie Preferences {Unmapped}      │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Protein Degradation Research         │    │ Patient Access Director Insight      │    │ Nonprofits and COVID-19              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Multi-Column CTAs {Unmapped}       │
│ • —                                  │    │ • —                                  │    │ • Card Grid                          │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Uterine Fibroids Patient Experience  │    │ Magnified Series: Linda Scarazzini   │    │ Antiviral Expertise for COVID-19     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • —                                  │
│ • Content Grid {Unmapped}            │    │ • Content Introduction {Unmapped}    │    │ • —                                  │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Precision Medicine Expansion         │    │ Value of Walking Down the Aisle      │    │ Genome Sequencing Potential          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Primary Header                     │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Content Cards                      │    │ • —                                  │
│ • Call-to-Action Columns {Unmapped}  │    │ • Data Highlights {Unmapped}         │    │ • —                                  │
│ • Card Grid                          │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Glaucoma and Eye Health Awareness    │    │ BTK Protein Research                 │    │ Eye Care Editorial Stories           │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • —                                  │
│ • Back to Top Button {Unmapped}      │    │ • Hero Section                       │    │ • —                                  │
│ • —                                  │    │ • Footer                             │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Medicinal Chemists Against Autoimmu… │    │ Blood Cancer Treatment Evolution     │    │ AbbVie's R&D Investment Story        │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Site Search {Unmapped}             │    │ • Back to Top Button {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Cookie Preferences {Unmapped}      │    │ • —                                  │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Unlocking One Million Genomes        │    │ Hepatitis C Research Breakthroughs   │    │ Psoriasis Patient Stories            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Primary Navigation {Unmapped}      │    │ • Global Navigation {Unmapped}       │
│ • Primary Header {Unmapped}          │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Hero Section {Unmapped}            │    │ • Main Content {Unmapped}            │    │ • Main Content {Unmapped}            │
│ • Main Navigation {Unmapped}         │    │ • Footer                             │    │ • Footer                             │
│ • Card Grid                          │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Aesthetics Editorial Stories         │    │ Patient Support Editorial Stories    │    │ Partnership Success Stories          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Story Cards                        │    │ • Footer Links                       │    │ • Hero Section                       │
│ • —                                  │    │ • Back to Top Button {Unmapped}      │    │ • Story Highlight                    │
│ • —                                  │    │ • —                                  │    │ • Dashboard Cards                    │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Personalized Medicine Challenges     │    │ Puerto Rico Health Center Rebuilding │    │ Day in Life Story Template           │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Main Navigation {Unmapped}         │    │ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Content Lead {Unmapped}            │    │ • CTA Button {Unmapped}              │
│ • —                                  │    │ • Text Columns {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • Back to Top {Unmapped}             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Neuroscience Stories Template        │    │ EEDI Stories Format                  │    │ Volunteer and Community Stories Tem… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Back to Top Button {Unmapped}      │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • —                                  │    │ • Card Grid - Stories                │    │ • Main Content {Unmapped}            │
│ • —                                  │    │ • Dashboard Cards {Unmapped}         │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Navigating Health Challenges Templa… │    │ Public Health and Safety Template    │    │ Vaccination Hope Template            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Navigation Bar {Unmapped}          │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • —                                  │    │ • Call-to-Action Grid {Unmapped}     │    │ • Card Grid {Unmapped}               │
│ • —                                  │    │ • Card Teasers                       │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Vision and Health Progress Template  │    │ Oncology Insights Template           │    │ Immunology Stories Template          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ COVID-19 Lessons Template            │    │ Patient Advocacy and Voices Template │    │ Community School Project Template    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Content Columns {Unmapped}         │    │ • Content Introduction {Unmapped}    │    │ • Content Grid {Unmapped}            │
│ • Card Grid                          │    │ • Card Grid {Unmapped}               │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Corporate Integration Insights Temp… │    │ Employee Spotlight Template          │    │ Equity in Dermatology Template       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Main Content {Unmapped}            │    │ • Primary Navigation {Unmapped}      │
│ • Main Content {Unmapped}            │    │ • —                                  │    │ • Main Content {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Workplace Reimagining Template       │    │ Family Benefits and Support Template │    │ Blood Cancer Vision Template         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Story Highlight Cards              │
│ • Main Content Area {Unmapped}       │    │ • Story Highlight                    │    │ • Call to Action Section {Unmapped}  │
│ • (+2 more — see Blocks mapped per … │    │ • Dashboard Cards                    │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Hepatitis C Elimination Template     │    │ Pandemic Hope and Conversations Tem… │    │ Sustainability and Growth Template   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Content Introduction {Unmapped}    │    │ • Main Content Area {Unmapped}       │    │ • Hero Section                       │
│ • Call-to-Action Buttons {Unmapped}  │    │ • —                                  │    │ • Main Content {Unmapped}            │
│ • (+2 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Stroke Recovery and Research Templa… │    │ Psoriasis Journey Template           │    │ Company Impact Reflection Template   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Feature Cards                      │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • Call-to-Action {Unmapped}          │    │ • Call-to-Action Button {Unmapped}   │
│ • —                                  │    │ • Content Section {Unmapped}         │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Digital Science Lab                  │    │ Eye Disease Focus                    │    │ AI in Drug Discovery                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Primary Content {Unmapped}         │    │ • Main Content {Unmapped}            │
│ • Card Grid                          │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Working at AbbVie                    │    │ Sustainability Efforts               │    │ Innovation and Action                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip               │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Main Content Area {Unmapped}       │
│ • Featured Story Card                │    │ • Call-to-Action Grid {Unmapped}     │    │ • —                                  │
│ • Dashboard Facts                    │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ COVID-19 Medicine Access             │    │ Support for Cancer Families          │    │ Accelerating Cure Discovery          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │    │ • Global Header {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Content {Unmapped}            │    │ • Main Content {Unmapped}            │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Cancer's Hidden Side                 │    │ Ambassadors in Action                │    │ Philanthropy Stories                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │
│ • Hero Section                       │    │ • Card Grid                          │    │ • Primary Navigation {Unmapped}      │
│ • Card Grid                          │    │ • —                                  │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • —                                  │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Magnified: Nicholas Donoghoe         │    │ Healthcare Microsite                 │    │ Magnified: Edrice Simmons            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Card Grid {Unmapped}               │    │ • Main Content {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • Card Grid                          │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ The Arch Tool                        │    │ Synthetic Control Arm                │    │ Immunology Frontier                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Card Grid {Unmapped}               │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Main Content {Unmapped}            │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • —                                  │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ IBD Care Improvements                │    │ Curiosity in Science                 │    │ Cancer Care Transformation           │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Main Content {Unmapped}            │    │ • Hero Section                       │
│ • —                                  │    │ • Card Grid                          │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Time is Hours                        │    │ Working Parents Community            │    │ Brand Partnerships                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Latest Stories {Unmapped}          │    │ • Latest Stories {Unmapped}          │    │ • Main Content {Unmapped}            │
│ • Call-to-Action Grid {Unmapped}     │    │ • Key Facts Section {Unmapped}       │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Change from Within                   │    │ AbbVie Research Collaborative        │    │ Rheumatoid Arthritis Awareness       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │
│ • Footer                             │    │ • Content Introduction {Unmapped}    │    │ • Back to Top Button {Unmapped}      │
│ • —                                  │    │ • Card Grid                          │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Innovation Through Health Equity     │    │ Virology Research Insights           │    │ Parkinson's Disease Advocacy         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │
│ • Hero Section                       │    │ • —                                  │    │ • Main Content Area {Unmapped}       │
│ • Card Grid                          │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Mental Health Leadership             │    │ Maternal Health Innovations          │    │ Persistence Lab Podcasts             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Card Grid                          │    │ • Hero Section {Unmapped}            │    │ • Main Content Intro {Unmapped}      │
│ • Back to Top Button {Unmapped}      │    │ • Main Content {Unmapped}            │    │ • Related Articles {Unmapped}        │
│ • —                                  │    │ • Back to Top {Unmapped}             │    │ • Footer Links                       │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Cancer Patient Support Drive         │    │ Science Stories Overview             │    │ Investigational Drugs Policy         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Card Grid                          │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Call-to-Action Section {Unmapped}  │    │ • Story Card Grid                    │    │ • Content Columns {Unmapped}         │
│ • —                                  │    │ • Dashboard Statistics {Unmapped}    │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Magnified: Johanna Corbin Feature    │    │ Community Service Stories            │    │ Inspiration: Joe's Story             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Content Teasers {Unmapped}         │    │ • Hero Section {Unmapped}            │    │ • Story Highlights Grid {Unmapped}   │
│ • CTA Buttons {Unmapped}             │    │ • Card Grid - Stories                │    │ • —                                  │
│ • Back to Top Button {Unmapped}      │    │ • Dashboard Cards {Unmapped}         │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Understanding Hidradenitis Suppurat… │    │ Predictive Analytics in Research     │    │ Profile Stories Archive              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Navigation {Unmapped}       │    │ • Utility Strip {Unmapped}           │
│ • Main Navigation {Unmapped}         │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Content Area {Unmapped}            │    │ • Main Content Area {Unmapped}       │    │ • Content Card Grid                  │
│ • —                                  │    │ • —                                  │    │ • Back to Top Button {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Emotional Impact of Ovarian Cancer   │    │ Cubs Brand Partnership               │    │ Parkinson's Community Efforts        │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • —                                  │
│ • —                                  │    │ • Call-to-Action Grid {Unmapped}     │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Mental Health and Skin Conditions    │    │ Value of Education Narrative         │    │ Impactful Stories of Little Patients │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Strip {Unmapped}           │    │ • Utility Navigation {Unmapped}      │
│ • Main Navigation                    │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Content Introduction               │    │ • Footer Links                       │    │ • Hero Section                       │
│ • Call-to-Action Buttons             │    │ • —                                  │    │ • Call-to-Action Grid {Unmapped}     │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Corporate Stories Collection         │    │ Complexities of Atopic Dermatitis    │    │ Decoding Immune System               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Links {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │
│ • Back to Top Button {Unmapped}      │    │ • Content Introduction {Unmapped}    │    │ • Main Content {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • Footer Navigation {Unmapped}       │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Working Parents Caregiver            │    │ Veteran's Mental Health              │    │ Healthcare Elevation                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Bar {Unmapped}             │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Search Functionality {Unmapped}    │    │ • Back to Top Button {Unmapped}      │    │ • —                                  │
│ • Cookie Preferences {Unmapped}      │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Medicine Delivery Efficiency         │    │ Small Cell Lung Cancer               │    │ Research in Systems                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Card Grid                          │
│ • Main Content {Unmapped}            │    │ • Card Grid                          │    │ • Call-to-Action Buttons {Unmapped}  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Drug Shortage Prevention             │    │ Facility Launch                      │    │ Living with Dystonia                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Primary Content {Unmapped}         │
│ • Main Content Area {Unmapped}       │    │ • Main Content Area {Unmapped}       │    │ • —                                  │
│ • Content Cards {Unmapped}           │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Employee Resource Groups             │    │ Genetic Medicine Insights            │    │ 2024 Working Parents                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Utility Strip {Unmapped}           │    │ • Global Utility Strip               │
│ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │
│ • Main Content Area {Unmapped}       │    │ • —                                  │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Story Highlight                    │
│ • —                                  │    │ • —                                  │    │ • Dashboard Cards                    │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Technologies in Disease Research     │    │ Educational Grants                   │    │ Andrew Campbell Profile              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Profile Overview {Unmapped}        │
│ • Content Cards                      │    │ • Multi-Column CTA {Unmapped}        │    │ • Call-to-Action Button {Unmapped}   │
│ • (+2 more — see Blocks mapped per … │    │ • Card Grid                          │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Innovation Areas                     │    │ Lab to Life                          │    │ Focus Areas                          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Utility Strip {Unmapped}           │    │ • Utility Links {Unmapped}           │
│ • Hero Section                       │    │ • Main Navigation {Unmapped}         │    │ • Main Navigation {Unmapped}         │
│ • Primary Navigation {Unmapped}      │    │ • Content Area {Unmapped}            │    │ • Footer Navigation {Unmapped}       │
│ • Innovation Highlights              │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Partnering Days                      │    │ Raymond Votzmeyer Profile            │    │ Our People                           │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Site Header                        │    │ • Utility Navigation {Unmapped}      │
│ • Hero Section                       │    │ • —                                  │    │ • Main Navigation {Unmapped}         │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Hero Section                       │
│ • Content Introduction {Unmapped}    │    │ • —                                  │    │ • Call-to-Action Buttons {Unmapped}  │
│ • Card Grid                          │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Grant Disclosures                    │    │ Eye Care Focus                       │    │ Eleni Lagkadinou Profile             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation Strip {Unmappe… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Footer Navigation {Unmapped}       │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ RD Leader Profile - Linda Scarazzini │    │ RD Leader Profile - Wolfram Nothaft  │    │ RD Leader Profile - Darin Messina    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Bar {Unmapped}      │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │
│ • —                                  │    │ • —                                  │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Science in 60 Seconds                │    │ Areas of Innovation - Genomics       │    │ Scientific Publications              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Site Header                        │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section {Unmapped}            │    │ • Page Hero                          │    │ • Primary Navigation {Unmapped}      │
│ • Main Content {Unmapped}            │    │ • Main Navigation {Unmapped}         │    │ • Hero Section                       │
│ • —                                  │    │ • Intro Content {Unmapped}           │    │ • Card Grid                          │
│ • —                                  │    │ • Feature Cards                      │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ RD Leader Profile - Shuhong Zhang    │    │ Therapeutic Modalities and Platforms │    │ Focus Area - Neuroscience            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Content {Unmapped}            │    │ • Content Grid {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • Card Grid {Unmapped}               │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ RD Leader Profile - Michael Foley    │    │ RD Leader Profile - Primal Kaur      │    │ Focus Area - Oncology                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Utility Navigation Strip           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Header and Navigation {Un… │
│ • —                                  │    │ • Hero Section                       │    │ • Content Cards                      │
│ • —                                  │    │ • Content Section                    │    │ • —                                  │
│ • —                                  │    │ • Card Grid                          │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ RD Leader Profile - Jonathon Sedgwi… │    │ Lab of the Future                    │    │ Discovery Files                      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Back to Top {Unmapped}             │
│ • —                                  │    │ • CTA Grid {Unmapped}                │    │ • —                                  │
│ • —                                  │    │ • Back to Top Button {Unmapped}      │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Precision Medicine                   │    │ Behind the Science                   │    │ RD Leader Profile - Philip Hajduk    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Primary CTA Grid {Unmapped}        │    │ • —                                  │    │ • —                                  │
│ • Secondary CTA Grid {Unmapped}      │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Focus Area - Aesthetics              │    │ Educational Grants Guide             │    │ Patient-Focused Drug Development     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Content Introduction {Unmapped}    │    │ • Content Teasers {Unmapped}         │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ RD Leader Profile - Daejin Abidoye   │    │ RD Sites                             │    │ AbbVie Ventures Portfolio            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Navigation {Unmapped}         │    │ • Global Navigation {Unmapped}       │    │ • Utility Navigation {Unmapped}      │
│ • Hero Banner                        │    │ • Hero Banner                        │    │ • Main Navigation {Unmapped}         │
│ • Content Layout {Unmapped}          │    │ • Who We Are {Unmapped}              │    │ • Footer Navigation {Unmapped}       │
│ • Footer                             │    │ • Science Section {Unmapped}         │    │ • Back-to-Top Button {Unmapped}      │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Clinical Trials Overview             │    │ Other Specialty Areas                │    │ Immunology Research                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Navigation                    │    │ • Utility Links {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Banner                        │    │ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │
│ • Who We Are Content {Unmapped}      │    │ • Hero Banner                        │    │ • Hero Section {Unmapped}            │
│ • Science Content {Unmapped}         │    │ • Content Grid {Unmapped}            │    │ • Content Columns {Unmapped}         │
│ • Clinical Trials Information {Unma… │    │ • Card Layout                        │    │ • Card Grid {Unmapped}               │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ABBVIE.COM — SUB-TEMPLATES TEMPLATES                                     │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Community of Science                 │    │ How to Apply for Grants              │    │ Corporate Opportunities              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Main Content {Unmapped}            │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • Footer Section                     │    │ • Call-to-Action Columns {Unmapped}  │
│ • Card Grid {Unmapped}               │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Assistance Income Criteria   │    │ Product Quality and Safety           │    │ Commercial Opportunities             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Site Header                        │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Page Hero                          │
│ • —                                  │    │ • Hero Section                       │    │ • Main Navigation {Unmapped}         │
│ • —                                  │    │ • Content Grid {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • Card Grid {Unmapped}               │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Savings Card Information             │    │ Grant Request Types                  │    │ Research and Development Opportunit… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Back to Top Button {Unmapped}      │
│ • Main Content Area {Unmapped}       │    │ • Content Grid {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ General Opportunities                │    │ Investigator Initiated Studies       │    │ Online Application Overview          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Footer Navigation {Unmapped}       │    │ • —                                  │
│ • Call-to-Action Grid {Unmapped}     │    │ • Back to Top Button {Unmapped}      │    │ • —                                  │
│ • Card Grid {Unmapped}               │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Application FAQs                     │    │ Eligibility Criteria                 │    │ Available Assistance Programs        │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Site Header                        │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Banner                        │
│ • —                                  │    │ • Content Columns                    │    │ • Navigation Menu {Unmapped}         │
│ • —                                  │    │ • Card Grid                          │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Frequently Asked Questions for Assi… │    │ AbbVie Ventures                      │    │ Bay Area Opportunities               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Navigation          │
│ • Hero Section                       │    │ • Content Section {Unmapped}         │    │ • Primary Header Navigation          │
│ • FAQ List {Unmapped}                │    │ • —                                  │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Introduction Content {Unmapped}    │
│ • —                                  │    │ • —                                  │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ AbbVie Pride Page                    │    │ Reasonable Accommodations            │    │ Tunisia Office Contact               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Content Highlight {Unmapped}       │    │ • —                                  │    │ • Hero Section {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • Content Section 1 {Unmapped}       │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Croatia Office Contact               │    │ Algeria Office Contact               │    │ South Africa Contact Center          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • —                                  │    │ • —                                  │
│ • Content Grid                       │    │ • —                                  │    │ • —                                  │
│ • Footer                             │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ ESG Resources                        │    │ Why AbbVie                           │    │ Addressing Barriers Initiative       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation Strip {Unmappe… │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation Bar             │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Content Cards                      │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Text Columns                       │    │ • Main Content Introduction {Unmapp… │    │ • Call to Action Section {Unmapped}  │
│ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Asian Leadership Network             │    │ Environmental and Social Governance  │    │ Veterans Resource Group              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Content Columns {Unmapped}         │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • Card Grid                          │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Internship Opportunities             │    │ Employee Benefits                    │    │ Life at AbbVie                       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation                  │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Banner                        │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Content Grid {Unmapped}            │    │ • Footer Section                     │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Slovenia Office Contact              │    │ Allergan Aesthetics Opportunities    │    │ Student Programs                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Main Navigation                    │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section                       │    │ • —                                  │    │ • Primary Navigation {Unmapped}      │
│ • Who We Are Section {Unmapped}      │    │ • —                                  │    │ • Content Section One {Unmapped}     │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Global Locations Directory           │    │ Cerevel Collaboration                │    │ Celsius Therapeutics Partnership     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Lead Content {Unmapped}            │    │ • Lead Content {Unmapped}            │
│ • —                                  │    │ • (+5 more — see Blocks mapped per … │    │ • (+8 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Nimble Therapeutics Collaboration    │    │ Capstan Therapeutics Collaboration   │    │ Women Leaders in Action              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • —                                  │
│ • Main Content Introduction {Unmapp… │    │ • Lead Content {Unmapped}            │    │ • —                                  │
│ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Graduate and Entry-Level Positions   │    │ Mitokinin Page                       │    │ Immunogen Page                       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Navigation                  │    │ • Global Utility Navigation          │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Introductory Text {Unmapped}       │    │ • Hero Section                       │
│ • Introduction Text {Unmapped}       │    │ • Neuroscience Section {Unmapped}    │    │ • Lead Content {Unmapped}            │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Equal Employment Opportunity         │    │ Innovative Impact Foundation         │    │ Operations Opportunities             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Links Bar {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Main Navigation Menu {Unmapped}    │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Learning and Development             │    │ Workplace Well-being                 │    │ Black Business Network               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation                 │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Call-to-Action Buttons {Unmapped}  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Back to Top Button {Unmapped}      │    │ • Main Content Area {Unmapped}       │
│ • —                                  │    │ • —                                  │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Employee Resource Groups Overview    │    │ Serbia Contact Center                │    │ Human Capital Management             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Content {Unmapped}            │    │ • Hero Section                       │    │ • Card Grid {Unmapped}               │
│ • —                                  │    │ • Content Grid {Unmapped}            │    │ • Prose Columns {Unmapped}           │
│ • —                                  │    │ • Footer                             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Ability at AbbVie                    │    │ Bosnia and Herzegovina Contact Cent… │    │ Disaster Relief                      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Navigation Header           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • —                                  │    │ • Hero Section                       │
│ • Content Cards                      │    │ • —                                  │    │ • Main Navigation {Unmapped}         │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Postdoctoral Program                 │    │ Ahora Hispanic Latino Network        │    │ Environmental Sustainability         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Back to Top Button {Unmapped}      │    │ • Back to Top Button {Unmapped}      │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ United States Contact Center         │    │ Aliada Therapeutics                  │    │ Lithuania Contact Center             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Who We Are Section {Unmapped}      │    │ • Back to Top Button {Unmapped}      │    │ • Hero Section                       │
│ • Science Section {Unmapped}         │    │ • —                                  │    │ • Call-to-Action Columns {Unmapped}  │
│ • Patients Section {Unmapped}        │    │ • —                                  │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Allergan Labeling                    │    │ Romania Contact Center               │    │ Estonia Contact Center               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Header Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Who We Are Section {Unmapped}      │    │ • Back to Top Button {Unmapped}      │
│ • Content Section One {Unmapped}     │    │ • Science Section {Unmapped}         │    │ • —                                  │
│ • (+2 more — see Blocks mapped per … │    │ • Patients Section {Unmapped}        │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Partnerships Page                    │    │ Location Detail Page                 │    │ Accessibility Statement              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Content Section {Unmapped}         │    │ • —                                  │
│ • Call-to-Action Grid {Unmapped}     │    │ • Card Grid                          │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Location Detail Page                 │    │ Location Detail Page                 │    │ Contact Us Page                      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Main Content Area {Unmapped}       │
│ • Content Section 1 {Unmapped}       │    │ • —                                  │    │ • —                                  │
│ • Content Section 2 {Unmapped}       │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Location Detail Page                 │    │ Community Guidelines                 │    │ Patents Information Page             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • —                                  │    │ • Hero Section                       │
│ • Who We Are Section {Unmapped}      │    │ • —                                  │    │ • Call-to-Action Grid {Unmapped}     │
│ • (+2 more — see Blocks mapped per … │    │ • —                                  │    │ • Content Columns {Unmapped}         │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Impact History Page                  │    │ Earnings Reports Page                │    │ Privacy Policy Page                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation Menu {Unmapped}  │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation                 │
│ • Hero Banner {Unmapped}             │    │ • Site Header                        │    │ • Primary Navigation                 │
│ • Introductory Text {Unmapped}       │    │ • Breadcrumbs Navigation {Unmapped}  │    │ • Search Functionality               │
│ • Timeline Section {Unmapped}        │    │ • Hero Section                       │    │ • Hero Section                       │
│ • (+6 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+8 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Privacy Inquiry Page                 │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │
│ • Main Content Area {Unmapped}       │
│ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### AbbVie Foundation Overview (`tpl_287`) — 5 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Content Section - Who We Are {Unmapped}
- Content Section - Science {Unmapped}

### Corporate Home Pages (`tpl_1`) — 3 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Leadership Profiles (`tpl_48`) — 3 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Leadership Profiles Grid {Unmapped}

### Pipeline Insights (`tpl_2`) — 2 pages

- Utility Bar {Unmapped}
- Main Navigation {Unmapped}
- Hero Banner {Unmapped}
- Call to Action {Unmapped}
- Card Grid {Unmapped}

### Science Overview (`tpl_20`) — 2 pages

- Utility Navigation Strip {Unmapped}
- Primary Site Navigation {Unmapped}
- Main Call-to-Action {Unmapped}
- Featured Stories Display {Unmapped}
- Statistics Showcase {Unmapped}

### Terms of Use (`tpl_35`) — 2 pages

- Primary Navigation {Unmapped}
- Header Logo {Unmapped}
- Hero Section
- Footer Links

### RD Leadership Overview (`tpl_207`) — 2 pages

- Global Header
- Hero Section
- Main Navigation {Unmapped}
- Content Cards

### Brand Partnerships - MLB (`tpl_215`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Section {Unmapped}
- Footer Section {Unmapped}

### AI and Data Convergence (`tpl_232`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Cards
- Back to Top Button {Unmapped}

### Patient Assistance Overview (`tpl_243`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Research Collaborative Initiatives (`tpl_248`) — 2 pages

- —

### Student and Graduate Programs (`tpl_282`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Columns {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Allergan Overview (`tpl_0`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Products Section {Unmapped}
- Aesthetics Section {Unmapped}
- Careers Section {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Code of Conduct (`tpl_3`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section

### Leadership Profile: Liz Shea (`tpl_4`) — 1 pages

- Global Navigation Header
- Global Footer

### Leadership Profile: Alberto Colzi (`tpl_5`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Leadership Profile: Jeffrey Stewart (`tpl_6`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Leadership Profile: Tracie Haas (`tpl_7`) — 1 pages

- Global Navigation {Unmapped}
- Primary Content Area {Unmapped}
- Related Links Section {Unmapped}

### Leadership Profile: Jason Smith (`tpl_8`) — 1 pages

- Global Header
- Hero Section

### Leadership Profile: Robert Michael (`tpl_9`) — 1 pages

- Primary Navigation {Unmapped}

### Join AbbVie (`tpl_10`) — 1 pages

- Global Utility Bar {Unmapped}
- Primary Navigation {Unmapped}
- Site Search {Unmapped}
- Cookie Preferences {Unmapped}

### Transparency in Payments (`tpl_11`) — 1 pages

- Global Header
- Hero Section
- Main Navigation {Unmapped}
- Content Introduction {Unmapped}
- Card Grid

### Leadership Profile: Nicholas Donoghoe (`tpl_12`) — 1 pages

- Primary Navigation {Unmapped}

### Leadership Profile: Jerome Bouyer (`tpl_13`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Contact Center (`tpl_14`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid
- Content Columns {Unmapped}

### Leadership Profile: Roopal Thakkar (`tpl_15`) — 1 pages

- Primary Navigation {Unmapped}
- Leader Biography {Unmapped}
- Related Links {Unmapped}

### Equity and Inclusion Principles (`tpl_16`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Introduction {Unmapped}
- CTA Button Section {Unmapped}
- Link List Section {Unmapped}
- Featured Story Card
- Recognition Dashboard Card {Unmapped}
- Back to Top Button {Unmapped}

### Partnering in Science (`tpl_17`) — 1 pages

- Utility Bar {Unmapped}
- Primary Navigation {Unmapped}
- Search Bar {Unmapped}
- Cookie Preferences {Unmapped}

### Protecting Human Rights (`tpl_18`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- CTA Button {Unmapped}
- Link List {Unmapped}
- Card Grid

### Leadership Profile: Nisha Patel Burns (`tpl_19`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Leadership Profile: Scott Reents (`tpl_21`) — 1 pages

- Primary Navigation {Unmapped}

### Positions and Views (`tpl_22`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Leadership Profile: Jag Dosanjh (`tpl_23`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Navigation

### Leadership Profile: Perry Siatis (`tpl_24`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Footer
- Back to Top Button {Unmapped}

### Leadership Profile (`tpl_25`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Leadership Profile {Unmapped}
- Back to Top Button {Unmapped}

### Principles Overview (`tpl_26`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- CTA Grid {Unmapped}

### Transparency Inquiry (`tpl_27`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Card Grid

### Accessibility Statement (`tpl_28`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Leadership Profile (`tpl_29`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section

### Leadership Profile (`tpl_30`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Magnified Story (`tpl_31`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Key Facts Overview (`tpl_32`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Key Facts Overview {Unmapped}
- Content Cards

### Patients Information (`tpl_33`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Leadership Profile (`tpl_34`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Related Links {Unmapped}

### Who We Are Overview (`tpl_36`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Introduction Text {Unmapped}
- Call-to-Action Button {Unmapped}
- Link List {Unmapped}
- Featured Card {Unmapped}
- Data Highlight {Unmapped}

### Inside Dream Initiative (`tpl_37`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Primary Call to Action {Unmapped}
- Content Cards

### Living with Illness (`tpl_38`) — 1 pages

- Global Header {Unmapped}
- Main Hero Section
- Navigation Menu {Unmapped}
- Content Introduction {Unmapped}
- Featured Story
- Dashboard Cards
- Back to Top Button {Unmapped}

### Leadership Profile (`tpl_39`) — 1 pages

- Global Navigation Header
- Leadership Profile Hero

### Patient Support Resources (`tpl_40`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- CTA Grid {Unmapped}
- Card Grid {Unmapped}

### Leadership Profile (`tpl_41`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section {Unmapped}
- Leader Biography {Unmapped}
- Related Links {Unmapped}

### Leadership Profile (`tpl_42`) — 1 pages

- Global Header

### Supplier Resources (`tpl_43`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Content Card Grid

### Medicine Discovery Insights (`tpl_44`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Featured Card {Unmapped}

### Ethical Research Commitment (`tpl_45`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Featured Card
- Dashboard Cards

### Sustainability Overview (`tpl_46`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Columns {Unmapped}
- Card Grid

### Magnified Story (`tpl_47`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Magnified Story (`tpl_49`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Story Content {Unmapped}
- Related Links {Unmapped}

### Leadership Profile Page (`tpl_50`) — 1 pages

- Global Navigation Header
- Site Footer

### FAQ on Payments Transparency (`tpl_51`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Responsible Supply Chain Overview (`tpl_52`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Data Highlight Card {Unmapped}
- Back to Top Button {Unmapped}

### Scientific Innovation Story (`tpl_53`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Area {Unmapped}

### Equity and Inclusion Impact (`tpl_54`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}
- Footer Section

### Operating with Integrity Overview (`tpl_55`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Introduction {Unmapped}
- Highlighted Card Grid {Unmapped}
- Back to Top Button {Unmapped}

### Website Sitemap (`tpl_56`) — 1 pages

- Utility Bar {Unmapped}
- Main Navigation {Unmapped}
- Site Map {Unmapped}
- Footer Section

### Payment Transparency Overview (`tpl_57`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Columns
- Footer

### Our Stories Landing Page (`tpl_58`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Content Cards

### Policies and Disclosures (`tpl_59`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Product Information Page (`tpl_60`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Engineer Diversity Profile (`tpl_61`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Convergence of Minds Story (`tpl_62`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Footer

### Nonprofit Partnership Impact (`tpl_63`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Magnified Series Feature (`tpl_64`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Links

### AI Innovation Story (`tpl_65`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Teasers {Unmapped}
- Dashboard Cards

### Eye Disease Research Focus (`tpl_66`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Environmental Sustainability Efforts (`tpl_67`) — 1 pages

- Global Header
- Hero Section
- Main Navigation
- Story Highlight
- Fact Highlight

### Patient Perseverance Story (`tpl_68`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Story Cards {Unmapped}
- Dashboard Facts {Unmapped}
- Back to Top Button {Unmapped}

### Green Chemistry Innovations (`tpl_69`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Human Factors Engineering Insight (`tpl_70`) — 1 pages

- Utility Links {Unmapped}
- Site Navigation {Unmapped}
- Content Area {Unmapped}
- Scroll Button {Unmapped}

### Real-World Data Utilization (`tpl_71`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}

### Alzheimer's Disease Challenges (`tpl_72`) — 1 pages

- Global Navigation {Unmapped}
- Primary Content {Unmapped}

### IBD Patient Story (`tpl_73`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Data Science Impact (`tpl_74`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer

### Migraine Analysis Story (`tpl_75`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Site Search
- Cookie Preferences {Unmapped}

### Patient-Centric Packaging (`tpl_76`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Protein Degradation Research (`tpl_77`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Patient Access Director Insight (`tpl_78`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section

### Nonprofits and COVID-19 (`tpl_79`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Multi-Column CTAs {Unmapped}
- Card Grid

### Uterine Fibroids Patient Experience (`tpl_80`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Grid {Unmapped}

### Magnified Series: Linda Scarazzini (`tpl_81`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Call-to-Action Button {Unmapped}
- Card Grid {Unmapped}
- Back to Top Button {Unmapped}

### Antiviral Expertise for COVID-19 (`tpl_82`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Precision Medicine Expansion (`tpl_83`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Columns {Unmapped}
- Card Grid

### Value of Walking Down the Aisle (`tpl_84`) — 1 pages

- Primary Header
- Main Navigation {Unmapped}
- Content Cards
- Data Highlights {Unmapped}

### Genome Sequencing Potential (`tpl_85`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Glaucoma and Eye Health Awareness (`tpl_86`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### BTK Protein Research (`tpl_87`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Footer

### Eye Care Editorial Stories (`tpl_88`) — 1 pages

- Global Header

### Medicinal Chemists Against Autoimmune Diseases (`tpl_89`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Site Search {Unmapped}
- Cookie Preferences {Unmapped}

### Blood Cancer Treatment Evolution (`tpl_90`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### AbbVie's R&D Investment Story (`tpl_91`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Content Cards
- Footer

### Unlocking One Million Genomes (`tpl_92`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Main Navigation {Unmapped}
- Card Grid

### Hepatitis C Research Breakthroughs (`tpl_93`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Footer

### Psoriasis Patient Stories (`tpl_94`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Footer

### Aesthetics Editorial Stories (`tpl_95`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Story Cards

### Patient Support Editorial Stories (`tpl_96`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Partnership Success Stories (`tpl_97`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Story Highlight
- Dashboard Cards

### Personalized Medicine Challenges (`tpl_98`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}

### Puerto Rico Health Center Rebuilding (`tpl_99`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Content Lead {Unmapped}
- Text Columns {Unmapped}
- Back to Top {Unmapped}

### Day in Life Story Template (`tpl_100`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- CTA Button {Unmapped}

### Neuroscience Stories Template (`tpl_101`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### EEDI Stories Format (`tpl_102`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Card Grid - Stories
- Dashboard Cards {Unmapped}

### Volunteer and Community Stories Template (`tpl_103`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Card Grid

### Navigating Health Challenges Template (`tpl_104`) — 1 pages

- Navigation Bar {Unmapped}

### Public Health and Safety Template (`tpl_105`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}
- Card Teasers

### Vaccination Hope Template (`tpl_106`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Card Grid {Unmapped}

### Vision and Health Progress Template (`tpl_107`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Oncology Insights Template (`tpl_108`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Immunology Stories Template (`tpl_109`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### COVID-19 Lessons Template (`tpl_110`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Card Grid

### Patient Advocacy and Voices Template (`tpl_111`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Introduction {Unmapped}
- Card Grid {Unmapped}

### Community School Project Template (`tpl_112`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Grid {Unmapped}

### Corporate Integration Insights Template (`tpl_113`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Employee Spotlight Template (`tpl_114`) — 1 pages

- Global Header {Unmapped}
- Main Content {Unmapped}

### Equity in Dermatology Template (`tpl_115`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Workplace Reimagining Template (`tpl_116`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}
- Call to Action Section {Unmapped}
- Card Grid

### Family Benefits and Support Template (`tpl_117`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Story Highlight
- Dashboard Cards

### Blood Cancer Vision Template (`tpl_118`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation
- Story Highlight Cards
- Call to Action Section {Unmapped}

### Hepatitis C Elimination Template (`tpl_119`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Call-to-Action Buttons {Unmapped}
- Card Grid {Unmapped}
- Back to Top Button {Unmapped}

### Pandemic Hope and Conversations Template (`tpl_120`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Area {Unmapped}

### Sustainability and Growth Template (`tpl_121`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Stroke Recovery and Research Template (`tpl_122`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Psoriasis Journey Template (`tpl_123`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Feature Cards
- Call-to-Action {Unmapped}
- Content Section {Unmapped}

### Company Impact Reflection Template (`tpl_124`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Call-to-Action Button {Unmapped}
- Card Grid

### Digital Science Lab (`tpl_125`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid

### Eye Disease Focus (`tpl_126`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Primary Content {Unmapped}

### AI in Drug Discovery (`tpl_127`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Working at AbbVie (`tpl_128`) — 1 pages

- Global Utility Strip
- Primary Navigation
- Hero Section
- Featured Story Card
- Dashboard Facts

### Sustainability Efforts (`tpl_129`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Call-to-Action Grid {Unmapped}
- Story Card {Unmapped}
- Dashboard Cards {Unmapped}

### Innovation and Action (`tpl_130`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}

### COVID-19 Medicine Access (`tpl_131`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Support for Cancer Families (`tpl_132`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Main Content {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Accelerating Cure Discovery (`tpl_133`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Featured Story Card
- Data Highlight {Unmapped}
- Back to Top Button {Unmapped}

### Cancer's Hidden Side (`tpl_134`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid

### Ambassadors in Action (`tpl_135`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid

### Philanthropy Stories (`tpl_136`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Featured Story Card
- Dashboard Card
- Footer

### Magnified: Nicholas Donoghoe (`tpl_137`) — 1 pages

- Global Header {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid {Unmapped}

### Healthcare Microsite (`tpl_138`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}
- Card Grid

### Magnified: Edrice Simmons (`tpl_139`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### The Arch Tool (`tpl_140`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid {Unmapped}

### Synthetic Control Arm (`tpl_141`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Immunology Frontier (`tpl_142`) — 1 pages

- Global Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Card Grid

### IBD Care Improvements (`tpl_143`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Curiosity in Science (`tpl_144`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}
- Card Grid

### Cancer Care Transformation (`tpl_145`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section

### Time is Hours (`tpl_146`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Latest Stories {Unmapped}
- Call-to-Action Grid {Unmapped}

### Working Parents Community (`tpl_147`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Latest Stories {Unmapped}
- Key Facts Section {Unmapped}

### Brand Partnerships (`tpl_148`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content {Unmapped}

### Change from Within (`tpl_149`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer

### AbbVie Research Collaborative (`tpl_150`) — 1 pages

- Global Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Content Introduction {Unmapped}
- Card Grid

### Rheumatoid Arthritis Awareness (`tpl_151`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Innovation Through Health Equity (`tpl_152`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid

### Virology Research Insights (`tpl_153`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Parkinson's Disease Advocacy (`tpl_154`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Area {Unmapped}

### Mental Health Leadership (`tpl_155`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Maternal Health Innovations (`tpl_156`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content {Unmapped}
- Back to Top {Unmapped}

### Persistence Lab Podcasts (`tpl_157`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Intro {Unmapped}
- Related Articles {Unmapped}
- Footer Links

### Cancer Patient Support Drive (`tpl_158`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid
- Call-to-Action Section {Unmapped}

### Science Stories Overview (`tpl_159`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Story Card Grid
- Dashboard Statistics {Unmapped}

### Investigational Drugs Policy (`tpl_160`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Card Grid

### Magnified: Johanna Corbin Feature (`tpl_161`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Teasers {Unmapped}
- CTA Buttons {Unmapped}
- Back to Top Button {Unmapped}

### Community Service Stories (`tpl_162`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Card Grid - Stories
- Dashboard Cards {Unmapped}

### Inspiration: Joe's Story (`tpl_163`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Story Highlights Grid {Unmapped}

### Understanding Hidradenitis Suppurativa (`tpl_164`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Content Area {Unmapped}

### Predictive Analytics in Research (`tpl_165`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}

### Profile Stories Archive (`tpl_166`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Card Grid
- Back to Top Button {Unmapped}

### Emotional Impact of Ovarian Cancer (`tpl_167`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Cubs Brand Partnership (`tpl_168`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}

### Parkinson's Community Efforts (`tpl_169`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Mental Health and Skin Conditions (`tpl_170`) — 1 pages

- Utility Navigation
- Main Navigation
- Content Introduction
- Call-to-Action Buttons
- Related Links
- Highlighted Story
- Summary Card

### Value of Education Narrative (`tpl_171`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Links

### Impactful Stories of Little Patients (`tpl_172`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}
- Card Grid

### Corporate Stories Collection (`tpl_173`) — 1 pages

- Utility Links {Unmapped}
- Main Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Complexities of Atopic Dermatitis (`tpl_174`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}

### Decoding Immune System (`tpl_175`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content {Unmapped}
- Footer Navigation {Unmapped}

### Working Parents Caregiver (`tpl_176`) — 1 pages

- Utility Bar {Unmapped}
- Primary Navigation {Unmapped}
- Search Functionality {Unmapped}
- Cookie Preferences {Unmapped}

### Veteran's Mental Health (`tpl_177`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Healthcare Elevation (`tpl_178`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Medicine Delivery Efficiency (`tpl_179`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Small Cell Lung Cancer (`tpl_180`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid

### Research in Systems (`tpl_181`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid
- Call-to-Action Buttons {Unmapped}

### Drug Shortage Prevention (`tpl_182`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}
- Content Cards {Unmapped}

### Facility Launch (`tpl_183`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Area {Unmapped}

### Living with Dystonia (`tpl_184`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Primary Content {Unmapped}

### Employee Resource Groups (`tpl_185`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Area {Unmapped}

### Genetic Medicine Insights (`tpl_186`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### 2024 Working Parents (`tpl_187`) — 1 pages

- Global Utility Strip
- Primary Navigation
- Hero Section
- Story Highlight
- Dashboard Cards

### Technologies in Disease Research (`tpl_188`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Cards
- Statistics Section {Unmapped}
- Back to Top Button {Unmapped}

### Educational Grants (`tpl_189`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Multi-Column CTA {Unmapped}
- Card Grid

### Andrew Campbell Profile (`tpl_190`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Profile Overview {Unmapped}
- Call-to-Action Button {Unmapped}
- Related Links {Unmapped}
- Profile Card
- Footer

### Innovation Areas (`tpl_191`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Innovation Highlights

### Lab to Life (`tpl_192`) — 1 pages

- Utility Strip {Unmapped}
- Main Navigation {Unmapped}
- Content Area {Unmapped}

### Focus Areas (`tpl_193`) — 1 pages

- Utility Links {Unmapped}
- Main Navigation {Unmapped}
- Footer Navigation {Unmapped}

### Partnering Days (`tpl_194`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Card Grid

### Raymond Votzmeyer Profile (`tpl_195`) — 1 pages

- Site Header

### Our People (`tpl_196`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Call-to-Action Buttons {Unmapped}

### Grant Disclosures (`tpl_197`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Eye Care Focus (`tpl_198`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Navigation {Unmapped}

### Eleni Lagkadinou Profile (`tpl_199`) — 1 pages

- Utility Navigation Strip {Unmapped}
- Primary Navigation {Unmapped}

### RD Leader Profile - Linda Scarazzini (`tpl_200`) — 1 pages

- Global Navigation {Unmapped}

### RD Leader Profile - Wolfram Nothaft (`tpl_201`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### RD Leader Profile - Darin Messina (`tpl_202`) — 1 pages

- Global Utility Bar {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Card Grid
- Dashboard Cards {Unmapped}

### Science in 60 Seconds (`tpl_203`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content {Unmapped}

### Areas of Innovation - Genomics (`tpl_204`) — 1 pages

- Site Header
- Page Hero
- Main Navigation {Unmapped}
- Intro Content {Unmapped}
- Feature Cards

### Scientific Publications (`tpl_205`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid

### RD Leader Profile - Shuhong Zhang (`tpl_206`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Therapeutic Modalities and Platforms (`tpl_208`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Grid {Unmapped}
- Card Grid {Unmapped}

### Focus Area - Neuroscience (`tpl_209`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### RD Leader Profile - Michael Foley (`tpl_210`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### RD Leader Profile - Primal Kaur (`tpl_211`) — 1 pages

- Utility Navigation Strip
- Primary Navigation
- Hero Section
- Content Section
- Card Grid

### Focus Area - Oncology (`tpl_212`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header and Navigation {Unmapped}
- Content Cards

### RD Leader Profile - Jonathon Sedgwick (`tpl_213`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Lab of the Future (`tpl_214`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Grid {Unmapped}
- Back to Top Button {Unmapped}

### Discovery Files (`tpl_216`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top {Unmapped}

### Precision Medicine (`tpl_217`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Primary CTA Grid {Unmapped}
- Secondary CTA Grid {Unmapped}

### Behind the Science (`tpl_218`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### RD Leader Profile - Philip Hajduk (`tpl_219`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Focus Area - Aesthetics (`tpl_220`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Educational Grants Guide (`tpl_221`) — 1 pages

- Global Header
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Call to Action Button {Unmapped}
- Card Grid

### Patient-Focused Drug Development (`tpl_222`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Teasers {Unmapped}

### RD Leader Profile - Daejin Abidoye (`tpl_223`) — 1 pages

- Site Navigation {Unmapped}
- Hero Banner
- Content Layout {Unmapped}
- Footer

### RD Sites (`tpl_224`) — 1 pages

- Global Navigation {Unmapped}
- Hero Banner
- Who We Are {Unmapped}
- Science Section {Unmapped}
- Card Grid
- Site Footer

### AbbVie Ventures Portfolio (`tpl_225`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Footer Navigation {Unmapped}
- Back-to-Top Button {Unmapped}

### Clinical Trials Overview (`tpl_226`) — 1 pages

- Site Navigation
- Hero Banner
- Who We Are Content {Unmapped}
- Science Content {Unmapped}
- Clinical Trials Information {Unmapped}

### Other Specialty Areas (`tpl_227`) — 1 pages

- Utility Links {Unmapped}
- Main Navigation {Unmapped}
- Hero Banner
- Content Grid {Unmapped}
- Card Layout

### Immunology Research (`tpl_228`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Columns {Unmapped}
- Card Grid {Unmapped}

### Community of Science (`tpl_229`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content {Unmapped}
- Card Grid {Unmapped}

### How to Apply for Grants (`tpl_230`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Footer Section

### Corporate Opportunities (`tpl_231`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Columns {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Patient Assistance Income Criteria (`tpl_233`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Product Quality and Safety (`tpl_234`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Grid {Unmapped}
- Card Grid {Unmapped}

### Commercial Opportunities (`tpl_235`) — 1 pages

- Site Header
- Page Hero
- Main Navigation {Unmapped}

### Savings Card Information (`tpl_236`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Area {Unmapped}

### Grant Request Types (`tpl_237`) — 1 pages

- Global Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Grid {Unmapped}

### Research and Development Opportunities (`tpl_238`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### General Opportunities (`tpl_239`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}
- Card Grid {Unmapped}

### Investigator Initiated Studies (`tpl_240`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Online Application Overview (`tpl_241`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Application FAQs (`tpl_242`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section

### Eligibility Criteria (`tpl_244`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Content Columns
- Card Grid

### Available Assistance Programs (`tpl_245`) — 1 pages

- Site Header
- Hero Banner
- Navigation Menu {Unmapped}

### Frequently Asked Questions for Assistance (`tpl_246`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- FAQ List {Unmapped}

### AbbVie Ventures (`tpl_247`) — 1 pages

- Global Navigation {Unmapped}
- Content Section {Unmapped}

### Bay Area Opportunities (`tpl_249`) — 1 pages

- Global Utility Navigation
- Primary Header Navigation
- Hero Section
- Introduction Content {Unmapped}
- Campus Teaser
- Image Carousel
- Focus Areas
- Breakthroughs Section
- Innovation Section

### AbbVie Pride Page (`tpl_250`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Highlight {Unmapped}

### Reasonable Accommodations (`tpl_251`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Tunisia Office Contact (`tpl_252`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Section 1 {Unmapped}
- Content Section 2 {Unmapped}
- Content Section 3 {Unmapped}

### Croatia Office Contact (`tpl_253`) — 1 pages

- Global Header
- Primary Navigation {Unmapped}
- Hero Section
- Content Grid
- Footer

### Algeria Office Contact (`tpl_254`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### South Africa Contact Center (`tpl_255`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### ESG Resources (`tpl_256`) — 1 pages

- Utility Navigation Strip {Unmapped}
- Primary Navigation Bar
- Content Cards
- Text Columns
- Call-to-Action Buttons {Unmapped}
- Back to Top Button {Unmapped}

### Why AbbVie (`tpl_257`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Introduction {Unmapped}
- Call-to-Action Buttons {Unmapped}
- Featured Links {Unmapped}
- Card Grid

### Addressing Barriers Initiative (`tpl_258`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call to Action Section {Unmapped}
- Card Grid

### Asian Leadership Network (`tpl_259`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Environmental and Social Governance (`tpl_260`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Card Grid

### Veterans Resource Group (`tpl_261`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Card Grid
- Dashboard Cards {Unmapped}
- Back to Top Button {Unmapped}

### Internship Opportunities (`tpl_262`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Employee Benefits (`tpl_263`) — 1 pages

- Global Navigation
- Hero Banner
- Content Grid {Unmapped}

### Life at AbbVie (`tpl_264`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Section

### Slovenia Office Contact (`tpl_265`) — 1 pages

- Global Header
- Main Navigation
- Hero Section
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}
- Footer

### Allergan Aesthetics Opportunities (`tpl_266`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Student Programs (`tpl_267`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Content Section One {Unmapped}
- Content Section Two {Unmapped}
- Card Grid
- Footer

### Global Locations Directory (`tpl_268`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Cerevel Collaboration (`tpl_269`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Lead Content {Unmapped}
- Neuroscience Section {Unmapped}
- Footer Links
- Footer Social Media
- Footer Legal
- Back to Top Button {Unmapped}

### Celsius Therapeutics Partnership (`tpl_270`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Lead Content {Unmapped}
- Content Grid 1 {Unmapped}
- Content Grid 2 {Unmapped}
- Back to Top Button {Unmapped}
- Footer Primary Links
- Footer Social Links
- Footer Popular Pages
- Footer External Links
- Footer Legal Links

### Nimble Therapeutics Collaboration (`tpl_271`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Introduction {Unmapped}
- CTA Button - Announcement {Unmapped}
- Immunology Section {Unmapped}
- Career Section {Unmapped}
- Footer Section
- Back to Top Button {Unmapped}

### Capstan Therapeutics Collaboration (`tpl_272`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Lead Content {Unmapped}
- Immunology Section {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Women Leaders in Action (`tpl_273`) — 1 pages

- Global Header
- Hero Section

### Graduate and Entry-Level Positions (`tpl_274`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Call to Action Button {Unmapped}
- Link List {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Mitokinin Page (`tpl_275`) — 1 pages

- Global Navigation
- Hero Section
- Introductory Text {Unmapped}
- Neuroscience Section {Unmapped}
- Footer Primary Links
- Footer Social Links
- Footer Legal Links
- Back to Top Button {Unmapped}

### Immunogen Page (`tpl_276`) — 1 pages

- Global Utility Navigation
- Primary Navigation
- Hero Section
- Lead Content {Unmapped}
- Spotlight Section
- Secondary Spotlight
- Footer
- Back to Top Button {Unmapped}

### Equal Employment Opportunity (`tpl_277`) — 1 pages

- Utility Links Bar {Unmapped}
- Main Navigation Menu {Unmapped}

### Innovative Impact Foundation (`tpl_278`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Operations Opportunities (`tpl_279`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Learning and Development (`tpl_280`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Call-to-Action Buttons {Unmapped}

### Workplace Well-being (`tpl_281`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Back to Top Button {Unmapped}

### Black Business Network (`tpl_283`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}
- Card Grid

### Employee Resource Groups Overview (`tpl_284`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Serbia Contact Center (`tpl_285`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Grid {Unmapped}
- Footer

### Human Capital Management (`tpl_286`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid {Unmapped}
- Prose Columns {Unmapped}

### Ability at AbbVie (`tpl_288`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Cards

### Bosnia and Herzegovina Contact Center (`tpl_289`) — 1 pages

- Global Navigation Header

### Disaster Relief (`tpl_290`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Main Navigation {Unmapped}
- Call to Action Section {Unmapped}
- Card Grid Section

### Postdoctoral Program (`tpl_291`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Ahora Hispanic Latino Network (`tpl_292`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Environmental Sustainability (`tpl_293`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### United States Contact Center (`tpl_294`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}

### Aliada Therapeutics (`tpl_295`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Lithuania Contact Center (`tpl_296`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Columns {Unmapped}
- Card Grid

### Allergan Labeling (`tpl_297`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Content Section One {Unmapped}
- Content Section Two {Unmapped}
- Content Section Three {Unmapped}

### Romania Contact Center (`tpl_298`) — 1 pages

- Header Navigation {Unmapped}
- Hero Section
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}

### Estonia Contact Center (`tpl_299`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Partnerships Page (`tpl_300`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}

### Location Detail Page (`tpl_301`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Content Section {Unmapped}
- Card Grid

### Accessibility Statement (`tpl_302`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Location Detail Page (`tpl_303`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Section 1 {Unmapped}
- Content Section 2 {Unmapped}

### Location Detail Page (`tpl_304`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}

### Contact Us Page (`tpl_305`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}

### Location Detail Page (`tpl_306`) — 1 pages

- Global Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section {Unmapped}
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}

### Community Guidelines (`tpl_307`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Patents Information Page (`tpl_308`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}
- Content Columns {Unmapped}

### Impact History Page (`tpl_309`) — 1 pages

- Global Navigation Menu {Unmapped}
- Hero Banner {Unmapped}
- Introductory Text {Unmapped}
- Timeline Section {Unmapped}
- Year 2023 Milestones {Unmapped}
- Year 2022 Milestones {Unmapped}
- Year 2021 Milestones {Unmapped}
- Year 2020 Milestones {Unmapped}
- Year 2019 Milestones {Unmapped}
- Year 2018 Milestones {Unmapped}

### Earnings Reports Page (`tpl_310`) — 1 pages

- Global Utility Strip {Unmapped}
- Site Header
- Breadcrumbs Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}
- News Details {Unmapped}

### Privacy Policy Page (`tpl_311`) — 1 pages

- Utility Navigation
- Primary Navigation
- Search Functionality
- Hero Section
- Introductory Text {Unmapped}
- Three Column CTA
- Footer Links
- Cookie Preferences
- Footer Disclaimer
- Warn on Leave Popup
- Warn on Third Party Popup
- Warn on Special Popup

### Privacy Inquiry Page (`tpl_312`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Area {Unmapped}
- Footer Section {Unmapped}
- Cookie Consent Banner {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}        │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Global Utility Strip {Unmapped}      │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section                         │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Back to Top Button {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Card Grid                            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Navigation {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Content {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Content Introduction {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer                               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Utility Strip {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Header                        │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Main Content Area {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T313 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                              │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Aesthetics Section {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back-to-Top Button {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Breadcrumbs Navigation {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Breakthroughs Section                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action {Unmapped}              │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Buttons                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Campus Teaser                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Card Grid Section                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Card Layout                            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Card Teasers                           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Career Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Careers Section {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T313 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • AbbVie Foundation Overview (5 pgs)                                                                │
│ • Corporate Home Pages (3 pgs)                                                                      │
│ • Leadership Profiles (3 pgs)                                                                       │
│ • Pipeline Insights (2 pgs)                                                                         │
│ • Science Overview (2 pgs)                                                                          │
│ • Terms of Use (2 pgs)                                                                              │
│ • RD Leadership Overview (2 pgs)                                                                    │
│ • Brand Partnerships - MLB (2 pgs)                                                                  │
│ • AI and Data Convergence (2 pgs)                                                                   │
│ • Patient Assistance Overview (2 pgs)                                                               │
│ • Research Collaborative Initiatives (2 pgs)                                                        │
│ • Student and Graduate Programs (2 pgs)                                                             │
│ • Allergan Overview (1 pgs)                                                                         │
│ • Code of Conduct (1 pgs)                                                                           │
│ • Leadership Profile: Liz Shea (1 pgs)                                                              │
│ • Leadership Profile: Alberto Colzi (1 pgs)                                                         │
│ • Leadership Profile: Jeffrey Stewart (1 pgs)                                                       │
│ • Leadership Profile: Tracie Haas (1 pgs)                                                           │
│ • Leadership Profile: Jason Smith (1 pgs)                                                           │
│ • Leadership Profile: Robert Michael (1 pgs)                                                        │
│ • Join AbbVie (1 pgs)                                                                               │
│ • Transparency in Payments (1 pgs)                                                                  │
│ • Leadership Profile: Nicholas Donoghoe (1 pgs)                                                     │
│ • Leadership Profile: Jerome Bouyer (1 pgs)                                                         │
│ • Contact Center (1 pgs)                                                                            │
│ • Leadership Profile: Roopal Thakkar (1 pgs)                                                        │
│ • Equity and Inclusion Principles (1 pgs)                                                           │
│ • Partnering in Science (1 pgs)                                                                     │
│ • Protecting Human Rights (1 pgs)                                                                   │
│ • Leadership Profile: Nisha Patel Burns (1 pgs)                                                     │
│ • Leadership Profile: Scott Reents (1 pgs)                                                          │
│ • Positions and Views (1 pgs)                                                                       │
│ • Leadership Profile: Jag Dosanjh (1 pgs)                                                           │
│ • Leadership Profile: Perry Siatis (1 pgs)                                                          │
│ • Leadership Profile (1 pgs)                                                                        │
│ • Principles Overview (1 pgs)                                                                       │
│ • Transparency Inquiry (1 pgs)                                                                      │
│ • Accessibility Statement (1 pgs)                                                                   │
│ • Leadership Profile (1 pgs)                                                                        │
│ • Leadership Profile (1 pgs)                                                                        │
│ • Magnified Story (1 pgs)                                                                           │
│ • Key Facts Overview (1 pgs)                                                                        │
│ • Patients Information (1 pgs)                                                                      │
│ • Leadership Profile (1 pgs)                                                                        │
│ • Who We Are Overview (1 pgs)                                                                       │
│ • Inside Dream Initiative (1 pgs)                                                                   │
│ • Living with Illness (1 pgs)                                                                       │
│ • Leadership Profile (1 pgs)                                                                        │
│ • Patient Support Resources (1 pgs)                                                                 │
│ • Leadership Profile (1 pgs)                                                                        │
│ • Leadership Profile (1 pgs)                                                                        │
│ • Supplier Resources (1 pgs)                                                                        │
│ • Medicine Discovery Insights (1 pgs)                                                               │
│ • Ethical Research Commitment (1 pgs)                                                               │
│ • Sustainability Overview (1 pgs)                                                                   │
│ • Magnified Story (1 pgs)                                                                           │
│ • Magnified Story (1 pgs)                                                                           │
│ • Leadership Profile Page (1 pgs)                                                                   │
│ • FAQ on Payments Transparency (1 pgs)                                                              │
│ • Responsible Supply Chain Overview (1 pgs)                                                         │
│ • Scientific Innovation Story (1 pgs)                                                               │
│ • Equity and Inclusion Impact (1 pgs)                                                               │
│ • Operating with Integrity Overview (1 pgs)                                                         │
│ • Website Sitemap (1 pgs)                                                                           │
│ • Payment Transparency Overview (1 pgs)                                                             │
│ • Our Stories Landing Page (1 pgs)                                                                  │
│ • Policies and Disclosures (1 pgs)                                                                  │
│ • Product Information Page (1 pgs)                                                                  │
│ • Engineer Diversity Profile (1 pgs)                                                                │
│ • Convergence of Minds Story (1 pgs)                                                                │
│ • Nonprofit Partnership Impact (1 pgs)                                                              │
│ • Magnified Series Feature (1 pgs)                                                                  │
│ • AI Innovation Story (1 pgs)                                                                       │
│ • Eye Disease Research Focus (1 pgs)                                                                │
│ • Environmental Sustainability Efforts (1 pgs)                                                      │
│ • Patient Perseverance Story (1 pgs)                                                                │
│ • Green Chemistry Innovations (1 pgs)                                                               │
│ • Human Factors Engineering Insight (1 pgs)                                                         │
│ • Real-World Data Utilization (1 pgs)                                                               │
│ • Alzheimer's Disease Challenges (1 pgs)                                                            │
│ • IBD Patient Story (1 pgs)                                                                         │
│ • Data Science Impact (1 pgs)                                                                       │
│ • Migraine Analysis Story (1 pgs)                                                                   │
│ • Patient-Centric Packaging (1 pgs)                                                                 │
│ • Protein Degradation Research (1 pgs)                                                              │
│ • Patient Access Director Insight (1 pgs)                                                           │
│ • Nonprofits and COVID-19 (1 pgs)                                                                   │
│ • Uterine Fibroids Patient Experience (1 pgs)                                                       │
│ • Magnified Series: Linda Scarazzini (1 pgs)                                                        │
│ • Antiviral Expertise for COVID-19 (1 pgs)                                                          │
│ • Precision Medicine Expansion (1 pgs)                                                              │
│ • Value of Walking Down the Aisle (1 pgs)                                                           │
│ • Genome Sequencing Potential (1 pgs)                                                               │
│ • Glaucoma and Eye Health Awareness (1 pgs)                                                         │
│ • BTK Protein Research (1 pgs)                                                                      │
│ • Eye Care Editorial Stories (1 pgs)                                                                │
│ • Medicinal Chemists Against Autoimmune Diseases (1 pgs)                                            │
│ • Blood Cancer Treatment Evolution (1 pgs)                                                          │
│ • AbbVie's R&D Investment Story (1 pgs)                                                             │
│ • Unlocking One Million Genomes (1 pgs)                                                             │
│ • Hepatitis C Research Breakthroughs (1 pgs)                                                        │
│ • Psoriasis Patient Stories (1 pgs)                                                                 │
│ • Aesthetics Editorial Stories (1 pgs)                                                              │
│ • Patient Support Editorial Stories (1 pgs)                                                         │
│ • Partnership Success Stories (1 pgs)                                                               │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Personalized Medicine Challenges (1 pgs)                                                          │
│ • Puerto Rico Health Center Rebuilding (1 pgs)                                                      │
│ • Day in Life Story Template (1 pgs)                                                                │
│ • Neuroscience Stories Template (1 pgs)                                                             │
│ • EEDI Stories Format (1 pgs)                                                                       │
│ • Volunteer and Community Stories Template (1 pgs)                                                  │
│ • Navigating Health Challenges Template (1 pgs)                                                     │
│ • Public Health and Safety Template (1 pgs)                                                         │
│ • Vaccination Hope Template (1 pgs)                                                                 │
│ • Vision and Health Progress Template (1 pgs)                                                       │
│ • Oncology Insights Template (1 pgs)                                                                │
│ • Immunology Stories Template (1 pgs)                                                               │
│ • COVID-19 Lessons Template (1 pgs)                                                                 │
│ • Patient Advocacy and Voices Template (1 pgs)                                                      │
│ • Community School Project Template (1 pgs)                                                         │
│ • Corporate Integration Insights Template (1 pgs)                                                   │
│ • Employee Spotlight Template (1 pgs)                                                               │
│ • Equity in Dermatology Template (1 pgs)                                                            │
│ • Workplace Reimagining Template (1 pgs)                                                            │
│ • Family Benefits and Support Template (1 pgs)                                                      │
│ • Blood Cancer Vision Template (1 pgs)                                                              │
│ • Hepatitis C Elimination Template (1 pgs)                                                          │
│ • Pandemic Hope and Conversations Template (1 pgs)                                                  │
│ • Sustainability and Growth Template (1 pgs)                                                        │
│ • Stroke Recovery and Research Template (1 pgs)                                                     │
│ • Psoriasis Journey Template (1 pgs)                                                                │
│ • Company Impact Reflection Template (1 pgs)                                                        │
│ • Digital Science Lab (1 pgs)                                                                       │
│ • Eye Disease Focus (1 pgs)                                                                         │
│ • AI in Drug Discovery (1 pgs)                                                                      │
│ • Working at AbbVie (1 pgs)                                                                         │
│ • Sustainability Efforts (1 pgs)                                                                    │
│ • Innovation and Action (1 pgs)                                                                     │
│ • COVID-19 Medicine Access (1 pgs)                                                                  │
│ • Support for Cancer Families (1 pgs)                                                               │
│ • Accelerating Cure Discovery (1 pgs)                                                               │
│ • Cancer's Hidden Side (1 pgs)                                                                      │
│ • Ambassadors in Action (1 pgs)                                                                     │
│ • Philanthropy Stories (1 pgs)                                                                      │
│ • Magnified: Nicholas Donoghoe (1 pgs)                                                              │
│ • Healthcare Microsite (1 pgs)                                                                      │
│ • Magnified: Edrice Simmons (1 pgs)                                                                 │
│ • The Arch Tool (1 pgs)                                                                             │
│ • Synthetic Control Arm (1 pgs)                                                                     │
│ • Immunology Frontier (1 pgs)                                                                       │
│ • IBD Care Improvements (1 pgs)                                                                     │
│ • Curiosity in Science (1 pgs)                                                                      │
│ • Cancer Care Transformation (1 pgs)                                                                │
│ • Time is Hours (1 pgs)                                                                             │
│ • Working Parents Community (1 pgs)                                                                 │
│ • Brand Partnerships (1 pgs)                                                                        │
│ • Change from Within (1 pgs)                                                                        │
│ • AbbVie Research Collaborative (1 pgs)                                                             │
│ • Rheumatoid Arthritis Awareness (1 pgs)                                                            │
│ • Innovation Through Health Equity (1 pgs)                                                          │
│ • Virology Research Insights (1 pgs)                                                                │
│ • Parkinson's Disease Advocacy (1 pgs)                                                              │
│ • Mental Health Leadership (1 pgs)                                                                  │
│ • Maternal Health Innovations (1 pgs)                                                               │
│ • Persistence Lab Podcasts (1 pgs)                                                                  │
│ • Cancer Patient Support Drive (1 pgs)                                                              │
│ • Science Stories Overview (1 pgs)                                                                  │
│ • Investigational Drugs Policy (1 pgs)                                                              │
│ • Magnified: Johanna Corbin Feature (1 pgs)                                                         │
│ • Community Service Stories (1 pgs)                                                                 │
│ • Inspiration: Joe's Story (1 pgs)                                                                  │
│ • Understanding Hidradenitis Suppurativa (1 pgs)                                                    │
│ • Predictive Analytics in Research (1 pgs)                                                          │
│ • Profile Stories Archive (1 pgs)                                                                   │
│ • Emotional Impact of Ovarian Cancer (1 pgs)                                                        │
│ • Cubs Brand Partnership (1 pgs)                                                                    │
│ • Parkinson's Community Efforts (1 pgs)                                                             │
│ • Mental Health and Skin Conditions (1 pgs)                                                         │
│ • Value of Education Narrative (1 pgs)                                                              │
│ • Impactful Stories of Little Patients (1 pgs)                                                      │
│ • Corporate Stories Collection (1 pgs)                                                              │
│ • Complexities of Atopic Dermatitis (1 pgs)                                                         │
│ • Decoding Immune System (1 pgs)                                                                    │
│ • Working Parents Caregiver (1 pgs)                                                                 │
│ • Veteran's Mental Health (1 pgs)                                                                   │
│ • Healthcare Elevation (1 pgs)                                                                      │
│ • Medicine Delivery Efficiency (1 pgs)                                                              │
│ • Small Cell Lung Cancer (1 pgs)                                                                    │
│ • Research in Systems (1 pgs)                                                                       │
│ • Drug Shortage Prevention (1 pgs)                                                                  │
│ • Facility Launch (1 pgs)                                                                           │
│ • Living with Dystonia (1 pgs)                                                                      │
│ • Employee Resource Groups (1 pgs)                                                                  │
│ • Genetic Medicine Insights (1 pgs)                                                                 │
│ • 2024 Working Parents (1 pgs)                                                                      │
│ • Technologies in Disease Research (1 pgs)                                                          │
│ • Educational Grants (1 pgs)                                                                        │
│ • Andrew Campbell Profile (1 pgs)                                                                   │
│ • Innovation Areas (1 pgs)                                                                          │
│ • Lab to Life (1 pgs)                                                                               │
│ • Focus Areas (1 pgs)                                                                               │
│ • Partnering Days (1 pgs)                                                                           │
│ • Raymond Votzmeyer Profile (1 pgs)                                                                 │
│ • Our People (1 pgs)                                                                                │
│ • Grant Disclosures (1 pgs)                                                                         │
│ • Eye Care Focus (1 pgs)                                                                            │
│ • Eleni Lagkadinou Profile (1 pgs)                                                                  │
│ • RD Leader Profile - Linda Scarazzini (1 pgs)                                                      │
│ • RD Leader Profile - Wolfram Nothaft (1 pgs)                                                       │
│ • RD Leader Profile - Darin Messina (1 pgs)                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Science in 60 Seconds (1 pgs)                                                                     │
│ • Areas of Innovation - Genomics (1 pgs)                                                            │
│ • Scientific Publications (1 pgs)                                                                   │
│ • RD Leader Profile - Shuhong Zhang (1 pgs)                                                         │
│ • Therapeutic Modalities and Platforms (1 pgs)                                                      │
│ • Focus Area - Neuroscience (1 pgs)                                                                 │
│ • RD Leader Profile - Michael Foley (1 pgs)                                                         │
│ • RD Leader Profile - Primal Kaur (1 pgs)                                                           │
│ • Focus Area - Oncology (1 pgs)                                                                     │
│ • RD Leader Profile - Jonathon Sedgwick (1 pgs)                                                     │
│ • Lab of the Future (1 pgs)                                                                         │
│ • Discovery Files (1 pgs)                                                                           │
│ • Precision Medicine (1 pgs)                                                                        │
│ • Behind the Science (1 pgs)                                                                        │
│ • RD Leader Profile - Philip Hajduk (1 pgs)                                                         │
│ • Focus Area - Aesthetics (1 pgs)                                                                   │
│ • Educational Grants Guide (1 pgs)                                                                  │
│ • Patient-Focused Drug Development (1 pgs)                                                          │
│ • RD Leader Profile - Daejin Abidoye (1 pgs)                                                        │
│ • RD Sites (1 pgs)                                                                                  │
│ • AbbVie Ventures Portfolio (1 pgs)                                                                 │
│ • Clinical Trials Overview (1 pgs)                                                                  │
│ • Other Specialty Areas (1 pgs)                                                                     │
│ • Immunology Research (1 pgs)                                                                       │
│ • Community of Science (1 pgs)                                                                      │
│ • How to Apply for Grants (1 pgs)                                                                   │
│ • Corporate Opportunities (1 pgs)                                                                   │
│ • Patient Assistance Income Criteria (1 pgs)                                                        │
│ • Product Quality and Safety (1 pgs)                                                                │
│ • Commercial Opportunities (1 pgs)                                                                  │
│ • Savings Card Information (1 pgs)                                                                  │
│ • Grant Request Types (1 pgs)                                                                       │
│ • Research and Development Opportunities (1 pgs)                                                    │
│ • General Opportunities (1 pgs)                                                                     │
│ • Investigator Initiated Studies (1 pgs)                                                            │
│ • Online Application Overview (1 pgs)                                                               │
│ • Application FAQs (1 pgs)                                                                          │
│ • Eligibility Criteria (1 pgs)                                                                      │
│ • Available Assistance Programs (1 pgs)                                                             │
│ • Frequently Asked Questions for Assistance (1 pgs)                                                 │
│ • AbbVie Ventures (1 pgs)                                                                           │
│ • Bay Area Opportunities (1 pgs)                                                                    │
│ • AbbVie Pride Page (1 pgs)                                                                         │
│ • Reasonable Accommodations (1 pgs)                                                                 │
│ • Tunisia Office Contact (1 pgs)                                                                    │
│ • Croatia Office Contact (1 pgs)                                                                    │
│ • Algeria Office Contact (1 pgs)                                                                    │
│ • South Africa Contact Center (1 pgs)                                                               │
│ • ESG Resources (1 pgs)                                                                             │
│ • Why AbbVie (1 pgs)                                                                                │
│ • Addressing Barriers Initiative (1 pgs)                                                            │
│ • Asian Leadership Network (1 pgs)                                                                  │
│ • Environmental and Social Governance (1 pgs)                                                       │
│ • Veterans Resource Group (1 pgs)                                                                   │
│ • Internship Opportunities (1 pgs)                                                                  │
│ • Employee Benefits (1 pgs)                                                                         │
│ • Life at AbbVie (1 pgs)                                                                            │
│ • Slovenia Office Contact (1 pgs)                                                                   │
│ • Allergan Aesthetics Opportunities (1 pgs)                                                         │
│ • Student Programs (1 pgs)                                                                          │
│ • Global Locations Directory (1 pgs)                                                                │
│ • Cerevel Collaboration (1 pgs)                                                                     │
│ • Celsius Therapeutics Partnership (1 pgs)                                                          │
│ • Nimble Therapeutics Collaboration (1 pgs)                                                         │
│ • Capstan Therapeutics Collaboration (1 pgs)                                                        │
│ • Women Leaders in Action (1 pgs)                                                                   │
│ • Graduate and Entry-Level Positions (1 pgs)                                                        │
│ • Mitokinin Page (1 pgs)                                                                            │
│ • Immunogen Page (1 pgs)                                                                            │
│ • Equal Employment Opportunity (1 pgs)                                                              │
│ • Innovative Impact Foundation (1 pgs)                                                              │
│ • Operations Opportunities (1 pgs)                                                                  │
│ • Learning and Development (1 pgs)                                                                  │
│ • Workplace Well-being (1 pgs)                                                                      │
│ • Black Business Network (1 pgs)                                                                    │
│ • Employee Resource Groups Overview (1 pgs)                                                         │
│ • Serbia Contact Center (1 pgs)                                                                     │
│ • Human Capital Management (1 pgs)                                                                  │
│ • Ability at AbbVie (1 pgs)                                                                         │
│ • Bosnia and Herzegovina Contact Center (1 pgs)                                                     │
│ • Disaster Relief (1 pgs)                                                                           │
│ • Postdoctoral Program (1 pgs)                                                                      │
│ • Ahora Hispanic Latino Network (1 pgs)                                                             │
│ • Environmental Sustainability (1 pgs)                                                              │
│ • United States Contact Center (1 pgs)                                                              │
│ • Aliada Therapeutics (1 pgs)                                                                       │
│ • Lithuania Contact Center (1 pgs)                                                                  │
│ • Allergan Labeling (1 pgs)                                                                         │
│ • Romania Contact Center (1 pgs)                                                                    │
│ • Estonia Contact Center (1 pgs)                                                                    │
│ • Partnerships Page (1 pgs)                                                                         │
│ • Location Detail Page (1 pgs)                                                                      │
│ • Accessibility Statement (1 pgs)                                                                   │
│ • Location Detail Page (1 pgs)                                                                      │
│ • Location Detail Page (1 pgs)                                                                      │
│ • Contact Us Page (1 pgs)                                                                           │
│ • Location Detail Page (1 pgs)                                                                      │
│ • Community Guidelines (1 pgs)                                                                      │
│ • Patents Information Page (1 pgs)                                                                  │
│ • Impact History Page (1 pgs)                                                                       │
│ • Earnings Reports Page (1 pgs)                                                                     │
│ • Privacy Policy Page (1 pgs)                                                                       │
│ • Privacy Inquiry Page (1 pgs)                                                                      │
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
| tpl_0 | Allergan Overview | Page detailing Allergan's integration and relationship with AbbVie. | https://www.abbvie.com/allergan.html | 1 |
| tpl_1 | Corporate Home Pages | Main pages providing an overview of AbbVie and updates like COVID-19 information. | https://www.abbvie.com/, https://www.abbvie.com/coronavirus.html, https://www.abbvie.com/covid-19crf.html | 3 |
| tpl_2 | Pipeline Insights | Pages focusing on AbbVie's research pipeline and development projects. | https://www.abbvie.com/science/pipeline.html, https://www.abbvie.com/science/pipeline.html?utm_medium=psearch&amp;utm_campaign=corprepppp_2023&amp;utm_source=google&amp;utm_content=igp&amp;utm_term=research-dev&amp;cid=ppc_CV388fdb1654d244169c71e7b4f7ff04c4&amp;gclid=CjwKCAiAmZGrBhAnEiwAo9qHiRTJmfLpf-WzbqgcZlNiwz2UdRnluEZxPLyuGDeX0dpeP5qTxHPTMRoCdLAQAvD_BwE&amp;gclsrc=aw.ds | 2 |
| tpl_3 | Code of Conduct | Content discussing AbbVie's ethical guidelines and operational integrity. | https://www.abbvie.com/who-we-are/operating-with-integrity/abbvies-code-of-conduct.html | 1 |
| tpl_4 | Leadership Profile: Liz Shea | Profile page for Liz Shea, highlighting her role and contributions. | https://www.abbvie.com/who-we-are/our-leaders/liz-shea.html | 1 |
| tpl_5 | Leadership Profile: Alberto Colzi | Profile page for Alberto Colzi detailing his professional background. | https://www.abbvie.com/who-we-are/our-leaders/alberto-colzi.html | 1 |
| tpl_6 | Leadership Profile: Jeffrey Stewart | Profile page for Jeffrey Stewart and his responsibilities. | https://www.abbvie.com/who-we-are/our-leaders/jeffrey-stewart.html | 1 |
| tpl_7 | Leadership Profile: Tracie Haas | Profile page for Tracie Haas. | https://www.abbvie.com/who-we-are/our-leaders/tracie-haas.html | 1 |
| tpl_8 | Leadership Profile: Jason Smith | Profile page for Jason Smith. | https://www.abbvie.com/who-we-are/our-leaders/jason-smith.html | 1 |
| tpl_9 | Leadership Profile: Robert Michael | Profile page for Robert Michael. | https://www.abbvie.com/who-we-are/our-leaders/robert-michael.html | 1 |
| tpl_10 | Join AbbVie | Information page for career opportunities and joining AbbVie. | https://www.abbvie.com/join-us.html | 1 |
| tpl_11 | Transparency in Payments | Details about AbbVie's disclosure practices regarding payments and integrity. | https://www.abbvie.com/who-we-are/operating-with-integrity/transparency-in-payment/allergan-ous-disclosures.html | 1 |
| tpl_12 | Leadership Profile: Nicholas Donoghoe | Profile of Nicholas Donoghoe. | https://www.abbvie.com/who-we-are/our-leaders/nicholas-donoghoe.html | 1 |
| tpl_13 | Leadership Profile: Jerome Bouyer | Profile page for Jerome Bouyer. | https://www.abbvie.com/who-we-are/our-leaders/jerome-bouyer.html | 1 |
| tpl_14 | Contact Center | Page providing contact information and customer support details. | https://www.abbvie.com/contact-center.html | 1 |
| tpl_15 | Leadership Profile: Roopal Thakkar | Profile page for Roopal Thakkar. | https://www.abbvie.com/who-we-are/our-leaders/roopal-thakkar.html | 1 |
| tpl_16 | Equity and Inclusion Principles | Page discussing AbbVie's commitment to diversity and equity. | https://www.abbvie.com/who-we-are/our-principles/equity-equality-inclusion-diversity.html | 1 |
| tpl_17 | Partnering in Science | Information page about scientific collaborations and partnerships. | https://www.abbvie.com/science/partner-with-us.html | 1 |
| tpl_18 | Protecting Human Rights | Page discussing AbbVie's policies on human rights and workplace safety. | https://www.abbvie.com/who-we-are/operating-with-integrity/protecting-human-rights-and-workplace-safety.html | 1 |
| tpl_19 | Leadership Profile: Nisha Patel Burns | Profile page for Nisha Patel Burns. | https://www.abbvie.com/who-we-are/our-leaders/nisha-patel-burns.html | 1 |
| tpl_20 | Science Overview | Main science pages highlighting AbbVie's research focus and big bets in science. | https://www.abbvie.com/science.html, https://www.abbvie.com/science/the-case-for-big-bets.html | 2 |
| tpl_21 | Leadership Profile: Scott Reents | Profile of Scott Reents. | https://www.abbvie.com/who-we-are/our-leaders/scott-reents.html | 1 |
| tpl_22 | Positions and Views | Page outlining AbbVie's stances on various principles and policies. | https://www.abbvie.com/who-we-are/our-principles/positions-views.html | 1 |
| tpl_23 | Leadership Profile: Jag Dosanjh | Profile page for Jag Dosanjh. | https://www.abbvie.com/who-we-are/our-leaders/jag-dosanjh.html | 1 |
| tpl_24 | Leadership Profile: Perry Siatis | Profile page for Perry Siatis. | https://www.abbvie.com/who-we-are/our-leaders/perry-siatis.html | 1 |
| tpl_25 | Leadership Profile | Page providing detailed information about individual leadership members at Abbvie. | https://www.abbvie.com/who-we-are/our-leaders/azita-saleki-gerhardt.html | 1 |
| tpl_26 | Principles Overview | Page highlighting Abbvie's guiding principles and values. | https://www.abbvie.com/who-we-are/our-principles.html | 1 |
| tpl_27 | Transparency Inquiry | Page for inquiries related to transparency in payment processes. | https://www.abbvie.com/who-we-are/operating-with-integrity/transparency-in-payment/abbvie-inquiry.html | 1 |
| tpl_28 | Accessibility Statement | Page detailing Abbvie's commitment to accessibility and related policies. | https://www.abbvie.com/accessibility-statement.html | 1 |
| tpl_29 | Leadership Profile | Page providing detailed information about individual leadership members at Abbvie. | https://www.abbvie.com/who-we-are/our-leaders/dave-purdue.html | 1 |
| tpl_30 | Leadership Profile | Page providing detailed information about individual leadership members at Abbvie. | https://www.abbvie.com/who-we-are/our-leaders/linda-ray.html | 1 |
| tpl_31 | Magnified Story | Feature story showcasing individual contributions by Abbvie personnel. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-jonathon-sedgwick.html | 1 |
| tpl_32 | Key Facts Overview | Page summarizing important information about Abbvie. | https://www.abbvie.com/who-we-are/key-facts.html | 1 |
| tpl_33 | Patients Information | General page providing information and resources for patients. | https://www.abbvie.com/patients.html | 1 |
| tpl_34 | Leadership Profile | Page providing detailed information about individual leadership members at Abbvie. | https://www.abbvie.com/who-we-are/our-leaders/wulff-erik-von-borcke.html | 1 |
| tpl_35 | Terms of Use | Page detailing the terms of use and legal policies of Abbvie's websites. | https://www.abbvie.com/terms-of-use.html, https://www.abbvie.com/termsofuse.html | 2 |
| tpl_36 | Who We Are Overview | Page summarizing Abbvie's identity, mission, and values. | https://www.abbvie.com/who-we-are.html | 1 |
| tpl_37 | Inside Dream Initiative | Feature story exploring the impact of the Dream Initiative. | https://www.abbvie.com/who-we-are/our-stories/inside-dream-initiative.html | 1 |
| tpl_38 | Living with Illness | Story highlighting the experiences of individuals dealing with chronic illnesses. | https://www.abbvie.com/who-we-are/our-stories/living-with-an-illness.html | 1 |
| tpl_39 | Leadership Profile | Page providing detailed information about individual leadership members at Abbvie. | https://www.abbvie.com/who-we-are/our-leaders/latif-akintade.html | 1 |
| tpl_40 | Patient Support Resources | Page offering assistance and resources for patient support. | https://www.abbvie.com/patients/patient-support.html | 1 |
| tpl_41 | Leadership Profile | Page providing detailed information about individual leadership members at Abbvie. | https://www.abbvie.com/who-we-are/our-leaders/timothy-richmond.html | 1 |
| tpl_42 | Leadership Profile | Page providing detailed information about individual leadership members at Abbvie. | https://www.abbvie.com/who-we-are/our-leaders/demetris-crum.html | 1 |
| tpl_43 | Supplier Resources | Page detailing resources and guidelines for suppliers. | https://www.abbvie.com/who-we-are/operating-with-integrity/responsible-supply-chain/supplier-resources.html | 1 |
| tpl_44 | Medicine Discovery Insights | Feature story explaining the processes involved in discovering new medicines. | https://www.abbvie.com/who-we-are/our-stories/what-does-it-take-to-discover-a-new-medicine.html | 1 |
| tpl_45 | Ethical Research Commitment | Page outlining Abbvie's commitment to ethical research practices, including animal studies. | https://www.abbvie.com/who-we-are/our-principles/positions-views/our-commitment-to-ethical-and-responsible-use-of-animals-in-research.html | 1 |
| tpl_46 | Sustainability Overview | Page detailing Abbvie's efforts in sustainability and environmental responsibility. | https://www.abbvie.com/sustainability.html | 1 |
| tpl_47 | Magnified Story | Feature story showcasing individual contributions by Abbvie personnel. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-sean-mcewen.html | 1 |
| tpl_48 | Leadership Profiles | Page providing comprehensive profiles of Abbvie's leadership team. | https://www.abbvie.com/who-we-are/our-leaders.html, https://www.abbvie.com/who-we-are/our-leaders/thomas-hudson.html, https://www.abbvie.com/who-we-are/our-leaders/sanjay-narayan.html | 3 |
| tpl_49 | Magnified Story | Feature story showcasing individual contributions by Abbvie personnel. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-matt-widman.html | 1 |
| tpl_50 | Leadership Profile Page | This template is used for leader profiles on the AbbVie website, featuring information about individual leaders and their roles. | https://www.abbvie.com/who-we-are/our-leaders/nicole-mowad-nassar.html | 1 |
| tpl_51 | FAQ on Payments Transparency | This page addresses frequently asked questions regarding physician and other payment transparency practices. | https://www.abbvie.com/who-we-are/operating-with-integrity/transparency-in-payment/frequently-asked-questions-physician-and-other-payments.html | 1 |
| tpl_52 | Responsible Supply Chain Overview | Details AbbVie's approach to maintaining a responsible and ethical supply chain. | https://www.abbvie.com/who-we-are/operating-with-integrity/responsible-supply-chain.html | 1 |
| tpl_53 | Scientific Innovation Story | Showcases efforts by AbbVie to innovate in cancer treatment and other scientific endeavors. | https://www.abbvie.com/who-we-are/our-stories/breaking-the-rules-of-science-to-treat-cancer.html | 1 |
| tpl_54 | Equity and Inclusion Impact | Details AbbVie's principles and initiatives to promote equity, inclusion, and diversity. | https://www.abbvie.com/who-we-are/our-principles/equity-equality-inclusion-diversity/impact-through-inclusion.html | 1 |
| tpl_55 | Operating with Integrity Overview | Describes AbbVie's commitment to integrity in their operations. | https://www.abbvie.com/who-we-are/operating-with-integrity.html | 1 |
| tpl_56 | Website Sitemap | Provides a structured overview of the AbbVie website's navigation and pages. | https://www.abbvie.com/site-map.html | 1 |
| tpl_57 | Payment Transparency Overview | Explains AbbVie's practices related to payment transparency and ethical dealings. | https://www.abbvie.com/who-we-are/operating-with-integrity/transparency-in-payment.html | 1 |
| tpl_58 | Our Stories Landing Page | Serves as a hub for various stories and articles related to AbbVie's impact and initiatives. | https://www.abbvie.com/who-we-are/our-stories.html | 1 |
| tpl_59 | Policies and Disclosures | Lists AbbVie's policies and disclosures related to their business practices. | https://www.abbvie.com/who-we-are/policies-disclosures.html | 1 |
| tpl_60 | Product Information Page | Provides detailed information about AbbVie's products for patients. | https://www.abbvie.com/patients/products.html | 1 |
| tpl_61 | Engineer Diversity Profile | Highlights the story of an engineer promoting diversity within manufacturing at AbbVie. | https://www.abbvie.com/who-we-are/our-stories/day-in-life-meet-engineer-promoting-diversity-within-manufacturing.html | 1 |
| tpl_62 | Convergence of Minds Story | Explores collaborative efforts and data-driven innovations at AbbVie. | https://www.abbvie.com/who-we-are/our-stories/stronger-together-convergence-minds-and-data.html | 1 |
| tpl_63 | Nonprofit Partnership Impact | Details the impact of AbbVie's partnerships with nonprofit organizations. | https://www.abbvie.com/who-we-are/our-stories/day-in-the-life-creating-impact-with-nonprofit-partners.html | 1 |
| tpl_64 | Magnified Series Feature | Part of AbbVie's Magnified series, showcasing individuals' contributions to healthcare. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-darin-messina.html | 1 |
| tpl_65 | AI Innovation Story | Discusses improvements in artificial intelligence at AbbVie through human ingenuity. | https://www.abbvie.com/who-we-are/our-stories/chembeads-improving-artificial-intelligence-through-human-ingenuity.html | 1 |
| tpl_66 | Eye Disease Research Focus | Explains why AbbVie focuses on challenging diseases in eye care. | https://www.abbvie.com/who-we-are/our-stories/a-history-discovery-why-we-focus-on-eye-cares-toughest-diseases.html | 1 |
| tpl_67 | Environmental Sustainability Efforts | Explores AbbVie's environmental sustainability initiatives. | https://www.abbvie.com/who-we-are/our-stories/starting-with-a-spark-an-inside-look-at-environmental-sustainability.html | 1 |
| tpl_68 | Patient Perseverance Story | Highlights stories of resilience and determination among AbbVie patients. | https://www.abbvie.com/who-we-are/our-stories/they-wont-back-down.html | 1 |
| tpl_69 | Green Chemistry Innovations | Details efforts to create cleaner and faster chemical reactions at AbbVie. | https://www.abbvie.com/who-we-are/our-stories/green-chemistry-cleaner-faster-chemical-reactions.html | 1 |
| tpl_70 | Human Factors Engineering Insight | Describes the role of human factors engineers in simplifying complex systems. | https://www.abbvie.com/who-we-are/our-stories/make-complicated-simple-inside-world-human-factors-engineers.html | 1 |
| tpl_71 | Real-World Data Utilization | Discusses how real-world data is used to improve drug treatment outcomes. | https://www.abbvie.com/who-we-are/our-stories/real-world-data-rounds-out-value-picture-drugs.html | 1 |
| tpl_72 | Alzheimer's Disease Challenges | Explores the challenges and uncertainties faced by patients with Alzheimer's disease. | https://www.abbvie.com/who-we-are/our-stories/living-with-unknowns-alzheimers-disease.html | 1 |
| tpl_73 | IBD Patient Story | Highlights personal stories of perseverance and love in the context of IBD treatment. | https://www.abbvie.com/who-we-are/our-stories/the-power-love-in-ibd.html | 1 |
| tpl_74 | Data Science Impact | Discusses the role of data science in advancing healthcare innovations at AbbVie. | https://www.abbvie.com/who-we-are/our-stories/everyones-talking-about-data-science.html | 1 |
| tpl_75 | Migraine Analysis Story | A page detailing the mathematical and scientific analysis of migraines. | https://www.abbvie.com/who-we-are/our-stories/the-math-of-migraine.html | 1 |
| tpl_76 | Patient-Centric Packaging | Explores efforts to improve patient-centric packaging solutions. | https://www.abbvie.com/who-we-are/our-stories/striving-for-patient-centricity-down-to-the-packaging.html | 1 |
| tpl_77 | Protein Degradation Research | Discusses advancements in protein degradation techniques for medical applications. | https://www.abbvie.com/who-we-are/our-stories/unlocking-the-next-level-of-protein-degradation.html | 1 |
| tpl_78 | Patient Access Director Insight | Highlights the role of a director in facilitating patient access to healthcare. | https://www.abbvie.com/who-we-are/our-stories/day-in-life-meet-director-clearing-path-for-patient-access.html | 1 |
| tpl_79 | Nonprofits and COVID-19 | Shares stories of nonprofit organizations rising to challenges during the COVID-19 pandemic. | https://www.abbvie.com/who-we-are/our-stories/the-hardest-hit-how-nonprofits-rise-to-challenge-covid-19.html | 1 |
| tpl_80 | Uterine Fibroids Patient Experience | A doctor’s perspective on experiencing and treating uterine fibroids. | https://www.abbvie.com/who-we-are/our-stories/how-uterine-fibroids-feel-to-patient-who-is-also-doctor.html | 1 |
| tpl_81 | Magnified Series: Linda Scarazzini | Features Linda Scarazzini in the Magnified series, discussing health topics. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-linda-scarazzini.html | 1 |
| tpl_82 | Antiviral Expertise for COVID-19 | Describes AbbVie's contributions to antiviral research in the fight against COVID-19. | https://www.abbvie.com/who-we-are/our-stories/how-abbvie-is-bringing-antiviral-expertise-to-covid-19-battle.html | 1 |
| tpl_83 | Precision Medicine Expansion | Explores the application of precision medicine beyond oncology. | https://www.abbvie.com/who-we-are/our-stories/precision-medicine-its-not-just-for-oncology-anymore.html | 1 |
| tpl_84 | Value of Walking Down the Aisle | Analyzes the emotional and social value of wedding traditions. | https://www.abbvie.com/who-we-are/our-stories/chasing-the-value-of-a-walk-down-the-aisle.html | 1 |
| tpl_85 | Genome Sequencing Potential | Unlocking potential through whole genome sequencing advancements. | https://www.abbvie.com/who-we-are/our-stories/the-blueprint-of-you-unlocking-potential-whole-genome-sequencing.html | 1 |
| tpl_86 | Glaucoma and Eye Health Awareness | Highlights efforts to improve understanding and treatment of glaucoma. | https://www.abbvie.com/who-we-are/our-stories/shining-light-on-glaucoma-and-eye-health.html | 1 |
| tpl_87 | BTK Protein Research | Examines the role of BTK protein in medical research and applications. | https://www.abbvie.com/who-we-are/our-stories/btk-protein-good-bad-and-ugly.html | 1 |
| tpl_88 | Eye Care Editorial Stories | A collection of editorial stories focusing on eye care. | https://www.abbvie.com/who-we-are/our-stories/eye-care-stories.html | 1 |
| tpl_89 | Medicinal Chemists Against Autoimmune Diseases | Highlights the creative approaches of medicinal chemists in combating autoimmune diseases. | https://www.abbvie.com/who-we-are/our-stories/how-medicinal-chemists-are-creating-new-weapons-against-autoimmune-diseases.html | 1 |
| tpl_90 | Blood Cancer Treatment Evolution | Discusses the advancements in blood cancer treatment methods over time. | https://www.abbvie.com/who-we-are/our-stories/then-and-now-renaissance-in-blood-cancer-treatment.html | 1 |
| tpl_91 | AbbVie's R&D Investment Story | Explores the impact and background of AbbVie's significant R&D investment. | https://www.abbvie.com/who-we-are/our-stories/the-story-behind-our-50-billion-rd-investment.html | 1 |
| tpl_92 | Unlocking One Million Genomes | Analyzes the implications and potential of genome unlocking research. | https://www.abbvie.com/who-we-are/our-stories/can-unlocking-one-million-genomes.html | 1 |
| tpl_93 | Hepatitis C Research Breakthroughs | Shares the journey and breakthroughs in combating Hepatitis C. | https://www.abbvie.com/who-we-are/our-stories/hepatitis-c-mysterious-virus-that-met-its-match.html | 1 |
| tpl_94 | Psoriasis Patient Stories | Insights into the lives of patients living with psoriasis. | https://www.abbvie.com/who-we-are/our-stories/trapped-in-your-own-skin.html | 1 |
| tpl_95 | Aesthetics Editorial Stories | A collection of stories centered around aesthetics and beauty care. | https://www.abbvie.com/who-we-are/our-stories/aesthetics-stories.html | 1 |
| tpl_96 | Patient Support Editorial Stories | Stories highlighting patient support initiatives and resources. | https://www.abbvie.com/who-we-are/our-stories/patient-support-stories.html | 1 |
| tpl_97 | Partnership Success Stories | Explores successful partnerships that have made a positive impact. | https://www.abbvie.com/who-we-are/our-stories/partnerships-stories.html | 1 |
| tpl_98 | Personalized Medicine Challenges | Discusses the difficulties in standardizing medicine for diverse needs. | https://www.abbvie.com/who-we-are/our-stories/why-isnt-medicine-one-size-fits-all.html | 1 |
| tpl_99 | Puerto Rico Health Center Rebuilding | Details efforts to rebuild community health centers in Puerto Rico. | https://www.abbvie.com/who-we-are/our-stories/rebuilding-puerto-rico-one-community-health-center-at-a-time.html | 1 |
| tpl_100 | Day in Life Story Template | Template for articles detailing individual stories and experiences. | https://www.abbvie.com/who-we-are/our-stories/day-in-life-government-affairs-director-educates-and-empowers.html | 1 |
| tpl_101 | Neuroscience Stories Template | Template for articles related to neuroscience and its advancements. | https://www.abbvie.com/who-we-are/our-stories/neuroscience-stories.html | 1 |
| tpl_102 | EEDI Stories Format | Template covering topics on equity, diversity, and inclusion. | https://www.abbvie.com/who-we-are/our-stories/eedi-stories.html | 1 |
| tpl_103 | Volunteer and Community Stories Template | Focused template for articles about community service and volunteerism. | https://www.abbvie.com/who-we-are/our-stories/abbvie-volunteers-return-to-serving.html | 1 |
| tpl_104 | Navigating Health Challenges Template | Template for personal health stories and challenges. | https://www.abbvie.com/who-we-are/our-stories/navigating-ulcerative-colitis-as-a-child.html | 1 |
| tpl_105 | Public Health and Safety Template | Template for articles addressing public health initiatives. | https://www.abbvie.com/who-we-are/our-stories/advancing-a-public-health-approach-to-patient-safety.html | 1 |
| tpl_106 | Vaccination Hope Template | Template showcasing stories about vaccination programs and their impact. | https://www.abbvie.com/who-we-are/our-stories/injecting-hope-one-vaccine-at-a-time.html | 1 |
| tpl_107 | Vision and Health Progress Template | Template focused on vision health and progress in related fields. | https://www.abbvie.com/who-we-are/our-stories/a-journey-of-sight-progress.html | 1 |
| tpl_108 | Oncology Insights Template | Template for articles related to oncology advancements. | https://www.abbvie.com/who-we-are/our-stories/oncology-stories.html | 1 |
| tpl_109 | Immunology Stories Template | Template for articles about immunology and patient stories. | https://www.abbvie.com/who-we-are/our-stories/immunology-stories.html | 1 |
| tpl_110 | COVID-19 Lessons Template | Template discussing lessons and insights gained during the COVID-19 pandemic. | https://www.abbvie.com/who-we-are/our-stories/connecting-patients-with-care-3-lessons-learned-during-covid-19.html | 1 |
| tpl_111 | Patient Advocacy and Voices Template | Template for stories highlighting patient advocacy and contributions. | https://www.abbvie.com/who-we-are/our-stories/how-patient-voices-are-changing-medicine.html | 1 |
| tpl_112 | Community School Project Template | Template for stories about community projects and educational advancements. | https://www.abbvie.com/who-we-are/our-stories/abbvie-rebuilds-north-chicagos-middle-school-inspiring-students-to-reach-higher.html | 1 |
| tpl_113 | Corporate Integration Insights Template | Template analyzing corporate integration processes and their outcomes. | https://www.abbvie.com/who-we-are/our-stories/three-factors-that-drove-transformational-integration-abbvie-allergan.html | 1 |
| tpl_114 | Employee Spotlight Template | Template for highlighting individual contributions and achievements within the company. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-shuhong-zhang.html | 1 |
| tpl_115 | Equity in Dermatology Template | Template addressing equity and inclusion within dermatology practices. | https://www.abbvie.com/who-we-are/our-stories/more-than-skin-deep-3-lessons-for-expanding-equity-in-dermatology.html | 1 |
| tpl_116 | Workplace Reimagining Template | Template for articles discussing workplace innovations and health accommodations. | https://www.abbvie.com/who-we-are/our-stories/making-it-migraine-friendly-why-were-reimagining-workplace.html | 1 |
| tpl_117 | Family Benefits and Support Template | Template detailing family benefits and support initiatives by the company. | https://www.abbvie.com/who-we-are/our-stories/putting-our-people-first-abbvies-family-benefits.html | 1 |
| tpl_118 | Blood Cancer Vision Template | Template for articles focusing on vision and advancements in blood cancer treatments. | https://www.abbvie.com/who-we-are/our-stories/discovery-files-vision-for-blood-cancer-patients.html | 1 |
| tpl_119 | Hepatitis C Elimination Template | Template for stories about efforts to eradicate Hepatitis C within confined communities. | https://www.abbvie.com/who-we-are/our-stories/going-inside-prison-walls-to-help-eliminate-hepatitis-c.html | 1 |
| tpl_120 | Pandemic Hope and Conversations Template | Template for articles on hope and patient conversations during the pandemic. | https://www.abbvie.com/who-we-are/our-stories/finding-hope-in-a-pandemic--a-conversation-with-two-hepatitis-c-.html | 1 |
| tpl_121 | Sustainability and Growth Template | Template discussing sustainable growth and science-based targets. | https://www.abbvie.com/who-we-are/our-stories/why-delivering-science-based-targets-are-key-to-sustainable-grow.html | 1 |
| tpl_122 | Stroke Recovery and Research Template | Template for articles on stroke recovery and ongoing research. | https://www.abbvie.com/who-we-are/our-stories/life-after-stroke-living-with-and-researching-spasticity.html | 1 |
| tpl_123 | Psoriasis Journey Template | Template for lifelong journey and lessons learned from managing psoriasis. | https://www.abbvie.com/who-we-are/our-stories/lessons-from-a-lifelong-journey-with-psoriasis.html | 1 |
| tpl_124 | Company Impact Reflection Template | Template reflecting on company impact over a significant period. | https://www.abbvie.com/who-we-are/our-stories/voices-abbvie-reflecting-on-decade-impact.html | 1 |
| tpl_125 | Digital Science Lab | Page showcasing AbbVie's digital science initiatives and innovations. | https://www.abbvie.com/who-we-are/our-stories/digital-science-lab.html | 1 |
| tpl_126 | Eye Disease Focus | Information about AbbVie's approach to eye diseases caused by diabetes. | https://www.abbvie.com/who-we-are/our-stories/sharpening-focus-on-eye-diseases-caused-by-diabetes.html | 1 |
| tpl_127 | AI in Drug Discovery | Exploration of how AI is utilized in drug development at AbbVie. | https://www.abbvie.com/who-we-are/our-stories/three-ways-ai-is-changing-drug-discovery-at-abbvie.html | 1 |
| tpl_128 | Working at AbbVie | Stories about employee experiences at AbbVie. | https://www.abbvie.com/who-we-are/our-stories/working-at-abbvie-stories.html | 1 |
| tpl_129 | Sustainability Efforts | Details on AbbVie's sustainability practices and initiatives. | https://www.abbvie.com/who-we-are/our-stories/sustainability-stories.html | 1 |
| tpl_130 | Innovation and Action | AbbVie's strategy for sustainable growth through innovation. | https://www.abbvie.com/who-we-are/our-stories/growing-sustainably-through-innovation-how-abbvie-takes-action.html | 1 |
| tpl_131 | COVID-19 Medicine Access | Ensuring global access to medicines during the COVID-19 pandemic. | https://www.abbvie.com/who-we-are/our-stories/ensuring-patients-around-world-get-medicines-during-covid-19.html | 1 |
| tpl_132 | Support for Cancer Families | AbbVie's efforts to support childhood cancer patients and their families. | https://www.abbvie.com/who-we-are/our-stories/childhood-cancer-patients-and-their-families-find-a-home-away-from-home.html | 1 |
| tpl_133 | Accelerating Cure Discovery | Focus on faster cures through advanced methodologies. | https://www.abbvie.com/who-we-are/our-stories/can-we-find-cures-faster.html | 1 |
| tpl_134 | Cancer's Hidden Side | Exploring lesser-known aspects and impacts of cancer. | https://www.abbvie.com/who-we-are/our-stories/navigating-the-hidden-side-of-cancer.html | 1 |
| tpl_135 | Ambassadors in Action | Highlighting AbbVie representatives and their impactful work. | https://www.abbvie.com/who-we-are/our-stories/ambassadors-in-action.html | 1 |
| tpl_136 | Philanthropy Stories | AbbVie's philanthropic initiatives and community engagement. | https://www.abbvie.com/who-we-are/our-stories/philanthropy-stories.html | 1 |
| tpl_137 | Magnified: Nicholas Donoghoe | Profile on Nicholas Donoghoe as part of AbbVie's Magnified series. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-nicholas-donoghoe.html | 1 |
| tpl_138 | Healthcare Microsite | Introduction of a new healthcare microsite in Chicago. | https://www.abbvie.com/who-we-are/our-stories/new-microsite-clinic-brings-healthcare-to-chicago-southwest-side.html | 1 |
| tpl_139 | Magnified: Edrice Simmons | Profile on Edrice Simmons featured in AbbVie's Magnified series. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-edrice-simmons.html | 1 |
| tpl_140 | The Arch Tool | About a time-saving tool developed for researchers at AbbVie. | https://www.abbvie.com/who-we-are/our-stories/meet-the-arch-a-time-saving-tool-for-researchers-focused-on-finding-cures.html | 1 |
| tpl_141 | Synthetic Control Arm | Efforts to reduce placebos in clinical trials. | https://www.abbvie.com/who-we-are/our-stories/synthetic-control-arm-end-placebos.html | 1 |
| tpl_142 | Immunology Frontier | AbbVie's advancements in immunology research. | https://www.abbvie.com/who-we-are/our-stories/immunologys-next-frontier.html | 1 |
| tpl_143 | IBD Care Improvements | Using real-world evidence to enhance IBD care. | https://www.abbvie.com/who-we-are/our-stories/real-world-evidence-uncovers-gaps-in-IBD-care.html | 1 |
| tpl_144 | Curiosity in Science | Advice from a scientist-physician-robot builder on curiosity. | https://www.abbvie.com/who-we-are/our-stories/advice-from-scientist-turned-physician-turned-robot-builder-be-curious.html | 1 |
| tpl_145 | Cancer Care Transformation | Innovative approaches to cancer care by AbbVie. | https://www.abbvie.com/who-we-are/our-stories/transforming-cancer-care-from-the-inside-out.html | 1 |
| tpl_146 | Time is Hours | Story emphasizing the importance of timely actions. | https://www.abbvie.com/who-we-are/our-stories/time-is-hours.html | 1 |
| tpl_147 | Working Parents Community | Support programs for working parents at AbbVie. | https://www.abbvie.com/who-we-are/our-stories/working-parents-2023-finding-comfort-in-community.html | 1 |
| tpl_148 | Brand Partnerships | Overview of AbbVie's brand partnership initiatives. | https://www.abbvie.com/who-we-are/brand-partnerships.html | 1 |
| tpl_149 | Change from Within | Exploring internal transformations at AbbVie for better impact. | https://www.abbvie.com/who-we-are/our-stories/change-from-within.html | 1 |
| tpl_150 | AbbVie Research Collaborative | Page highlighting collaborative research efforts by AbbVie in scientific fields. | https://www.abbvie.com/who-we-are/our-stories/abbvie-research-collaborative.html | 1 |
| tpl_151 | Rheumatoid Arthritis Awareness | Content focused on the urgency of addressing rheumatoid arthritis. | https://www.abbvie.com/who-we-are/our-stories/why-you-cant-wait-with-rheumatoid-arthritis.html | 1 |
| tpl_152 | Innovation Through Health Equity | Page showcasing AbbVie's initiatives for health equity. | https://www.abbvie.com/who-we-are/our-stories/empowering-innovation-through-the-abbvie-foundation-health-equit.html | 1 |
| tpl_153 | Virology Research Insights | Insights and research stories related to virology. | https://www.abbvie.com/who-we-are/our-stories/virology-stories.html | 1 |
| tpl_154 | Parkinson's Disease Advocacy | Narratives and initiatives supporting Parkinson's disease understanding and treatment. | https://www.abbvie.com/who-we-are/our-stories/two-lives-converging-in-the-fight-against-parkinsons.html | 1 |
| tpl_155 | Mental Health Leadership | Articles and efforts reflecting AbbVie's leadership in mental health. | https://www.abbvie.com/who-we-are/our-stories/a-legacy-of-leadership-in-mental-health.html | 1 |
| tpl_156 | Maternal Health Innovations | Innovative approaches to improving maternal health outcomes. | https://www.abbvie.com/who-we-are/our-stories/an-innovative-approach-to-improve-maternal-health.html | 1 |
| tpl_157 | Persistence Lab Podcasts | Dedicated podcast series by AbbVie exploring persistence in healthcare. | https://www.abbvie.com/who-we-are/our-stories/the-persistence-lab-podcasts.html | 1 |
| tpl_158 | Cancer Patient Support Drive | Narrative focusing on efforts to extend quality time for cancer patients. | https://www.abbvie.com/who-we-are/our-stories/not-good-enough-behind-the-drive-to-give-cancer-patients-more-time.html | 1 |
| tpl_159 | Science Stories Overview | Collection of stories showcasing scientific achievements and research. | https://www.abbvie.com/who-we-are/our-stories/science-stories.html | 1 |
| tpl_160 | Investigational Drugs Policy | Details on AbbVie's policy regarding access to investigational drugs. | https://www.abbvie.com/who-we-are/access-to-investigational-drugs-policy.html | 1 |
| tpl_161 | Magnified: Johanna Corbin Feature | Profile piece featuring Johanna Corbin and her contributions. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-johanna-corbin.html | 1 |
| tpl_162 | Community Service Stories | Highlighting AbbVie's engagement in serving communities. | https://www.abbvie.com/who-we-are/our-stories/serving-communities-stories.html | 1 |
| tpl_163 | Inspiration: Joe's Story | Personal narrative showcasing resilience and inspiration. | https://www.abbvie.com/who-we-are/our-stories/real-people-real-inspiration-joes-story.html | 1 |
| tpl_164 | Understanding Hidradenitis Suppurativa | Educational content about the skin condition hidradenitis suppurativa. | https://www.abbvie.com/who-we-are/our-stories/shedding-light-upon-a-misunderstood-skin-condition-hidradenitis.html | 1 |
| tpl_165 | Predictive Analytics in Research | Exploration of molecular behavior charts and predictive analytics in research. | https://www.abbvie.com/who-we-are/our-stories/a-molecular-behavior-chart-speeding-up-research-with-predictive-analytics.html | 1 |
| tpl_166 | Profile Stories Archive | Compilation of various profiles and stories highlighting AbbVie associates. | https://www.abbvie.com/who-we-are/our-stories/profile-stories.html | 1 |
| tpl_167 | Emotional Impact of Ovarian Cancer | Exploration of emotional challenges faced by ovarian cancer patients. | https://www.abbvie.com/who-we-are/our-stories/resilient-reality-the-emotional-toll-of-ovarian-cancer.html | 1 |
| tpl_168 | Cubs Brand Partnership | Details and narratives on AbbVie's partnership with the Cubs organization. | https://www.abbvie.com/who-we-are/brand-partnerships/cubs.html | 1 |
| tpl_169 | Parkinson's Community Efforts | Focus on the Parkinson's disease community shaping future healthcare solutions. | https://www.abbvie.com/who-we-are/our-stories/how-the-parkinsons-disease-community-is-shaping-the-future.html | 1 |
| tpl_170 | Mental Health and Skin Conditions | Effects of chronic skin disease on mental health. | https://www.abbvie.com/who-we-are/our-stories/recognizing-the-mental-health-impact-of-chronic-skin-disease.html | 1 |
| tpl_171 | Value of Education Narrative | Stories showcasing the transformative impact of education. | https://www.abbvie.com/who-we-are/our-stories/the-value-of-education-from-a-dim-reality-to-a-bright-future.html | 1 |
| tpl_172 | Impactful Stories of Little Patients | Narratives highlighting the significant impact on pediatric healthcare. | https://www.abbvie.com/who-we-are/our-stories/little-patients-big-impact.html | 1 |
| tpl_173 | Corporate Stories Collection | Compilation of stories reflecting AbbVie's corporate values and actions. | https://www.abbvie.com/who-we-are/our-stories/company-stories.html | 1 |
| tpl_174 | Complexities of Atopic Dermatitis | Educational pieces breaking down atopic dermatitis complexities. | https://www.abbvie.com/who-we-are/our-stories/much-more-than-itchy-skin-breaking-down-complexities-atopic-dermatitis.html | 1 |
| tpl_175 | Decoding Immune System | Insights into new medicine discovery. | https://www.abbvie.com/who-we-are/our-stories/decoding-immune-systems-secrets-inside-the-discovery-of-a-new-medicine.html | 1 |
| tpl_176 | Working Parents Caregiver | Celebrating contributions of caregivers. | https://www.abbvie.com/who-we-are/our-stories/celebrating-abbvies-2025-working-parents-caregivers.html | 1 |
| tpl_177 | Veteran's Mental Health | Commitment to mental health research. | https://www.abbvie.com/who-we-are/our-stories/one-veterans-journey-and-abbvies-commitment-to-mental-health-research.html | 1 |
| tpl_178 | Healthcare Elevation | Improving healthcare accessibility. | https://www.abbvie.com/who-we-are/our-stories/elevating-health-care-for-all.html | 1 |
| tpl_179 | Medicine Delivery Efficiency | Innovative approaches to faster treatments. | https://www.abbvie.com/who-we-are/our-stories/5-ways-abbvie-work-to-deliver-medicines-in-half-the-time.html | 1 |
| tpl_180 | Small Cell Lung Cancer | Challenges in treating lung cancer. | https://www.abbvie.com/who-we-are/our-stories/five-reasons-why-small-cell-lung-cancer-is-tough-to-treat.html | 1 |
| tpl_181 | Research in Systems | Studies in chaotic system modeling. | https://www.abbvie.com/who-we-are/our-stories/specialized-research-in-chaotic-systems-sparcs.html | 1 |
| tpl_182 | Drug Shortage Prevention | Operations ensuring medicine availability. | https://www.abbvie.com/who-we-are/our-stories/how-abbvies-integrated-operations-help-prevent-drug-shortages.html | 1 |
| tpl_183 | Facility Launch | Opening new research locations. | https://www.abbvie.com/who-we-are/our-stories/ready-set-launch-abbvie-opens-new-facility-in-the-bay-area.html | 1 |
| tpl_184 | Living with Dystonia | Impact analysis of cervical dystonia. | https://www.abbvie.com/who-we-are/our-stories/more-than-a-stiff-neck-the-impact-of-living-with-cervical-dyston.html | 1 |
| tpl_185 | Employee Resource Groups | Their role in employee well-being. | https://www.abbvie.com/who-we-are/our-stories/how-employee-resource-groups-create-meaningful-impact-at-abbvie.html | 1 |
| tpl_186 | Genetic Medicine Insights | Research advancements in genetic treatments. | https://www.abbvie.com/who-we-are/our-stories/expert-insights-the-promise-of-genetic-medicine-and-abbvies-role-in-research.html | 1 |
| tpl_187 | 2024 Working Parents | Finding purpose in challenging times. | https://www.abbvie.com/who-we-are/our-stories/abbvies-2024-working-parents-finding-purpose-in-adversity.html | 1 |
| tpl_188 | Technologies in Disease Research | Innovative tools for medical progress. | https://www.abbvie.com/who-we-are/our-stories/five-technologies-supporting-progress-in-challenging-diseases.html | 1 |
| tpl_189 | Educational Grants | Programs for independent learning support. | https://www.abbvie.com/science/independent-educational-grants.html | 1 |
| tpl_190 | Andrew Campbell Profile | Insights into R&D leadership. | https://www.abbvie.com/science/our-people/our-rd-leaders/andrew-campbell.html | 1 |
| tpl_191 | Innovation Areas | Exploring new research focuses. | https://www.abbvie.com/science/areas-of-innovation.html | 1 |
| tpl_192 | Lab to Life | Research impact on practical applications. | https://www.abbvie.com/science/our-people/lab-to-life.html | 1 |
| tpl_193 | Focus Areas | Detailed analysis of research priorities. | https://www.abbvie.com/science/areas-of-focus.html | 1 |
| tpl_194 | Partnering Days | Collaborative events for innovation. | https://www.abbvie.com/science/partner-with-us/partnering-days.html | 1 |
| tpl_195 | Raymond Votzmeyer Profile | Highlighting leadership in R&D. | https://www.abbvie.com/science/our-people/our-rd-leaders/raymond-votzmeyer.html | 1 |
| tpl_196 | Our People | Profiles and contributions in science. | https://www.abbvie.com/science/our-people.html | 1 |
| tpl_197 | Grant Disclosures | Transparency in educational funding. | https://www.abbvie.com/science/independent-educational-grants/grants-and-contribution-disclosures.html | 1 |
| tpl_198 | Eye Care Focus | Advancements in ophthalmology research. | https://www.abbvie.com/science/areas-of-focus/eye-care.html | 1 |
| tpl_199 | Eleni Lagkadinou Profile | Insights into leading research figures. | https://www.abbvie.com/science/our-people/our-rd-leaders/eleni-lagkadinou.html | 1 |
| tpl_200 | RD Leader Profile - Linda Scarazzini | Page featuring the profile of Linda Scarazzini, an RD leader at AbbVie. | https://www.abbvie.com/science/our-people/our-rd-leaders/linda-scarazzini.html | 1 |
| tpl_201 | RD Leader Profile - Wolfram Nothaft | Page featuring the profile of Wolfram Nothaft, an RD leader at AbbVie. | https://www.abbvie.com/science/our-people/our-rd-leaders/wolfram-nothaft.html | 1 |
| tpl_202 | RD Leader Profile - Darin Messina | Page featuring the profile of Darin Messina, an RD leader at AbbVie. | https://www.abbvie.com/science/our-people/our-rd-leaders/darin-messina.html | 1 |
| tpl_203 | Science in 60 Seconds | Interactive page summarizing scientific concepts in a brief and engaging format. | https://www.abbvie.com/science/our-people/science-in-60-seconds.html | 1 |
| tpl_204 | Areas of Innovation - Genomics | Details on genomics research and innovation efforts by AbbVie. | https://www.abbvie.com/science/areas-of-innovation/genomics.html | 1 |
| tpl_205 | Scientific Publications | Repository of scientific research and publications by AbbVie. | https://www.abbvie.com/science/publications.html | 1 |
| tpl_206 | RD Leader Profile - Shuhong Zhang | Page featuring the profile of Shuhong Zhang, an RD leader at AbbVie. | https://www.abbvie.com/science/our-people/our-rd-leaders/shuhong-zhang.html | 1 |
| tpl_207 | RD Leadership Overview | Comprehensive page listing AbbVie's RD leaders and their contributions. | https://www.abbvie.com/science/our-people/our-rd-leaders.html, https://www.abbvie.com/science/our-people/our-rd-leaders/christopher-boone.html | 2 |
| tpl_208 | Therapeutic Modalities and Platforms | Overview of therapeutic modalities and innovative platforms in use at AbbVie. | https://www.abbvie.com/science/areas-of-innovation/therapeutic-modalities-and-platforms.html | 1 |
| tpl_209 | Focus Area - Neuroscience | Page detailing research and advancements in neuroscience at AbbVie. | https://www.abbvie.com/science/areas-of-focus/neuroscience.html | 1 |
| tpl_210 | RD Leader Profile - Michael Foley | Page featuring the profile of Michael Foley, an RD leader at AbbVie. | https://www.abbvie.com/science/our-people/our-rd-leaders/michael-foley.html | 1 |
| tpl_211 | RD Leader Profile - Primal Kaur | Page featuring the profile of Primal Kaur, an RD leader at AbbVie. | https://www.abbvie.com/science/our-people/our-rd-leaders/primal-kaur.html | 1 |
| tpl_212 | Focus Area - Oncology | Details on oncology research and treatments developed by AbbVie. | https://www.abbvie.com/science/areas-of-focus/oncology.html | 1 |
| tpl_213 | RD Leader Profile - Jonathon Sedgwick | Page featuring the profile of Jonathon Sedgwick, an RD leader at AbbVie. | https://www.abbvie.com/science/our-people/our-rd-leaders/jonathon-sedgwick.html | 1 |
| tpl_214 | Lab of the Future | Showcase of AbbVie's innovative lab development strategies. | https://www.abbvie.com/science/our-people/lab-of-the-future.html | 1 |
| tpl_215 | Brand Partnerships - MLB | Information on AbbVie's collaboration with Major League Baseball for health initiatives. | https://www.abbvie.com/who-we-are/brand-partnerships/major-league-baseball.html, https://www.abbvie.com/MLB.html | 2 |
| tpl_216 | Discovery Files | Interactive and multimedia exploration of scientific discoveries by AbbVie. | https://www.abbvie.com/science/our-people/discovery-files.html | 1 |
| tpl_217 | Precision Medicine | Page on personalized medicine strategies and advancements at AbbVie. | https://www.abbvie.com/science/areas-of-innovation/precision-medicine.html | 1 |
| tpl_218 | Behind the Science | Insights into the scientific efforts and personnel driving AbbVie's innovations. | https://www.abbvie.com/science/our-people/behind-the-science.html | 1 |
| tpl_219 | RD Leader Profile - Philip Hajduk | Page featuring the profile of Philip Hajduk, an RD leader at AbbVie. | https://www.abbvie.com/science/our-people/our-rd-leaders/philip-hajduk.html | 1 |
| tpl_220 | Focus Area - Aesthetics | Details on aesthetic treatments and research conducted by AbbVie. | https://www.abbvie.com/science/areas-of-focus/aesthetics.html | 1 |
| tpl_221 | Educational Grants Guide | Training guide for requestors of independent educational grants by AbbVie. | https://www.abbvie.com/science/independent-educational-grants/requestor-training-guide.html | 1 |
| tpl_222 | Patient-Focused Drug Development | Overview of AbbVie's approaches to centering patient needs in drug development. | https://www.abbvie.com/science/areas-of-innovation/patient-focused-drug-development.html | 1 |
| tpl_223 | RD Leader Profile - Daejin Abidoye | Page featuring the profile of Daejin Abidoye, an RD leader at AbbVie. | https://www.abbvie.com/science/our-people/our-rd-leaders/daejin-abidoye.html | 1 |
| tpl_224 | RD Sites | Information about AbbVie's research and development sites worldwide. | https://www.abbvie.com/science/rd-sites.html | 1 |
| tpl_225 | AbbVie Ventures Portfolio | Details the portfolio and initiatives under AbbVie Ventures. | https://www.abbvie.com/science/partner-with-us/abbvie-ventures/abbvie-ventures-portfolio.html | 1 |
| tpl_226 | Clinical Trials Overview | Provides information on ongoing and completed clinical trials by AbbVie. | https://www.abbvie.com/science/clinical-trials.html | 1 |
| tpl_227 | Other Specialty Areas | Focuses on AbbVie's research and achievements in specialty areas of medicine. | https://www.abbvie.com/science/areas-of-focus/other-specialties.html | 1 |
| tpl_228 | Immunology Research | Highlights AbbVie's advancements and research in immunology. | https://www.abbvie.com/science/areas-of-focus/immunology.html | 1 |
| tpl_229 | Community of Science | Showcases AbbVie's community efforts towards scientific development. | https://www.abbvie.com/science/our-people/community-of-science.html | 1 |
| tpl_230 | How to Apply for Grants | Guides on the process to apply for independent educational grants offered by AbbVie. | https://www.abbvie.com/science/independent-educational-grants/how-to-apply.html | 1 |
| tpl_231 | Corporate Opportunities | Explores corporate career opportunities at AbbVie. | https://www.abbvie.com/join-us/opportunities/corporate.html | 1 |
| tpl_232 | AI and Data Convergence | Discusses innovation through artificial intelligence and data convergence in research. | https://www.abbvie.com/science/areas-of-innovation/ai-and-data-convergence.html, https://www.abbvie.com/science/areas-of-innovation/data-convergence.html | 2 |
| tpl_233 | Patient Assistance Income Criteria | Details income criteria for patient assistance programs at AbbVie. | https://www.abbvie.com/patients/patient-support/patient-assistance/income-criteria.html | 1 |
| tpl_234 | Product Quality and Safety | Addresses AbbVie's commitment to product quality and safety standards. | https://www.abbvie.com/patients/product-quality-and-safety.html | 1 |
| tpl_235 | Commercial Opportunities | Highlights commercial career opportunities at AbbVie. | https://www.abbvie.com/join-us/opportunities/commercial.html | 1 |
| tpl_236 | Savings Card Information | Provides information on savings card programs for patients. | https://www.abbvie.com/patients/patient-support/patient-assistance/savings-card.html | 1 |
| tpl_237 | Grant Request Types | Discusses various types of independent educational grants available from AbbVie. | https://www.abbvie.com/science/independent-educational-grants/request-types.html | 1 |
| tpl_238 | Research and Development Opportunities | Explores career opportunities in research and development at AbbVie. | https://www.abbvie.com/join-us/opportunities/research-and-development.html | 1 |
| tpl_239 | General Opportunities | Overview of career opportunities across different domains at AbbVie. | https://www.abbvie.com/join-us/opportunities.html | 1 |
| tpl_240 | Investigator Initiated Studies | Information on how investigators can propose and conduct studies with AbbVie support. | https://www.abbvie.com/science/clinical-trials/investigator-initiated-studies.html | 1 |
| tpl_241 | Online Application Overview | Guides patients through the online application process for assistance programs. | https://www.abbvie.com/patients/patient-support/patient-assistance/online-application-overview.html | 1 |
| tpl_242 | Application FAQs | Answers frequently asked questions about the online application process. | https://www.abbvie.com/patients/patient-support/patient-assistance/online-application-frequently-asked-questions.html | 1 |
| tpl_243 | Patient Assistance Overview | Overview of assistance programs available to patients at AbbVie. | https://www.abbvie.com/patients/patient-support/patient-assistance.html, https://www.abbvie.com/patients/patient-assistance.html | 2 |
| tpl_244 | Eligibility Criteria | Details eligibility requirements for enrollment in assistance programs. | https://www.abbvie.com/patients/patient-support/patient-assistance/eligibility-criteria.html | 1 |
| tpl_245 | Available Assistance Programs | Lists the various patient assistance programs offered by AbbVie. | https://www.abbvie.com/patients/patient-support/patient-assistance/available-programs.html | 1 |
| tpl_246 | Frequently Asked Questions for Assistance | Answers common queries about patient assistance programs. | https://www.abbvie.com/patients/patient-support/patient-assistance/patient-assistance-frequently-asked-questions.html | 1 |
| tpl_247 | AbbVie Ventures | Details collaborative opportunities and initiatives under AbbVie Ventures. | https://www.abbvie.com/science/partner-with-us/abbvie-ventures.html | 1 |
| tpl_248 | Research Collaborative Initiatives | Explores collaborative research initiatives on conditions like migraines and endometriosis. | https://www.abbvie.com/science/abbvie-research-collaborative-migraine.html, https://www.abbvie.com/science/abbvie-research-collaborative-endometrosis.html | 2 |
| tpl_249 | Bay Area Opportunities | Showcases career opportunities specifically in the Bay Area. | https://www.abbvie.com/join-us/bay-area-opportunities.html | 1 |
| tpl_250 | AbbVie Pride Page | A page dedicated to the AbbVie Pride resource group, showcasing its objectives and activities. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/abbvie-pride.html | 1 |
| tpl_251 | Reasonable Accommodations | Information page detailing AbbVie's policies and support for reasonable accommodations. | https://www.abbvie.com/join-us/reasonable-accommodations.html | 1 |
| tpl_252 | Tunisia Office Contact | Contact information for AbbVie's office located in Tunisia. | https://www.abbvie.com/contact-center/locations/tunisia.html | 1 |
| tpl_253 | Croatia Office Contact | Details and contact information for AbbVie offices in Croatia. | https://www.abbvie.com/contact-center/locations/croatia.html | 1 |
| tpl_254 | Algeria Office Contact | Contact page for AbbVie's office in Algeria. | https://www.abbvie.com/contact-center/locations/algeria.html | 1 |
| tpl_255 | South Africa Contact Center | Information on AbbVie's contact support for South Africa and Sub-Saharan Africa. | https://www.abbvie.com/contact-center/locations/south-africa-and-sub-saharan-africa.html | 1 |
| tpl_256 | ESG Resources | Environmental, social, and governance-related resources provided by AbbVie. | https://www.abbvie.com/sustainability/environmental-social-and-governance/resources.html | 1 |
| tpl_257 | Why AbbVie | A page explaining AbbVie's mission, values, and benefits of joining the company. | https://www.abbvie.com/join-us/why-abbvie.html | 1 |
| tpl_258 | Addressing Barriers Initiative | An overview of AbbVie's initiatives to address systemic barriers. | https://www.abbvie.com/sustainability/abbvie-foundation/addressing-systemic-barriers.html | 1 |
| tpl_259 | Asian Leadership Network | Details about the Asian Leadership Network at AbbVie. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/asian-leadership-network.html | 1 |
| tpl_260 | Environmental and Social Governance | AbbVie's commitment and actions towards ESG principles. | https://www.abbvie.com/sustainability/environmental-social-and-governance.html | 1 |
| tpl_261 | Veterans Resource Group | Information about AbbVie's resource group dedicated to veterans. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/veterans.html | 1 |
| tpl_262 | Internship Opportunities | Details on internship programs available at AbbVie. | https://www.abbvie.com/join-us/internships.html | 1 |
| tpl_263 | Employee Benefits | Overview of benefits offered to AbbVie employees. | https://www.abbvie.com/join-us/life-at-abbvie/benefits.html | 1 |
| tpl_264 | Life at AbbVie | Insight into the culture and work environment at AbbVie. | https://www.abbvie.com/join-us/life-at-abbvie.html | 1 |
| tpl_265 | Slovenia Office Contact | Contact details for AbbVie's office in Slovenia. | https://www.abbvie.com/contact-center/locations/slovenia.html | 1 |
| tpl_266 | Allergan Aesthetics Opportunities | Career opportunities within Allergan Aesthetics, a part of AbbVie. | https://www.abbvie.com/join-us/opportunities/allergan-aesthetics.html | 1 |
| tpl_267 | Student Programs | Overview of programs offered to students and recent graduates. | https://www.abbvie.com/join-us/student-programs.html | 1 |
| tpl_268 | Global Locations Directory | Listing and details of AbbVie's global office locations. | https://www.abbvie.com/contact-center/locations.html | 1 |
| tpl_269 | Cerevel Collaboration | Information on AbbVie's collaboration with Cerevel Therapeutics. | https://www.abbvie.com/cerevel.html | 1 |
| tpl_270 | Celsius Therapeutics Partnership | Details on the partnership between AbbVie and Celsius Therapeutics. | https://www.abbvie.com/celsius-therapeutics.html | 1 |
| tpl_271 | Nimble Therapeutics Collaboration | Information on AbbVie's collaboration with Nimble Therapeutics. | https://www.abbvie.com/nimbletherapeutics.html | 1 |
| tpl_272 | Capstan Therapeutics Collaboration | Details on AbbVie's partnership with Capstan Therapeutics. | https://www.abbvie.com/capstan-therapeutics.html | 1 |
| tpl_273 | Women Leaders in Action | Details about AbbVie's resource group for women leaders. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/women-leaders-in-action.html | 1 |
| tpl_274 | Graduate and Entry-Level Positions | Information on graduate programs and entry-level career opportunities at AbbVie. | https://www.abbvie.com/join-us/student-and-new-graduates/new-graduates-and-entry-level-positions.html | 1 |
| tpl_275 | Mitokinin Page | A webpage describing Mitokinin, possibly related to AbbVie research. | https://www.abbvie.com/mitokinin.html | 1 |
| tpl_276 | Immunogen Page | A detailed page on Immunogen research or information. | https://www.abbvie.com/immunogen.html | 1 |
| tpl_277 | Equal Employment Opportunity | Information regarding AbbVie's commitment to equal employment opportunities. | https://www.abbvie.com/join-us/equal-employment-opportunity-employer.html | 1 |
| tpl_278 | Innovative Impact Foundation | Details on initiatives under AbbVie Foundation focusing on innovation and impact. | https://www.abbvie.com/sustainability/abbvie-foundation/innovative-impact.html | 1 |
| tpl_279 | Operations Opportunities | Career opportunities in operations at AbbVie. | https://www.abbvie.com/join-us/opportunities/operations.html | 1 |
| tpl_280 | Learning and Development | Programs and initiatives for learning and development at AbbVie. | https://www.abbvie.com/join-us/life-at-abbvie/learning-and-development.html | 1 |
| tpl_281 | Workplace Well-being | Well-being programs and policies for employees at AbbVie. | https://www.abbvie.com/join-us/life-at-abbvie/well-being-in-the-workplace.html | 1 |
| tpl_282 | Student and Graduate Programs | Information on programs targeted at students and new graduates. | https://www.abbvie.com/join-us/student-and-new-graduates.html, https://www.abbvie.com/join-us/opportunities/student-programs.html | 2 |
| tpl_283 | Black Business Network | Details on the Black Business Network employee resource group at AbbVie. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/black-business-network.html | 1 |
| tpl_284 | Employee Resource Groups Overview | An overview of employee resource groups at AbbVie. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups.html | 1 |
| tpl_285 | Serbia Contact Center | Contact information for AbbVie's Serbia location. | https://www.abbvie.com/contact-center/locations/serbia.html | 1 |
| tpl_286 | Human Capital Management | Information on AbbVie's human capital management as part of sustainability efforts. | https://www.abbvie.com/sustainability/environmental-social-and-governance/human-capital-management.html | 1 |
| tpl_287 | AbbVie Foundation Overview | An overview of the AbbVie Foundation's philanthropic efforts. | https://www.abbvie.com/sustainability/abbvie-foundation.html, https://www.abbvie.com/sustainability/philanthropy/employee-engagement.html, https://www.abbvie.com/sustainability/philanthropy/philanthropic-programs.html | 5 |
| tpl_288 | Ability at AbbVie | Details on the Ability at AbbVie employee resource group. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/ability-at-abbvie.html | 1 |
| tpl_289 | Bosnia and Herzegovina Contact Center | Contact information for AbbVie's Bosnia and Herzegovina location. | https://www.abbvie.com/contact-center/locations/bosnia-and-herzegovina.html | 1 |
| tpl_290 | Disaster Relief | Programs and initiatives by AbbVie for disaster relief efforts. | https://www.abbvie.com/sustainability/disaster-relief.html | 1 |
| tpl_291 | Postdoctoral Program | Information on postdoctoral opportunities at AbbVie. | https://www.abbvie.com/join-us/postdoctoral-program.html | 1 |
| tpl_292 | Ahora Hispanic Latino Network | Details on the Ahora Hispanic Latino employee resource group at AbbVie. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/ahora-hispanic-latino.html | 1 |
| tpl_293 | Environmental Sustainability | AbbVie's initiatives in environmental sustainability. | https://www.abbvie.com/sustainability/environmental-social-and-governance/environmental-sustainability.html | 1 |
| tpl_294 | United States Contact Center | Contact information for AbbVie's United States location. | https://www.abbvie.com/contact-center/locations/united-states.html | 1 |
| tpl_295 | Aliada Therapeutics | Overview or information on Aliada Therapeutics. | https://www.abbvie.com/aliada-therapeutics.html | 1 |
| tpl_296 | Lithuania Contact Center | Contact information for AbbVie's Lithuania location. | https://www.abbvie.com/contact-center/locations/lithuania.html | 1 |
| tpl_297 | Allergan Labeling | Information on Allergan labeling as part of AbbVie's portfolio. | https://www.abbvie.com/allergan-labeling.html | 1 |
| tpl_298 | Romania Contact Center | Contact information for AbbVie's Romania location. | https://www.abbvie.com/contact-center/locations/romania.html | 1 |
| tpl_299 | Estonia Contact Center | Contact information for AbbVie's Estonia location. | https://www.abbvie.com/contact-center/locations/estonia.html | 1 |
| tpl_300 | Partnerships Page | Page detailing partnerships, possibly with specific organizations or events. | https://www.abbvie.com/partnerships-chicago-cubs.html | 1 |
| tpl_301 | Location Detail Page | Provides details about specific AbbVie locations worldwide. | https://www.abbvie.com/contact-center/locations/lebanon.html | 1 |
| tpl_302 | Accessibility Statement | Page outlining AbbVie's accessibility policies and commitments. | https://www.abbvie.com/accessibility-statement/declaracion-de-accessibilidad.html | 1 |
| tpl_303 | Location Detail Page | Provides details about specific AbbVie locations worldwide. | https://www.abbvie.com/contact-center/locations/latvia.html | 1 |
| tpl_304 | Location Detail Page | Provides details about specific AbbVie locations worldwide. | https://www.abbvie.com/contact-center/locations/united-arab-emirates.html | 1 |
| tpl_305 | Contact Us Page | Central page for contacting AbbVie directly. | https://www.abbvie.com/contactus.html | 1 |
| tpl_306 | Location Detail Page | Provides details about specific AbbVie locations worldwide. | https://www.abbvie.com/contact-center/locations/saudi-arabia.html | 1 |
| tpl_307 | Community Guidelines | Describes social media and community interaction policies. | https://www.abbvie.com/social-media-community-guidelines.html | 1 |
| tpl_308 | Patents Information Page | Contains information related to AbbVie's patents and intellectual property. | https://www.abbvie.com/patents.html | 1 |
| tpl_309 | Impact History Page | Details historical milestones and achievements of AbbVie. | https://www.abbvie.com/landing/a-history-of-impact.html | 1 |
| tpl_310 | Earnings Reports Page | Provides the latest financial earnings and reports from AbbVie. | https://www.abbvie.com/latest-earnings.html | 1 |
| tpl_311 | Privacy Policy Page | Details AbbVie's privacy practices and policies. | https://www.abbvie.com/privacy.html | 1 |
| tpl_312 | Privacy Inquiry Page | Dedicated page for submitting privacy-related inquiries to AbbVie. | https://www.abbvie.com/privacy-inquiry.html | 1 |
