# Katie Flinn Design — Brand Brief & SEO Architecture
**Prepared by:** Hybrid Real Estate Web Services
**Date:** 2 April 2026
**Status:** AWAITING CLIENT SIGN-OFF — do not build until approved

---

## 1. BUSINESS OVERVIEW

**Business Name:** Katie Flinn Design
**Owner:** Katie Flinn
**Location:** PO Box 1141, Elsternwick VIC 3185 (previously New Brighton, NSW 2483)
**Email:** hello@katieflinndesign.com
**Instagram:** @katieflinndesign (~41K followers)
**Facebook:** facebook.com/katieflinndesign

**What she does:** Katie is a self-taught jewellery maker specialising in lost wax cast, sculptural fine jewellery using sterling silver, solid gold, Australian opals, sapphires, and diamonds. She handcrafts every piece from start to finish — currently from her van while travelling Australia full-time.

**Revenue streams (4 pillars):**

1. **Ready-made jewellery** — Rings, pendants, daggers. Price range $190–$2,295 AUD (shop)
2. **Custom commissions** — Artist-led bespoke pieces starting at $2,500, most clients $4,000–$7,000. 12-week lead time
3. **Online courses** — Two modules on Podia: Wax Jewellery Making ($850) + Metal Finishing & Stone Setting ($599), or bundled at $1,222. Plus standalone tools modules at $60 each
4. **Business mentoring** — 3-month Mastermind program at $1,800 ($600/month) for creative entrepreneurs

**Current status note:** Katie is "taking a step back from the usual hustle to focus on creating in a slower, more thoughtful way" — the site needs to reflect this intentional, unhurried energy while still driving conversions.

---

## 2. TECH STACK SNAPSHOT (CURRENT SITE)

| Element | Current |
|---------|---------|
| **Platform** | Squarespace 7.1 (commerce-enabled) |
| **Course hosting** | Podia (katieflinn.podia.com) — lifetime access model |
| **Domain** | katieflinndesign.com |
| **Analytics** | Google Analytics 4 (G-2ZBPVC88BX) |
| **Tag Manager** | GTM-N7GPFWH |
| **Facebook Pixel** | 327540794544886 |
| **Heatmapping** | Hotjar (hjid: 3401663) |
| **reCAPTCHA** | Standard + Enterprise keys |
| **SSL** | Active (via Squarespace) |
| **Payment** | Squarespace Commerce (AUD, AU shipping default) |
| **Email/Newsletter** | /sub page (likely Squarespace email campaigns or Mailchimp) |
| **Schema markup** | WebSite, Organization, LocalBusiness — all present |
| **Booking/forms** | Custom enquiry form on /custom-made-jewellery (native Squarespace form) |

**Key issues identified:**
- Outdated announcement bar still referencing "December 20th 2021" shipping
- No meta descriptions on most pages
- Two different postal addresses across pages (NSW vs VIC)
- No sitemap reference visible
- Course platform is entirely external (Podia) — no native course pages on the site
- No booking/calendar integration for calls
- No review collection system
- Font stack defaults to Squarespace system fonts (no custom typography)

---

## 3. BRAND EXTRACTION

### Logo
Two logo assets identified:
- **Primary wordmark:** KFD BLUE V3.png — "Katie Flinn Design" blue text logo
- **Icon/monogram:** KFD EYE.png — mystical eye symbol used in footer

### Colour Palette

| Role | Colour | Approximate Hex | Notes |
|------|--------|-----------------|-------|
| **Primary brand** | Soft blue | ~#6FB3E5 | Used in logo, highlight elements, link colour |
| **Background** | Off-white / cream | ~#FAF9F6 | Squarespace default, clean gallery feel |
| **Text** | Dark charcoal | ~#333333 | Body text |
| **Accent** | Gold / warm metallic | — | Implied by jewellery imagery; not explicit in CSS |

**Recommendation:** The current palette is minimal — mostly blue logo on white with dark text. For the redesign, I'd suggest introducing a richer palette that matches her jewellery aesthetic: deep navy/midnight, warm gold accent, soft cream, and keeping the blue as a signature accent. This needs Katie's input.

### Typography
- Current: Squarespace system defaults (no Typekit ID set, no Google Fonts detected)
- **Recommendation:** A serif/display heading font to convey artisan luxury + a clean sans-serif body. Candidates: Playfair Display / Cormorant Garamond for headings, Inter / DM Sans for body.

