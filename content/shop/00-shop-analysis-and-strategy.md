# BRANCH B — Shop Section: Competitive Analysis & SEO Strategy

---

## Executive Summary

This document provides the strategic foundation for all shop content on www.masia.jkc-dev.nl/shop/. It covers the comparative analysis between the new shop, the old shop (shop.m-asia.nl), and the competitor (coolenchina.com), along with keyword strategy and structural recommendations.

---

## 1. New Shop Audit: www.masia.jkc-dev.nl/shop/

### Site Structure

The new shop is a WooCommerce-based B2B toy catalog with login-gated pricing. Key characteristics:

- **Shop homepage** → hero + category cards + popular products + testimonials
- **Catalog page** (/catalog/) → full product listing with sidebar filters
- **6 product categories:** Balls, Dolls, Soft Toys, Play Set, Friction Cars, Hanging Sheets
- **Support page** (/support/) → contact info + form + company details
- **Register page** (/register/) → account registration for B2B buyers
- **My Account** (/my-account/) → order management
- **Cart + Checkout** → standard WooCommerce flow
- **About Us** → shared from main site
- **Case Studies, Contact, Blog** → shared from main site

### Navigation

```
Catalog → Balls | Dolls | Soft Toys | Play Set | Friction Cars | Hanging Sheets | On sale
About Us → Our story | Why choose M-Asia? | Our team
My Account
Support
Cart
```

### Content Issues Found

| Page | Issue | Severity |
|---|---|---|
| Shop homepage | No SEO intro text describing the shop/catalog | High |
| Catalog page | No intro text above product grid | High |
| All 6 category pages | Zero category descriptions — empty SEO text | Critical |
| Register page | No explanatory content — just a bare form | High |
| Support page | Content adequate but thin | Medium |
| Category pages | No FAQ sections | Medium |
| All pages | Generic title tags ("Home - M-Asia Shop") | High |
| USP bar | Still references sourcing services, not B2B shop benefits | Medium |

### Key Observations

1. **Login-gated pricing:** Prices are hidden behind login ("Log in to view price"). This is intentional for B2B but needs clear communication about why registration is required.
2. **No "How it works" page:** The old shop had this and it explained the registration → browse → order → ship flow. The new shop lacks this entirely.
3. **Category pages are empty:** No introductory text, no category descriptions, no FAQ. These pages cannot rank.
4. **Missing "On sale" filter page:** The nav links to `?orderby=on_sale` but this is a filter, not a proper landing page.

---

## 2. Old Shop Analysis: shop.m-asia.nl

### Structure
- Homepage with hero, popular products, category cards, testimonials
- Catalog page with all products
- Category pages (Balls, Dolls, Friction Cars, Hanging Sheets, Play Set) — **also no descriptions**
- **How it Works page** — valuable 4-step guide (Register → Browse → Order → Shipping)
- Showroom page
- Register page
- About Us, Contact pages

### Content Strengths
- "How it Works" page clearly explains the B2B buying process
- "HIGH QUALITY TOYS FROM CHINA" — clear positioning
- Strong meta description: "M-Asia offers a wide range of toy products from China"
- Testimonials section carried over from main site
- USP numbers: "Products in stock / Active clients"
- Registration CTA prominent on product cards

### Content Weaknesses
- Category pages have zero descriptive content (same as new shop)
- No FAQ sections anywhere
- No SEO-optimized text on any page
- Generic Yoast setup
- No schema beyond basic page/website

### Key Elements to Preserve
- "How it Works" concept → should become a dedicated section or page on new shop
- "Not yet a buyer at M-Asia? Register for a free account to view the prices" → strong CTA pattern
- B2B registration flow emphasis
- Showroom concept (if physical showroom still exists)

---

## 3. Competitor Comparison: coolenchina.com

Coolen China does not operate a public product shop. Their model is service-based (sourcing on request), not catalog-based. This means:

- M-Asia's shop is a **competitive differentiator** — they actually have stock products available for immediate order
- No direct competitor shop to benchmark against in this niche
- The closest comparison is general B2B toy wholesale platforms

### Competitive Advantage for M-Asia Shop
1. Ready stock in the Netherlands → faster delivery than ordering from China
2. No minimum sourcing project needed → just browse and buy
3. Transparent product range → clients can see what's available before contacting
4. Lower entry barrier than full sourcing → ideal for small retailers testing products

---

## 4. SEO Keyword Strategy for Shop

### Primary Keywords by Page

| Page | Primary Keyword | Intent |
|---|---|---|
| Shop Homepage | wholesale toys from China | Commercial |
| Catalog | toy catalog wholesale | Transactional |
| Balls category | wholesale balls toys | Transactional |
| Dolls category | wholesale dolls China | Transactional |
| Soft Toys category | wholesale soft toys | Transactional |
| Play Set category | wholesale play sets toys | Transactional |
| Friction Cars category | wholesale friction cars toys | Transactional |
| Hanging Sheets category | wholesale hanging play sheets | Transactional |
| Support | M-Asia shop support | Navigational |
| Register | M-Asia wholesale registration | Transactional |

### Content Gaps vs. Old Shop

| Gap | Old Shop | New Shop | Action Needed |
|---|---|---|---|
| How it Works page | Yes | No | Create or add section |
| Category descriptions | No | No | Add to all categories |
| Shop intro text | Minimal | None | Add to homepage + catalog |
| Registration explanation | On product cards | Missing | Add to register + product cards |
| Showroom page | Yes | No | Add if still relevant |
| FAQ on category pages | No | No | Add to all categories |

---

## 5. USP Bar Recommendations for Shop

The current USP bar references the main site messaging. For the shop, replace with:

**Current:**
- Best product sourcing in the Netherlands
- Personal approach
- Customers rate us 4.0/5 on Google

**Recommended for shop:**
- Toys in stock — shipped from the Netherlands
- B2B pricing — register for free
- Quality inspected in China before shipping

---

## 6. Deliverables for Shop Branch

| File | Page | Content Included |
|---|---|---|
| 00-shop-analysis-and-strategy.md | This document | Strategy + analysis |
| 01-shop-homepage.md | Shop Homepage | Full rewrite |
| 02-shop-catalog.md | Catalog page | Intro text + structure |
| 03-category-balls.md | Balls category | Full category content + FAQ |
| 04-category-dolls.md | Dolls category | Full category content + FAQ |
| 05-category-soft-toys.md | Soft Toys category | Full category content + FAQ |
| 06-category-play-set.md | Play Set category | Full category content + FAQ |
| 07-category-friction-cars.md | Friction Cars category | Full category content + FAQ |
| 08-category-hanging-sheets.md | Hanging Sheets category | Full category content + FAQ |
| 09-shop-support.md | Support page | Enhanced content |
| 10-shop-register.md | Register page | Full content + How it Works |
