# Client Pitch Presentation
## UrbanKicks Apparel — Online Storefront & POS Integration

> **Prepared for:** Sarah Lim, Operations Director
> **Prepared by:** ClientOps Desk
> **Date:** October 10, 2026
> **Audience:** UrbanKicks Board of Directors

---

## Slide 1: Executive Summary & Project Vision

### From Brick-and-Mortar to Digital Storefront in 28 Days

**The Opportunity**
UrbanKicks Apparel is ready to take its boutique footwear brand online. With the holiday pop-up event approaching in exactly 4 weeks, this is the moment to launch a full e-commerce presence that captures both walk-in and online customers simultaneously.

**What We're Building**
A responsive web storefront with product catalogs, integrated Malaysian payment gateways (FPX + Stripe), an AI-powered recommendation engine, and a real-time inventory sync that connects your physical POS to your online catalog — so you never oversell a single pair of shoes.

**Why Now**
- Holiday pop-up creates natural launch momentum
- Board has approved RM 16,000 for Phase 1
- 28-day timeline is aggressive but achievable with focused execution
- Early online presence captures holiday season revenue

**Our Commitment**
We deliver a production-ready storefront, milestone-by-milestone pricing transparency, and this slide deck — all by tomorrow morning so your board can make an informed decision.

---

## Slide 2: Technical Architecture & Core Deliverables

### Architecture Overview

```
[Customer Browser]
       |
       v
[Responsive Web Frontend] --- [AI Recommendation Widget]
       |                              |
       v                              v
[Backend API Layer] ---------- [AI Agent Service]
       |
       +-- [Product Catalog API]
       +-- [FPX Payment Gateway]
       +-- [Stripe Payment Gateway]
       +-- [Inventory Sync Engine]
              |
              v
       [Physical POS System]
```

### Core Deliverables

| # | Deliverable | Description |
|---|---|---|
| 1 | **Responsive Storefront** | Desktop, tablet, mobile-optimized product browsing and checkout |
| 2 | **Product Catalog** | Admin-managed catalog with categories, images, and pricing |
| 3 | **FPX Payment Gateway** | Malaysian online banking integration (Maybank2u, CIMB Clicks, etc.) |
| 4 | **Stripe Payment Gateway** | International card payments (Visa, Mastercard, Amex) |
| 5 | **POS Inventory Sync** | Real-time stock reconciliation preventing overselling across channels |
| 6 | **AI Recommendation Widget** | Personalized product suggestions based on browsing behavior |

### Technology Stack
- **Frontend:** React/Next.js (responsive, server-rendered)
- **Backend:** Node.js REST API
- **Payments:** FPX direct integration + Stripe SDK
- **AI:** Recommendation engine with collaborative filtering
- **Sync:** Scheduled polling + webhook-based POS integration
- **Hosting:** Cloud-deployed with auto-scaling

---

## Slide 3: Delivery Roadmap & Weekly Milestones

### 4-Week Sprint to Launch

| Week | Phase | Key Activities | Exit Milestone |
|---|---|---|---|
| **Week 1** | Discovery & Design | Requirements lock, POS API audit, UI/UX wireframes, design sign-off | Approved architecture + visual designs |
| **Week 2** | Build Foundation | Frontend scaffold, catalog data model, backend API, cart logic | Storefront renders catalog + cart operational |
| **Week 3** | Integration Sprint | FPX/Stripe gateway integration, POS inventory sync script, end-to-end testing | Payments process + sync prevents overselling |
| **Week 4** | QA & Launch | AI widget integration, full regression testing, UAT, bug fixes, production deployment | Live storefront for holiday pop-up |

### Critical Path
```
Day 1-2: POS API access secured ──> Day 3-7: Designs approved
                                            |
                                            v
Day 8-14: Frontend + Backend built ──> Day 15-21: Payments + Sync integrated
                                                   |
                                                   v
                                   Day 22-28: QA ──> UAT ──> LAUNCH
```

### Risk Buffers Built In
- Each service line includes a 10-25% risk buffer (per rate card)
- Core MVP includes an additional 10% contingency (RM 1,095)
- Daily stand-ups ensure blockers are caught within 24 hours
- UAT scheduled with 2-day buffer before go-live

---

## Slide 4: Financial Proposal & Tiered Investment Options

### Budget Reality

The full ideal scope totals **RM 17,964** — exceeding the board-approved ceiling of RM 16,000 by RM 1,964. We've solved this with a two-tier package:

---

### Tier A: Core MVP — RM 12,046.10

*Within budget with RM 3,954 headroom*

| Service | Hours | Base Cost | Risk Buffer | Line Total |
|---|---|---|---|---|
| UI/UX Design | 15h | RM 1,800 | RM 180 | RM 1,980 |
| Frontend Development | 22h | RM 3,300 | RM 495 | RM 3,795 |
| Backend API Integration | 18h | RM 3,240 | RM 648 | RM 3,888 |
| AI Agent Configuration | Deferred | — | — | — |
| Project Management | 10h | RM 1,000 | RM 100 | RM 1,100 |
| QA Testing | 12h | RM 1,080 | RM 108 | RM 1,188 |
| **Subtotal** | **77h** | **RM 9,420** | **RM 1,531** | **RM 10,951** |
| 10% Contingency | | | | RM 1,095.10 |
| **Grand Total** | | | | **RM 12,046.10** |

