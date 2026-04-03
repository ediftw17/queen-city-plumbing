# Build Brief — Queen City Plumbing

## Task
Build a complete, production-quality single-file landing page and save it as index.html in the current directory.

Read C:/workspace/projects/website-building-agency/clients/jf-air-and-heat/index.html first.
Match that level of quality: full inline CSS, schema.org JSON-LD, Google Fonts, smooth scroll, mobile responsive.

## Business Data
- **Name:** Queen City Plumbing
- **Tagline:** Charlotte's Most Trusted Plumbers
- **Phone:** (704) 634-4466
- **Address:** 2209 Graham Park Dr, Charlotte, NC 28273
- **Hours:** Mon-Fri 7:00 AM - 6:00 PM | Saturday available
- **Founded:** 2009
- **Owner:** Justin McFalls (second-generation plumber, 20+ years experience)
- **Rating:** 4.8 stars (1,383+ reviews)
- **Schema type:** Plumber (schema.org)
- **Canonical URL:** https://queen-city-plumbing.vercel.app

## Services
1. Emergency Plumbing Repairs (24/7 availability)
2. Leak Detection & Repair
3. Drain Cleaning & Unclogging
4. Sewer Line Repair & Replacement
5. Water Heater Installation & Repair (tank + tankless)
6. Garbage Disposal Repair & Installation

## Design System
- **Palette:**
  - Navy: #0B1724 (background)
  - Navy-mid: #132030
  - Navy-light: #1A2C42
  - Blue: #1E40AF (primary accent)
  - Blue-light: #3B82F6
  - Orange: #F97316 (CTA, highlights)
  - Orange-dark: #EA6C0C
  - White: #FFFFFF
  - Gray-400: #9CA3AF
  - Gray-200: #E5E7EB
- **Fonts:** Bebas Neue (headings/display) + DM Sans (body, 300/400/500/600) from Google Fonts
- **Aesthetic:** Dark, premium, trustworthy service brand. High contrast. Orange CTAs pop against navy.

## Page Sections (in order)
1. **Nav** — sticky top, logo left ("Queen City Plumbing"), phone number right as orange button
2. **Hero** — full viewport, navy bg, large headline (Bebas Neue), subtitle, two CTAs: orange "Call Now" + outline "Get Free Estimate". Trust badges row below: 4.8 stars, 1,383+ Reviews, 15 Years, BBB Accredited
3. **Services** — dark card grid (3 cols desktop, 1 col mobile), each card: SVG icon, service name, 1-line description
4. **Why Choose Us** — 4 stat blocks: 15+ Years, 1,383+ Reviews, 4.8 Stars, Family-Owned Since 2009
5. **About** — Justin McFalls, second-generation plumber, short paragraph about family business and expertise
6. **Trust Signals** — BBB accredited, licensed & insured, same-day service, 100% satisfaction guarantee
7. **CTA Banner** — full-width orange-to-navy gradient, headline "Plumbing Emergency? We Answer 24/7.", large phone number, call button
8. **Footer** — dark navy, name, address, hours, phone, copyright

## Technical Requirements
- Single file: all CSS inline in style tag, no external CSS files
- Google Fonts via link tag
- Schema.org JSON-LD for Plumber type with address, phone, hours, geo coords (latitude: 35.1580, longitude: -80.9195), aggregateRating ratingValue 4.8 reviewCount 1383
- Smooth scroll behavior
- Mobile responsive (hamburger nav on mobile, stacked cards)
- OG meta tags pointing to https://queen-city-plumbing.vercel.app
- All CTAs link to tel:7046344466
