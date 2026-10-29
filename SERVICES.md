# heynewell — Service Catalog & Scopes

> Internal ops doc. Tier 1 = live on the site. Tier 2 = scoped, sold by phone, added to site on demand.
> Construction lane = /construction.html. Prices are anchors — Jordan confirms per client.
> Fulfillment key: 🤖 agent-run (Jordan QA) · 👤 Jordan · 🤝 partner (vendor needed)

---

## TIER 1 — The Core (live on heynewell.com)

### 1. Email, fixed up — $150 one-time · 🤖 1 day
- Own-domain mailbox(es) on managed mailcow (prod), migration, device setup, spam handling
- **Fulfillment runbook exists** (2026-10-29 session: script → domains → mailboxes → DNS → SOPS → TB)
- Upsell trigger: every email client needs a website

### 2. Website, live — $900 one-time · 🤖 3–5 days
- Fast static site (CF Pages), mobile-first, local SEO basics, GBP citation match
- Client supplies photos; copy drafted by agent, approved by client
- Upsell trigger: everything (care plan)

### 3. Everything, kept running — $95/mo · 🤖 ongoing
- Hosting, email, backups, security, content changes within 48h, cancel anytime
- Margin note: infra cost ≈ $0 (own fleet); price is for the SLA

---

## TIER 2 — The Add-on Ladder (scoped, sell by phone after site ships)

### 4. Google Business Profile engine — $150/mo · 🤖
- Weekly posts, review responses within 24h, review-request pipeline (auto SMS/email post-job)
- Setup included first month (photos, services, service area, Q&A seeding)
- **Sell to:** everyone. This is where trades get calls. Highest-margin add-on.

### 5. Socials, done-for-you — $200/mo · 🤖
- Job photos → drafted posts (FB/IG/GBP), 3×/week, client approves in one text
- NOT viral marketing — proof-of-work content that closes residential customers
- Upsell trigger: none needed; pitch with care plan

### 6. Google Ads / Local Services Ads — $250/mo or 12% of spend · 👤+🤖
- LSA setup (Google-screened badge), search campaigns for service keywords
- Landing page included (leverages website pipeline)
- ⚠️ Jordan guides strategy on first client before selling broadly

### 7. Quote kit, automated — $300 one-time · 🤖
- Proposal/quote templates + "get a quote" booking flow on their site (Cal.com or form→email)
- Wins bids while the owner sleeps

### 8. Customer newsletter — $75/mo · 🤖
- Monthly, drafted from their job photos, client approves, sends via their domain (deliverability on our infra)

### 9. Print & signage — per job · 🤝
- Design in-house (tier-1 skills); print via partner vendor
- ⚠️ BLOCKED: needs a print vendor relationship (wholesale signage/business-card printer) — Jordan to pick one local + one online

---

## CONSTRUCTION LANE — /construction.html (premium, Jordan-led)

> Positioning: US-native construction-document expertise + automated drawing pipeline
> (plan analysis → takeoff → shop drawings → QC). Offshore shops compete on price/speed;
> we compete on industry fluency and per-bid pricing with no retainer lock-in.

### 10. Takeoffs & estimates — from $250/trade, $750 whole project · 🤖+👤 48h
- Material quantities + labor hours from issued plans, marked-up PDF back
- Per-bid pricing, no monthly commitment (vs. estimator salary $70–100k/yr)

### 11. Shop drawings — from $90/sheet, package quotes · 🤖+👤 3–7 days
- ezdxf/matplotlib pipeline, two-tier QC vision gate, DWG/PDF deliverable
- Anchor vs market: US shops charge $100–150/sheet; offshore $40–70 (quality/comm risk)

### 12. Blueprint consultation / plan review — $350 flat · 👤 48h
- Pre-bid or pre-construction plan review: discrepancies, missing details, likely RFIs
- Deliverable: prioritized issue list with sheet references

### 13. Submittal & vendor coordination — from $600/mo per project · 🤖+👤
- **The vendor-relationship angle:** submittal log management, chasing vendors/manufacturers
  for cutsheets, product data, O&Ms; tracking review status; resubmittals; closeout docs
- This is the paperwork GCs and subs hate staffing. We are the submittal clerk.
- Upsell: specification research (below)

### 14. Spec & vendor research — from $200/package · 🤖
- Spec-matching, approved-equal alternates (cost-savings subs), lead-time research,
  vendor sourcing with quotes compared. Deliverable: comparison memo + recommendation

---

## AI LANE — /ai.html — "AI, finished." (smart-crowd positioning)

> Intake: client shares their ChatGPT/Claude/Gemini session (export, link, paste).
> The thread IS the spec. We ship the outcome. Never condescend — they did the smart part.
> Phase 1: accept ANY export format. Phase 2: converters → .curt (open standard, dotcurt.org)
> become the intake gate. Phase 3: PM retainer on .curt pipelines.

### 15. Session Rescue — $300 one-time · 🤖+👤 3 days
- One thread → one shipped outcome (site/doc/automation), fixed price quoted BEFORE work
- 30-day break-fix included
- Gate: quote free; if thread = two projects, say so before two invoices

### 16. The Stack — $750 one-time · 🤖+👤 1–2 weeks
- Up to 4 threads finished, prioritized with client, weekly check-in, 60-day break-fix

### 17. AI Ops retainer — $350/mo · 🤖 ongoing
- We run the AI side of their business monthly: new threads → shipped work,
  one-off prompts → documented reusable workflows, kept alive
- "Your AI department"

### 18. AI Project Management retainer — $500+/mo · 👤+🤖 (PHASE 3 — don't sell yet)
- Session intake → project → tracked deliverables, weekly shipping cadence
- Unlocks once .curt intake pipeline is real

**Privacy stance (site copy, non-negotiable):** read to execute, never trained on,
never resold, deleted on request with written confirmation. .curt nod on page = anti-lock-in.

---

## PACKAGING

- **The Works** (tier 1+2 bundle): $295/mo + $900 setup — anchor everything against it
- **Bid Desk** (construction retainer): $1,200/mo — 2 takeoffs + consult hours + submittal log for one active project. For subs bidding 2–4 jobs/month.
- First 3 construction clients = design partners: 20% off for testimonial + portfolio rights