**What's Included:** Responsive storefront, product catalog, FPX payments, POS inventory sync, QA, PM
**What's Deferred:** Stripe gateway, AI recommendation widget (Phase 2 change order)

---

### Tier B: Full Enterprise — RM 17,964.00

*Ideal scope, RM 1,964 over budget*

| Service | Hours | Base Cost | Risk Buffer | Line Total |
|---|---|---|---|---|
| UI/UX Design | 18h | RM 2,160 | RM 216 | RM 2,376 |
| Frontend Development | 28h | RM 4,200 | RM 630 | RM 4,830 |
| Backend API Integration | 22h | RM 3,960 | RM 792 | RM 4,752 |
| AI Agent Configuration | 12h | RM 2,640 | RM 660 | RM 3,300 |
| Project Management | 12h | RM 1,200 | RM 120 | RM 1,320 |
| QA Testing | 14h | RM 1,260 | RM 126 | RM 1,386 |
| **Grand Total** | **106h** | **RM 15,420** | **RM 2,544** | **RM 17,964** |

**Everything Included:** All deliverables including Stripe + AI widget

---

### Our Recommendation

> **Go with Tier A (Core MVP) for the holiday pop-up.** Launch with FPX payments and POS sync — the two things that directly prevent revenue loss. Scope Stripe and the AI widget as a Phase 2 change order within 30 days of go-live, funded from the RM 3,954 budget headroom plus a small top-up.

---

## Slide 5: Risk Mitigation & Margin Guarantees

### Risk Matrix

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| POS API access delayed | Medium | High | Day 1-2 priority; fallback manual sync script if API unavailable |
| FPX merchant approval slow | Low | High | Client registers account Day 1; we build against sandbox in parallel |
| Scope creep during build | High | Medium | Strict SOW boundaries; formal change order process |
| Holiday deadline missed | Low | Critical | 4-milestone sprint with daily stand-ups; 2-day UAT buffer |
| Overselling due to sync failure | Medium | Critical | Sync script includes failsafe: auto-disable online checkout if sync is stale >5 min |

### Margin Guarantees

**Risk Buffers Applied Per Rate Card:**
- UI/UX Design: 10% buffer on all hours
- Frontend Development: 15% buffer
- Backend API Integration: 20% buffer (highest complexity)
- AI Agent Configuration: 25% buffer (emerging tech uncertainty)
- Project Management: 10% buffer
- QA Testing: 10% buffer

**Additional Safeguards:**
- Core MVP carries a **10% contingency** (RM 1,095.10) on top of all risk buffers
- Total buffer as % of Core MVP grand total: **21.8%** (RM 2,626.10 of RM 12,046.10)
- No contingency on Full Enterprise (already over budget) — buffer is built into per-service risk percentages

### Quality Gates
1. **Design sign-off** before any code is written (Week 1 exit)
2. **Integration test report** before UAT (Week 3 exit)
3. **UAT sign-off** by Sarah Lim before deployment (Week 4)
4. **Post-launch 30-day bug warranty** included in both tiers

---

## Slide 6: Next Steps & Immediate Kickoff Action

### Decision Required Today

| Decision | Options | Impact |
|---|---|---|
| **Engagement tier** | Tier A (Core MVP) or Tier B (Full Enterprise) | Determines scope and budget |
| **Budget approval** | RM 12,046 (Tier A) or RM 17,964 (Tier B) | If Tier B, board needs to approve RM 1,964 overage |
| **Kickoff date** | Tomorrow (Day 1) or Monday | Each day lost compresses the 28-day window |

### If Approved Tomorrow — Day 1 Actions

1. **08:00** — Contract signing + 40% deposit invoice issued
2. **09:00** — Kickoff call with Sarah Lim (30 min): confirm POS API details, brand assets, product data
3. **10:00** — Technical architect begins POS API audit
4. **14:00** — UI/UX designer begins storefront wireframes
5. **17:00** — Day 1 stand-up: confirm all access credentials received

### What You'll Have by Tomorrow Morning

| Deliverable | Format | Location |
|---|---|---|
| Financial estimate breakdown | CSV | `outputs/01_financial_estimate.csv` |
| Full Scope of Work (SOW) | Markdown | `outputs/02_scope_of_work.md` |
| This pitch presentation | Markdown | `outputs/03_client_proposal_slides.md` |
| Execution audit report | Log | `outputs/00_execution_audit.log` |

### Contact

**ClientOps Desk — Lead Operations Orchestrator**
- Channel: WhatsApp (same channel as inquiry)
- Response time: Within 2 hours during business hours
- Escalation: Direct line to Operations Director

---

### The Bottom Line

> UrbanKicks can have a live online storefront with FPX payments and POS inventory sync in 28 days for **RM 12,046** — within budget, with a 21.8% total risk buffer, and ready for the holiday pop-up. Stripe and AI recommendations can follow as Phase 2. The only thing standing between today and kickoff is a signature.

---

*End of Presentation — 6 Slides*
