# Scope of Work (SOW)

## Project: UrbanKicks Apparel — Online Storefront & POS Integration

| Field | Detail |
|---|---|
| **Client** | UrbanKicks Apparel (Boutique Footwear Brand) |
| **Client Contact** | Sarah Lim, Operations Director |
| **Prepared By** | ClientOps Desk — Lead Operations Orchestrator |
| **Date Issued** | 2026-10-10 |
| **Project Code** | UK-RETAIL-2026-Q4 |
| **Engagement Channel** | WhatsApp Inbound Inquiry |
| **Hard Deadline** | 28 days from kickoff (holiday pop-up launch) |
| **Budget Ceiling** | RM 16,000 (board-approved, Phase 1) |

---

## 1. Project Objective

Transform UrbanKicks Apparel's physical retail operation into a full online storefront with integrated payment processing, AI-powered product recommendations, and real-time inventory synchronization between the physical POS system and the digital catalog. The solution must launch within 28 days to coincide with the client's upcoming holiday pop-up event.

### Core Goals
- Deploy a responsive web application accessible across desktop, tablet, and mobile
- Enable online checkout via FPX (mandatory for Malaysian market) and Stripe (international cards)
- Implement an AI recommendation widget to increase average order value
- Build a backend sync script that prevents overselling by reconciling POS inventory counts with the online catalog in real time
- Deliver all artifacts (milestone breakdown, pricing, slide deck) to the client by the next business morning

---

## 2. Tiered Package Summary

Due to the full ideal scope (RM 17,964) exceeding the board-approved ceiling of RM 16,000, two engagement tiers are proposed:

### Tier A: Core MVP — RM 12,046.10 (Within Budget)

| Component | Scope |
|---|---|
| Responsive storefront | Product catalog, cart, checkout |
| Payment gateway | FPX only (Malaysian online banking) |
| POS inventory sync | Real-time sync script (crucial requirement) |
| UI/UX design | Storefront and catalog layout |
| QA | Core functional + payment flow testing |
| Project management | 4-week sprint coordination |
| Contingency | 10% buffer included (RM 1,095.10) |
| **Deferred items** | Stripe gateway, AI recommendation widget (Phase 2) |

### Tier B: Full Enterprise — RM 17,964.00 (Ideal Scope, Over Budget by RM 1,964)

| Component | Additional Scope vs Core MVP |
|---|---|
| Payment gateway | FPX + Stripe (international cards) |
| AI recommendation widget | Full AI engine with personalized product suggestions |
| Frontend | Enhanced checkout, AI widget integration |
| Backend | Dual gateway integration, catalog API, enhanced POS sync |
| QA | Full regression, cross-browser, dual payment testing |
| Project management | Enhanced client reporting and stakeholder demos |

> **Recommendation:** Proceed with Tier A (Core MVP) to meet the holiday pop-up deadline within budget. Tier B enhancements can be scoped as a Phase 2 change order post-launch.

---

## 3. Milestone Breakdown (Weeks 1-4)

### Week 1: Discovery, Design & Architecture (Days 1-7)

| Day | Activity | Deliverable |
|---|---|---|
| Day 1-2 | Requirements lock, technical architecture design, POS API audit | Approved architecture document |
| Day 3-5 | UI/UX wireframes: storefront, catalog, product detail, checkout, cart | Wireframe set (Figma or equivalent) |
| Day 6-7 | Design review with Sarah Lim, revisions, design sign-off | Approved visual designs |

**Milestone 1 Exit Criteria:** Signed-off wireframes and visual designs; POS API access credentials obtained; technical architecture approved.

**Services:** UI/UX Design (15h core / 18h enterprise), Project Management (3h)

### Week 2: Frontend Build & Backend Foundation (Days 8-14)

| Day | Activity | Deliverable |
|---|---|---|
| Day 8-10 | Frontend scaffold: responsive layout, navigation, catalog pages | Working storefront shell |
| Day 11-12 | Product catalog data model, admin product CRUD | Catalog management interface |
| Day 13-14 | Backend API foundation: product endpoints, cart logic | API documentation + working endpoints |

**Milestone 2 Exit Criteria:** Storefront renders product catalog responsively; backend API serves product data; cart functionality operational.

**Services:** Frontend Development (11h core / 14h enterprise), Backend API Integration (10h core / 12h enterprise)

### Week 3: Payment Integration & POS Sync (Days 15-21)

| Day | Activity | Deliverable |
|---|---|---|
| Day 15-16 | FPX payment gateway integration and testing | FPX checkout flow operational |
| Day 17-18 | (Enterprise only) Stripe payment gateway integration | Stripe checkout flow operational |
| Day 19-20 | POS inventory sync script: polling/sync logic, reconciliation | Sync script deployed and tested |
| Day 21 | End-to-end payment + inventory integration test | Integration test report |

**Milestone 3 Exit Criteria:** FPX payments process successfully; POS inventory sync prevents overselling in test scenarios; (Enterprise) Stripe payments operational.

**Services:** Backend API Integration (8h core / 10h enterprise), Frontend Development (8h core / 10h enterprise), AI Agent Configuration (0h core / 8h enterprise)

### Week 4: AI Widget, QA, UAT & Launch (Days 22-28)

