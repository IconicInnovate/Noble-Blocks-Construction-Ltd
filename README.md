# Noble Blocks and Properties Ltd — Website Design & Development Brief

> **Purpose of this document:** Single source of truth for the UI/UX Designer and Developer building the Noble Blocks and Properties Ltd website. It defines the business, the (two) audiences it serves, required pages/features, brand direction, and deliverables.

---

## 1. Project Snapshot

|                             |                                                                                                                                                                        |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Client**                  | Noble Blocks and Properties Ltd                                                                                                                                        |
| **Industry**                | Concrete Block Manufacturing **+** Real Estate Services (dual business)                                                                                                |
| **Tagline**                 | "Building Dreams, One Block at a Time."                                                                                                                                |
| **Location**                | Osun State, Nigeria                                                                                                                                                    |
| **Primary contact channel** | WhatsApp/Call — see Section 13 (number needs confirming)                                                                                                               |
| **Email**                   | nobleblocks07@gmail.com                                                                                                                                                |
| **Social handle**           | Instagram: `noble_propertiesLtd`                                                                                                                                       |
| **Project type**            | Marketing / lead-generation website with a lightweight property-listings section. No dedicated website currently exists — Instagram is the only online presence found. |

**One-line brief:** Noble Blocks and Properties Ltd is two businesses in one: a **concrete hollow block manufacturer/supplier** for builders and contractors, and a **real estate services firm** (valuation, development, land sales/lease, facility management, consultancy). The website needs to serve both buyer intents clearly, without either one burying the other.

---

## 2. About the Business

**What they actually do (from client-provided material):**

_Building Materials_

- Premium concrete hollow blocks, made to any size, for construction projects

_Real Estate Services_

- Property Valuation
- Property Development
- Land and Landed Properties for Sales & Lease
- Facility Management
- Property Consultancy Services
- (also referenced: Property Management, Property Design & Development)

**Mission:** To provide innovative solutions to challenges in the real estate sector, delivering sustainable value and exceeding client expectations through excellence, integrity, and creativity.

**Vision:** To stand out as a leading real estate brand that redefines property ownership and community development through professionalism, innovation, and trust — creating lasting impact.

**Core Values (spells the company name — a nice hook for the About page):**

- **N** — Novelty
- **O** — Ownership
- **B** — Boldness
- **L** — Loyalty
- **E** — Excellence

---

## 3. Business Goals (why we're building this)

1. **Give a two-sided business one coherent front door** — a contractor looking for blocks and a family looking for land are different visitors with different questions; the homepage needs to route each to the right place within seconds.
2. **Generate leads for both sides** — WhatsApp/call for quick block orders; enquiry form for real estate (valuation, land purchase, facility management).
3. **Look credible where Instagram can't** — a real website with a proper "About/Mission/Vision" section signals permanence that a social page doesn't, especially useful for real estate trust.
4. **List actual inventory** — land/property listings currently live only in scattered Instagram posts; the site should give them a permanent, browsable home.
5. **Support the "NOBLE" values story** — the values acrostic (Novelty, Ownership, Boldness, Loyalty, Excellence) is distinctive brand material already created by the client; the site should use it, not waste it.

---

## 4. Target Audience

**Audience A — Block buyers**

- Individual builders, contractors, and site engineers needing concrete hollow blocks in bulk or custom sizes.
- Price- and reliability-sensitive; wants to know sizes available, strength/durability claims, and how to order/get a quote fast.

**Audience B — Real estate clients**

- Individuals/families looking to buy or lease land/property in Osun State.
- Property owners needing valuation, facility management, or consultancy.
- Investors looking for development opportunities.

The site's IA (Section 6) is built around **cleanly separating these two audiences from the homepage down**, rather than mixing block sales and land listings on the same pages.

---

## 5. Competitive / Reference Benchmarking

- **Local Osun real estate agencies** (e.g., agencies operating out of Osogbo) tend to lean on address, phone number, and personal-service messaging rather than large digital portfolios — trust is built through visible local presence and direct contact, not scale. Noble should match this: address/service-area, phone/WhatsApp, and a simple enquiry form need to be prominent, not buried in a "Contact" page.
- **Construction/materials suppliers** in this space typically win business by making **specs and ordering friction-free** — block sizes, strength grade, minimum order quantity, delivery area, and a fast quote path matter more than polish.
- From the earlier Horizon Construct Firm benchmarking (Elalan/Setraco): a clean **categorized listings pattern** (filter by type/purpose) and a **short, credible About/Mission/Vision section** apply well here too — Noble already has strong mission/vision/values copy ready to use.

---

## 6. Sitemap (Phase 1 scope)

```
Home  (splits into two clear paths: "Order Blocks" / "Real Estate Services")
├── About Us
│   └── Mission / Vision / Core Values (N-O-B-L-E)
├── Concrete Blocks
│   ├── Product info (sizes, strength/durability, custom sizing)
│   ├── How to Order (bulk/custom quote request)
│   └── Delivery/service area
├── Real Estate Services
│   ├── Property Valuation
│   ├── Property Development
│   ├── Land & Landed Properties (Sales & Lease)
│   ├── Facility Management
│   └── Property Consultancy Services
├── Property Listings
│   ├── Filter: For Sale | For Lease
│   ├── Filter: Land | Residential | Commercial
│   └── Listing Detail Page (template, reused per property)
├── Contact / Enquiry
│   ├── General enquiry form
│   ├── Block quote request form
│   └── Real estate enquiry form
└── (Phase 2, not in this build) Blog/Articles, Client Testimonials
```