### Brand Voice
Extracted from all site copy, About page, course pages, and social bio:

| Trait | Evidence |
|-------|----------|
| **Direct & unfiltered** | "No bullshit. No fluff." (course page) |
| **Casual & personal** | "Hey! I'm Katie" — first-name, first-person throughout |
| **Confident & passionate** | "I absolutely love business, personal growth, creativity" |
| **Fantasy/mystical** | Product names: Frostmourne, Dragon Eye, Shadowmoon, Astral Moonblade, Duskfall Realm |
| **Artist-first** | "It's about sharing your vision and letting me bring it to life in my own artistic way" |
| **Empowering** | "My true soul mission on this earth is to empower creatives" |
| **Australian but global** | Ships worldwide, travels Australia, learned in India |

**Voice summary:** Warm, direct, mystical, empowering. She talks like a friend who happens to be an incredibly skilled artisan. No corporate polish — raw authenticity with confidence. Fantasy-world naming convention is a signature differentiator.

### Imagery Style
- High-quality macro product photography (rings on hands, detail shots of stone settings)
- Natural/organic backgrounds (earth, sand, stone, fabric)
- Warm, moody lighting — not clinical studio white
- Van life / travel / workshop behind-the-scenes on socials
- Student work showcases for course marketing

### Brand Values (from Sustainability page)
- Recycled metals exclusively
- Australian opals sourced direct from miners
- Sustainable FSC-certified packaging
- Monthly "Pay The Rent" contributions to Indigenous communities
- Banks with B-Corp certified Bank Australia (no fossil fuels, gambling, arms)

---

## 4. SOCIAL MEDIA INTEL

### Instagram (@katieflinndesign)
- **Followers:** ~41K
- **Bio name:** "KATIE FKN FLINN" (with fire heart emoji)
- **Content themes:** Product showcases, wax carving process, course promotion, van life updates, gemstone sourcing, student success stories, business mentoring
- **Visual style:** Moody, warm, close-up macro jewellery shots — consistent with site imagery
- **Engagement driver:** Behind-the-scenes process content and student transformations

### Facebook
- Page exists but minimal activity (2 reviews, not yet rated)
- Not a primary channel

### Press/Features
- Featured in The Gem Monarchy: "A Glimpse Into A Fantasy World"
- Featured in Jewellery World: "Ethereal jewellery handcrafted with love"
- Listed in "25 Australian Jewellers to Follow on Instagram" (QReport)

---

## 5. EXISTING CONTENT INVENTORY

### Pages on current site:

| Page | URL | Status | Content Quality |
|------|-----|--------|----------------|
| Home | / | Live | Minimal — just intro + 3 section links |
| About | /about | Live | Strong — full origin story, milestones, philosophy |
| Custom Jewellery | /custom-made-jewellery | Live | Excellent — detailed FAQ, pricing, full enquiry form |
| Course Landing | /jewellery-making-course | Live | Good — modules, pricing, student testimonials |
| Course Links | /courselinks | Live | Detailed — full curriculum breakdown, AfterPay links |
| Shop | /shop | Live | 21 products listed, good imagery |
| Sold Gallery | /sold-gallery | Live | 29+ past pieces with multiple images each — strong portfolio |
| Contact | /contact | Live | Basic — simple form, email, address |
| Sustainability | /Sustainability | Live | Good — ethical sourcing, packaging, banking |
| FAQ | /faq | Live | 10 questions covering process, materials, care |
| Mastermind | /mastermind | Live | Business mentoring offering — $1,800 |
| T&Cs | /termsandconditions | Live | Standard |
| Newsletter | /sub | Live | Email signup |

### Testimonials available:
- 5 student showcases on course page (Saskia Heyns, Jordy Todd, Gemma Hewson, Cristy Kantor, Paris Strada)
- Press quotes from The Gem Monarchy and Jewellery World
- No formal customer review system in place

---

## 6. SEO ARCHITECTURE — PROPOSED SITE STRUCTURE

### Version 1: Single-Flow Redesign (One-Page with Anchored Sections)

