---
tags: [CampusOS, briefing, gaps, website, compliance]
date: 2026-06-03
status: active
---

# 02 · Critical Gaps & Fixes

← [[01 - Situation & Brand Scorecard]] | Next: [[03 - Market Opportunity]] →

---

## The Core Risk

> When a CIO or IT Director gets our email, the first thing they do is visit campusos.co. If they see INR pricing, India-specific terminology, and zero FERPA — the decision is made before they ever book a demo. In higher-ed procurement, you rarely get a second chance with the same contact.

**Do NOT start any college outreach until the site passes the 30-second US buyer test.**

---

## 9 Identified Gaps

| Gap | Current State | Priority | Fix Timeline |
|-----|--------------|----------|-------------|
| **SEO Locale** | `og:locale = en_IN` on every page | 🔴 CRITICAL | 1 day |
| **Pricing Currency** | INR in JSON-LD schema + visible pricing | 🔴 CRITICAL | 1 day |
| **FERPA Compliance** | Zero mention anywhere on the site | 🔴 CRITICAL | Week 1 |
| **Terminology** | TnP, NAAC, NEP, UGC, "College ERP" in copy | 🔴 CRITICAL | 2 weeks |
| **US Customer Proof** | No US logos, no case studies (UMF not showcased) | 🟡 HIGH | Week 2 |
| **Review Profiles** | Not listed on G2 or Capterra | 🟡 HIGH | Week 1 |
| **Content Depth** | No blog, no /about page, no /pricing page | 🟡 HIGH | Month 1–2 |
| **ADA / WCAG** | No accessibility statement posted publicly | 🟡 HIGH | Month 1 |
| **SOC 2** | No audit initiated — required by larger institutions | 🔵 YEAR 1 | Month 3–6 |

---

## What Changes After 2 Weeks of Work

| Before | After |
|--------|-------|
| `og:locale = en_IN` signals India in every search | `og:locale = en_US` — US search ranking signal |
| INR pricing → instant disqualifier | USD pricing visible — objection removed |
| FERPA absent — question 1 in every demo is unanswerable | FERPA compliance page live — linked from homepage |
| TnP, NAAC, NEP — reads as offshore vendor | US terminology sweep — reads as US vendor |
| No US logos on site | UMF logo on homepage — "one real US university" |
| No G2/Capterra — invisible in buyer research | Profiles created — appears in procurement searches |

---

## Terminology Swap Cheat Sheet

| India Term | US Term |
|-----------|---------|
| TnP (Training & Placement) | Career Services |
| NAAC | Accreditation |
| NEP | Curriculum Standards |
| UGC | Federal / State Compliance |
| College ERP | Campus Management System |

---

## Pre-Outreach Checklist (Hard Gate)

Before a single email goes out, confirm all three:

- [ ] FERPA compliance page live at `campusos.co/compliance` — linked from homepage header
- [ ] USD pricing visible — zero INR showing anywhere on the site
- [ ] Calendly booking link set up and tested end-to-end

---

## Related Notes
- [[07 - Timeline & Priority Actions]] — who owns each fix and by when
- [[08 - Decisions Needed]] — team must assign ownership of the site sprint today