| Day | Activity | Deliverable |
|---|---|---|
| Day 22-23 | (Enterprise only) AI recommendation widget integration | AI widget live on storefront |
| Day 24-25 | Full QA: regression, cross-browser, responsive, payment flows | QA sign-off report |
| Day 26 | User Acceptance Testing (UAT) with Sarah Lim and team | UAT sign-off |
| Day 27 | Bug fixes, final polish, performance optimization | Production-ready build |
| Day 28 | Deployment to production, go-live for holiday pop-up | Live storefront URL |

**Milestone 4 Exit Criteria:** All critical bugs resolved; UAT signed off by client; storefront deployed and live; holiday pop-up ready.

**Services:** QA Testing (12h core / 14h enterprise), AI Agent Configuration (0h core / 4h enterprise), Frontend Development (3h core / 4h enterprise), Project Management (7h core / 9h enterprise)

---

## 4. Deliverables

### Core MVP (Tier A) Deliverables
1. Responsive web storefront (desktop, tablet, mobile)
2. Product catalog with admin management interface
3. FPX payment gateway integration
4. POS-to-online inventory synchronization script
5. Shopping cart and checkout flow
6. Basic SEO meta tags and structured data
7. Deployment to production hosting
8. Technical documentation (API docs, admin guide)

### Full Enterprise (Tier B) Additional Deliverables
9. Stripe payment gateway integration (international cards)
10. AI-powered product recommendation widget
11. Enhanced analytics dashboard
12. Extended QA: cross-browser regression suite

### Documentation Deliverables (Both Tiers)
- This Scope of Work document
- Financial estimate breakdown (01_financial_estimate.csv)
- Client pitch presentation slides (03_client_proposal_slides.md)
- Execution audit log (00_execution_audit.log)

---

## 5. Out-of-Scope Boundaries

The following items are explicitly excluded from this engagement. Any request for these items will be treated as a change order:

1. **Mobile native apps** (iOS/Android) — only a responsive web application is in scope
2. **Legacy POS system replacement** — we integrate with the existing POS via its API; we do not replace or modify the POS software itself
3. **Content creation** — product photography, copywriting, and marketing content are the client's responsibility
4. **Hosting and domain costs** — cloud hosting, domain registration, and SSL certificate fees are borne by the client
5. **Third-party API fees** — FPX merchant fees, Stripe transaction fees, and AI model API usage costs are the client's responsibility
6. **Post-launch maintenance** — 30 days of bug-fix support is included; ongoing maintenance requires a separate retainer agreement
7. **Multi-language support** — English and Bahasa Malaysia only for Phase 1; additional languages are a future phase
8. **Loyalty program or referral system** — not included in this scope
9. **Social media integration** — social login and social commerce feeds are excluded
10. **Data migration from existing systems** — if the client has an existing online catalog, migration is a separate scope item

---

## 6. Payment Schedule

Payments are tied to milestone completion and invoiced upon acceptance of milestone exit criteria.

| Payment Milestone | Trigger | Percentage | Amount (Core MVP) | Amount (Full Enterprise) |
|---|---|---|---|---|
| **Deposit** | Contract signing + kickoff | 40% | RM 4,818.44 | RM 7,185.60 |
| **Beta Delivery** | Milestone 3 exit (payment + sync operational) | 30% | RM 3,613.83 | RM 5,389.20 |
| **Final Sign-off** | Milestone 4 exit (UAT passed, deployed) | 30% | RM 3,613.83 | RM 5,389.20 |
| **Total** | | 100% | RM 12,046.10 | RM 17,964.00 |

### Payment Terms
- All invoices are due within 7 days of issuance
- Late payments beyond 14 days may result in work suspension
- Payment method: bank transfer (details provided on invoice)
- Currency: Malaysian Ringgit (MYR)
- Taxes: Subject to prevailing SST rates where applicable

---

## 7. Assumptions & Dependencies

1. Client provides POS API documentation and access credentials by Day 2
2. Client provides product catalog data (CSV/spreadsheet) by Day 3
3. Client provides brand assets (logo, color palette, typography) by Day 2
4. Client allocates Sarah Lim or a designate for daily 15-minute stand-ups and weekly reviews
5. FPX merchant account is already registered or will be registered by Day 7
6. (Enterprise) Stripe account is registered and verified by Day 10
7. Production hosting environment is provisioned by Day 25

---

## 8. Change Management

Any scope additions, timeline extensions, or budget revisions must be processed through a formal change order:
1. Client submits change request in writing
2. ClientOps Desk assesses impact on timeline, cost, and resources
3. Both parties sign the change order before work begins
4. Change order becomes an addendum to this SOW

---

## 9. Acceptance Criteria

The project will be considered complete and accepted when:
- All Milestone 1-4 exit criteria are met and signed off
- The storefront is deployed to production and accessible via a public URL
- FPX payment processes a test transaction successfully
- POS inventory sync prevents overselling in a verified test scenario
- (Enterprise) Stripe payment processes a test transaction successfully
- (Enterprise) AI recommendation widget displays relevant suggestions on the storefront
- All critical and high-severity bugs are resolved
- UAT is signed off by Sarah Lim or her designate

---

*This Scope of Work is valid for 14 days from the date issued. Engagement begins upon signed acceptance and receipt of the deposit payment.*