**Footer (every page):** logo, tagline, quick links to both business lines, WhatsApp/call, email, Instagram, service area (Osun State), copyright.

**Persistent element:** sticky WhatsApp/call button — but it should be smart enough (or at least labeled clearly) to not confuse a block buyer with a real estate enquiry; consider two distinct CTAs ("Order Blocks" vs "Property Enquiry") rather than one generic button.

---

## 7. Page-by-Page Requirements

### 7.1 Home

- Hero: strong visual (construction site / blocks + a property image), headline built around the tagline "Building Dreams, One Block at a Time."
- **Two-path split section** directly under the hero: "Need Concrete Blocks?" vs "Looking for Property?" — each a card/button leading into its own journey. This is the single most important UX decision on the site given the dual business model.
- Mission/Vision teaser, linking to full About page.
- Featured property listings (if available at launch).
- Trust strip: years active, area served, WhatsApp number, "Osun State" — actual figures to be confirmed with client (Section 13).
- Final CTA band with both contact paths.

### 7.2 About Us

- Company story, Mission, Vision, and the NOBLE core values as a visual acrostic (this is strong existing brand content — worth a dedicated, well-designed section, not just a text block).

### 7.3 Concrete Blocks

- What's offered: sizes available, strength/durability claims, custom sizing.
- Minimum order quantity, delivery/service area (confirm with client).
- Clear "Get a Quote" CTA (WhatsApp deep link or form).
- Product photography needed (see Section 10 — not yet provided).

### 7.4 Real Estate Services

- One page with five clearly labeled sections (Valuation, Development, Land Sales & Lease, Facility Management, Consultancy) — short description of what's included in each, plus a CTA into the enquiry form.

### 7.5 Property Listings

- Grid of available land/properties with filter by Sale/Lease and Type.
- Each listing opens a **Listing Detail Page**: title, location, size/price (where disclosable), description, image gallery, "Enquire about this property" CTA.
- **Note:** no listings were provided in the source material — this section needs real inventory from the client before it can go live with content (can launch with a "New listings coming soon" state if needed).

### 7.6 Contact / Enquiry

- WhatsApp/call (primary), email, Instagram, service area.
- Two lightweight forms (or one form with a "What are you enquiring about?" toggle): Block order vs Real estate enquiry — routes to the right team/inbox if they're handled differently internally.

---

## 8. Brand & Visual Direction (for UI/UX Designer)

Source material: Instagram post graphics (mission/vision/values slides, a construction-site promotional flyer) and the circular house-and-roof logo mark.

- **Current state:** the client's existing social graphics use several unrelated colors (dark red for Mission, orange for Vision, teal for Core Values, plus a purple-toned construction photo). This reads as template-driven rather than an intentional brand system — **recommend consolidating to a disciplined palette** for the website rather than carrying all four colors over.
- **Suggested direction:** a primary **navy or deep blue** (professional, real-estate-appropriate, and echoes the blue in the existing logo mark), paired with a **warm amber/gold or terracotta accent** (ties to construction/blocks and creates visual distinction from the "real estate" blue when needed to separate the two business lines). Neutral grays/off-white for structure.
- **Consider color-coding the two business lines subtly** (e.g., blocks/construction content leans warmer, real estate content leans into the primary blue) so users always have a visual cue for which "side" of the site they're on — without looking like two unrelated brands.
- **Typography:** clean, confident sans-serif for both headings and body — this brand's credibility comes from clarity and trust cues (mission/vision/values, contact info), not decorative type.
- **Logo:** existing circular blue roof/house mark with "NOBLE BLOCKS AND PROPERTIES LTD." wordmark — request the vector source file from the client.
- **Imagery needed:** real photos of blocks/product and real property/land photos are essential — the current source material has almost no product photography (see Section 10).
- **Tone:** trustworthy, straightforward, local — this is a hands-on, service-driven local business, not a luxury developer. Design should avoid overly slick "luxury real estate" tropes that don't match the block-manufacturing side of the business.

---

## 9. Content & Assets Provided by Client

- [x] Logo (circular blue roof/house mark + wordmark)
- [x] Mission / Vision / Core Values copy (strong, ready to use)
- [x] Service list (blocks + 5 real estate services)
- [x] Contact email
- [x] Instagram handle

### Still needed from client before design starts

- [ ] **Confirmed phone/WhatsApp number** — the two source posts show two different numbers (`08085689980` / `wa.me/+2348085689980` vs. `+2348085689989` in the post caption). **This must be resolved before the number appears anywhere on the live site.**
- [ ] Vector logo file (SVG/AI/EPS)
- [ ] Real photography: blocks/product shots, past work, site photos
- [ ] Real property/land listings (at least a handful, to populate the listings section at launch)
- [ ] Concrete block specs: available sizes, strength grade/PSI, minimum order quantity, delivery area/fees
- [ ] Company history: years active, projects/properties handled, service area beyond Osun (if any)
- [ ] Office/yard address, if there's a physical location for block pickup or visits

---

## 10. Deliverables

**UI/UX Designer**

1. Consolidated brand direction (palette, type, logo usage) based on Section 8
2. Low-fidelity wireframes — all Phase 1 pages, mobile + desktop, with special attention to the homepage "two-path split"
3. High-fidelity mockups — all Phase 1 pages, mobile + desktop
4. Component/style guide (colors, type scale, buttons, listing cards, forms)
5. Clickable prototype for stakeholder review