```
katieflinndesign.com/
│
├── #hero          → "Otherworldly Jewellery, Handcrafted with Soul"
├── #about         → Katie's story (condensed) + sustainability callout
├── #jewellery     → Shop preview + custom commissions CTA
├── #gallery       → Portfolio carousel (sold pieces + current)
├── #courses       → Tiered course cards + student success
├── #mentoring     → Mastermind program overview
├── #testimonials  → Student + customer quotes
├── #faq           → Expanded FAQ (12+ questions, schema-marked)
├── #contact       → Contact form + book a call CTA
└── #footer        → Social links, email, legal
│
├── /courses       → SEPARATE PAGE: Tiered course breakdown (new)
├── /reviews       → SEPARATE PAGE: Review funnel (new — our skill)
└── /book          → SEPARATE PAGE: Book a call (Calendly/Cal.com embed)
```

### Version 2: Multi-Page Replica (Same Structure as Current, Redesigned)

```
katieflinndesign.com/
│
├── /              → Homepage (redesigned hero, sections, CTAs)
├── /about         → Full about page (story, values, sustainability merged)
├── /custom-jewellery → Custom commissions (form, FAQ, pricing, process)
├── /shop          → Product catalogue (Squarespace commerce or static showcase)
├── /sold-gallery  → Portfolio of past work
├── /courses       → NEW: Tiered course page with curriculum detail
├── /course-links  → Redirect to /courses (consolidate)
├── /mastermind    → Business mentoring
├── /faq           → Expanded FAQ
├── /sustainability → Ethical practices (or merge into /about)
├── /contact       → Contact form + book a call
├── /reviews       → Review funnel page (new — our skill)
├── /book          → Book a call page (new)
└── /terms         → T&Cs
```

### Target Keywords by Page

| Page/Section | Primary Keyword | Secondary Keywords |
|-------------|----------------|-------------------|
| Homepage | handcrafted jewellery australia | artisan jewellery, lost wax cast jewellery, australian jeweller |
| About | katie flinn jewellery designer | australian jewellery maker, handmade jewellery artist |
| Custom | custom jewellery australia | bespoke engagement ring, custom opal ring, commission jewellery |
| Shop | buy handmade jewellery online | opal ring australia, sterling silver ring handmade, gold jewellery handcrafted |
| Gallery | handcrafted opal rings gallery | custom engagement ring gallery, artisan jewellery portfolio |
| Courses | jewellery making course online | learn jewellery making, lost wax casting course, wax carving course |
| Mentoring | creative business mentoring | jewellery business course, small business coaching creatives |
| FAQ | jewellery making FAQ | how to start making jewellery, lost wax casting explained |
| Reviews | katie flinn design reviews | customer reviews handmade jewellery |

### On-Page SEO Spec

Every page will include:
- Unique `<title>` tag: `Primary Keyword | Katie Flinn Design`
- Unique `<meta description>` (150-160 chars with CTA)
- Single `<h1>` with target keyword
- Logical H2/H3 hierarchy
- Image `alt` attributes on every image
- Internal linking between sections
- LocalBusiness schema markup
- FAQ schema on FAQ section
- Open Graph tags for social sharing
- Canonical tags
- Structured data for Products (shop) and Courses (course page)

---

## 7. PROPOSED COURSE PAGE STRUCTURE (NEW — TIERED)

This is a new dedicated page replacing the scattered course info across /jewellery-making-course and /courselinks.

```
/courses

├── Hero: "Learn to Make High-End Jewellery"
│
├── Tier 1: TOOLS MODULES ($60 each)
│   ├── Wax Tools Module
│   └── Metal Tools Module
│   └── CTA: "Start Here — Get the Checklists"
│
├── Tier 2: INDIVIDUAL COURSES
│   ├── Wax Jewellery Making — $850 (7h 45min, lifetime access)
│   └── Metal Finishing + Stone Setting — $599 (5h 50min, lifetime access)
│   └── CTA: "Enrol Now" / AfterPay option
│
├── Tier 3: FULL BUNDLE — $1,222 (save $227)
│   └── CTA: "Get the Full Experience"
│
├── Student Showcase (5 students with before/after + Instagram links)
├── Curriculum Breakdown (accordion — what's covered in each module)
├── FAQ Section (4+ course-specific questions)
└── CTA: "Still not sure? Book a free intro call"
```

---

## 8. FEATURE & INTEGRATION MAP

### Core Features (both versions)
- [x] Mobile-first responsive design
- [x] Clear primary CTA above the fold ("Shop" / "Book a Custom Piece" / "Learn Jewellery Making")
- [x] Contact form with email delivery
- [x] Click-to-email on mobile
- [x] Social media links (Instagram, Facebook)
- [x] Google Analytics 4 tag
- [x] Facebook Pixel
- [x] Cookie consent notice
- [x] FAQ with schema markup
- [x] LocalBusiness + Organization schema
- [x] Open Graph tags

