# Subspace.money — Product Teardown
### Independent Product Analysis · May 2026

---

## Overview

This repository contains a structured product teardown of **Subspace.money**, an India-first subscription management and marketplace platform that enables users to manage existing subscriptions, purchase new ones via gift vouchers, and share subscriptions with others through a group finance model.

This project was self-initiated as part of my effort to develop a practical product thinking skillset — moving beyond theory into real, hands-on product analysis. The goal was to pick a live product operating in a competitive space, use it as a real customer, and deliver feedback that is specific, consequence-aware, and actionable — the kind of thinking expected in a product or strategy role from day one.

---

## Methodology

The app was used as a real customer across all core flows — onboarding, subscription discovery, gift card purchase, wallet and withdrawal, chat and friends features, and account management. Observations were documented during usage, then structured through a product analysis lens covering:

- **GTM & ICP** — where the product's positioning or go-to-market creates gaps with its target users
- **Features / Services** — where existing features fail to deliver on their intended function or miss an opportunity
- **UX** — where the experience breaks user trust, creates confusion, or blocks core flows
- **Competitor Analysis** — where benchmarking against comparable products reveals clear gaps

Frameworks such as value chain analysis, customer journey mapping, network effects theory, and conversion funnel analysis informed the reasoning throughout — applied as analytical lenses, not templates.

---

## Structure

The report is divided into two sections:

### Primary Analysis — 8 Strategic & Product Observations

| # | Observation | Pillar |
|---|-------------|--------|
| 1 | Onboarding fails to communicate the buy + share value proposition | GTM & ICP |
| 2 | Gift card mechanic is visible but not explained — expectation gap at purchase | Features / Services |
| 3 | Gift card tier structure is duplicated, unexplained, and unconvertible | Features / Services |
| 4 | Cart bugs and absent cross-sell mechanics damage purchase conversion | Features + GTM |
| 5 | Tag colors and numbers on subscription cards have no explained meaning | UX + Features |
| 6 | Friends feature is structurally disconnected from the sharing flow | Features + GTM |
| 7 | Refer & earn and savings features are buried — growth loop is invisible | GTM & ICP |
| 8 | Empty chats persist without a message being sent — privacy and trust risk | Features + UX |

### Secondary Section — UX & UI Issues Impacting Core Functioning

Flagged separately because they directly affect app reliability and user trust:

| # | Issue | Severity |
|---|-------|----------|
| 1 | Accounts tab inaccessible until app restart — KYC flow blocked | Critical |
| 2 | Withdrawal back navigation leads to wrong page + inconsistent animations | Medium |
| 3 | Chat input invisible when keyboard opens on Android | High |
| 4 | Dark mode has no outlines and no accessibility / high contrast support | Medium |

---

## Each Observation Is Structured As

**(a) Observed** — What was seen directly in the app or flow

**(b) Problem** — The real user or business pain, and why it matters at scale

**(c) Ship instead** — A specific, actionable solution with tradeoff consideration

---

## Key Themes

Across the eight primary observations, three systemic issues emerge:

**1. Trust gaps at the transaction layer** — Points 2, 3, and 4 all point to a purchase experience that creates confusion at the moment of highest user commitment. In a fintech product, that is the most expensive place to lose a user.

**2. Value proposition invisible to new users** — Points 1 and 7 show that Subspace's most differentiated features — the marketplace, group sharing, and savings flywheel — are either not communicated during onboarding or buried deep in the product. Users who do not discover these features will not stay.

**3. Network effect moat is structurally weakened** — Point 6 identifies that the friends and sharing features, which are central to Subspace's network effect moat, are disconnected from each other. Sharing interactions remain anonymous with no social layer forming — which means the stickiness that network effects are supposed to create is not compounding.

---

## Full Report

📄 [View Full Report — Google Drive](https://docs.google.com/document/d/1bbyGhknj0DqZAJYiVXKhzHKUk8nKpGxO-l-45ELw-g4/edit?usp=drive_link)

The `.docx` report file is also attached directly to this repository.

---

## Disclaimer

This report was drafted with the assistance of a generative AI tool. All product research, in-app observations, competitive analysis, and ideation are my own. The AI was used solely to structure and articulate findings — every observation reflects direct personal usage of the Subspace application, and every recommendation originates from my own analysis and thinking.

---

*Subspace.money — Independent Product Teardown · May 2026*