### New Features to Add
- [ ] **Book a Call** — Calendly or Cal.com embed (replacing lack of booking)
- [ ] **Review funnel page** — Our standard review-page skill (star rating → Google Reviews or private feedback → Notion via Make.com)
- [ ] **Tiered course page** — Dedicated page with pricing tiers and curriculum
- [ ] **Upgraded custom enquiry form** — Current form is good but can be streamlined with better UX
- [ ] **Instagram feed embed** — Pull recent posts for social proof
- [ ] **Portfolio/gallery lightbox** — For sold gallery and shop
- [ ] **Newsletter signup** — Prominent placement with lead magnet
- [ ] **Student showcase carousel** — Course social proof

### Existing Integrations to Preserve
| Integration | Status | Action |
|-------------|--------|--------|
| GA4 (G-2ZBPVC88BX) | Active | Carry over tag |
| GTM (GTM-N7GPFWH) | Active | Carry over tag |
| Facebook Pixel (327540794544886) | Active | Carry over tag |
| Hotjar (3401663) | Active | Carry over tag |
| Podia (course platform) | Active | Link to external — or embed if possible |
| Squarespace Commerce | Active | Decide: keep Squarespace for shop, or static showcase? |

### New Integrations Recommended
| Integration | Purpose | Priority |
|-------------|---------|----------|
| Calendly / Cal.com | Book a discovery call for custom commissions | High |
| Make.com + Notion | Review funnel backend | High (part of review page skill) |
| Google Search Console | Monitor search performance | High |
| Mailchimp / ConvertKit | Email marketing (if not already in use) | Medium |
| Google Business Profile | Local SEO + reviews | Medium |

---

## 9. FAQ CONTENT PLAN (EXPANDED — 14 QUESTIONS)

Merging existing FAQs from multiple pages + new questions based on search intent:

1. What metals does Katie Flinn Design work with?
2. Where are the gemstones sourced from?
3. How does lost wax casting work?
4. How long does a custom piece take?
5. What is the minimum budget for a custom commission?
6. Can I provide my own gemstones?
7. What kinds of pieces does Katie NOT make?
8. Do you ship internationally?
9. Why has my skin gone black/green after wearing my jewellery?
10. How do I care for my opal jewellery?
11. What's included in the jewellery making courses?
12. Do I need prior experience to take the course?
13. How much will I need to invest in tools?
14. What if I'm not ready for a full course — can I start small?

All 14 will be marked up with FAQ schema for Google featured snippet eligibility.

---

## 10. DELIVERABLES SUMMARY

| # | Deliverable | Description |
|---|------------|-------------|
| 1 | **Version 1 — Single-Flow Redesign** | One-page site with anchored sections, upgraded content, modern design, all CTAs, SEO-optimised |
| 2 | **Version 2 — Multi-Page Replica** | Same page structure as current site but fully redesigned with new visual treatment |
| 3 | **Tiered Course Page** | Standalone /courses page with pricing tiers, curriculum, student showcases |
| 4 | **Review Funnel Page** | Star-rating → Google Reviews redirect or private feedback capture (our standard skill) |
| 5 | **Book a Call Page** | Calendly/Cal.com embed for custom commission enquiries |
| 6 | **Build Report** | Full handover document with SEO spec, integration notes, recommendations |

---

## 11. OPEN QUESTIONS FOR SIGN-OFF

Before building, I need your call on these:

1. **Colour palette direction** — Keep the existing blue-on-white minimal look, or go richer (navy/gold/cream) to match the jewellery aesthetic?
2. **Shop functionality** — Static product showcase (images + "enquire" CTA), or do we need actual e-commerce checkout? Current site uses Squarespace Commerce.
3. **Course hosting** — Keep Podia as the external platform and just link to it, or build a more integrated course landing experience?
4. **Booking tool** — Calendly, Cal.com, or something else for "Book a Call"?
5. **Mastermind page** — Include in both versions or just V2 (multi-page)?
6. **Google Review link** — Do we have Katie's Google Business Profile URL for the review funnel?
7. **Newsletter platform** — What's she currently using? Mailchimp, ConvertKit, Squarespace email?
8. **Domain/hosting** — Is the plan to deploy on Cloudflare Pages (our standard), or does she want to stay on Squarespace?

---

*Ready for sign-off. No code will be written until these decisions are locked in.*
