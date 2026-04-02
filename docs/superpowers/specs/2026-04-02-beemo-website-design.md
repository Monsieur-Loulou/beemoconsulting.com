# Beemo Consulting FZCO — Website Design Spec

## Overview

A single-page credibility website for Beemo Consulting FZCO, a Dubai-based boutique management consulting firm specializing in AI product strategy and go-to-market for tech companies.

**Goal:** Establish credibility for anyone who lands on the site (prospective clients, partners, investors). Not a lead generation funnel — no forms, no CTAs beyond a contact email.

**Tone:** Modern, bold, tech-forward. Opinionated language. Boutique firm positioning (not solo freelancer, not big consultancy).

## Visual Direction

- **Theme:** Dark (near-black background, white/light text)
- **Aesthetic:** Linear/Vercel energy — clean, confident, minimal
- **Typography:** Modern sans-serif, generous whitespace
- **No images or illustrations** — the words carry the page
- **Responsive:** Must look good on mobile and desktop
- **Use /frontend-design skill** for implementation to ensure high design quality

## Page Structure

### 1. Hero (full viewport height)

```
BEEMO CONSULTING

We help tech companies turn AI into products people actually use.

Product strategy. Go-to-market. Execution advisory.
Dubai · Global
```

- Bold headline, centered or left-aligned depending on design direction
- "BEEMO CONSULTING" as wordmark/logo (text-only, no graphic logo)
- No CTA button — credibility site, not a funnel

### 2. Value Propositions (three stacked blocks)

Manifesto style — one after another, not a grid.

**Block 1:**
```
Launch AI products faster.

We work with founding teams and product leaders to go from prototype to
market-ready. Define the right product scope, nail positioning, and ship
with confidence.
```

**Block 2:**
```
Find product-market fit.

AI capabilities are not products. We help you identify who actually needs
what you've built, validate willingness to pay, and design the go-to-market
motion that lands.
```

**Block 3:**
```
Scale what works.

Once you have traction, we help you build the playbook — pricing, packaging,
channel strategy, expansion sequencing. Structured growth, not guesswork.
```

### 3. Credibility Strip

```
Our team has worked with

Google · Amazon · IOG (Cardano) · Cybergun · Graffiti
```

- Horizontal line of company names (no logos)
- "Our team" framing — firm language, not personal CV
- Subtle, not the focus of the page

### 4. Approach / Philosophy

```
Consulting that ships.

We don't write decks that collect dust. We embed with your team,
pressure-test your assumptions, and stay until the product is in market.

No juniors. No filler. Senior operators who've built and launched at scale.
```

- Opinionated, differentiating from traditional consulting
- Short and punchy

### 5. Footer

```
BEEMO CONSULTING
Beemo Consulting FZCO · Dubai, UAE

alexandre@beemoconsulting.com
```

- Minimal — company name, legal entity, location, contact email
- No social links, no newsletter

## Technical Requirements

- **Static HTML + CSS.** No framework, no build step.
- **Single page, single file or minimal file structure** — deployable anywhere (Netlify, Vercel, GitHub Pages, S3).
- **Performance:** Should score 95+ on Lighthouse. No JS required (unless for subtle animations).
- **SEO basics:** Proper meta tags, Open Graph tags, page title, meta description.
- **Favicon:** Simple text-based or geometric favicon matching the brand.

## Content Notes

- All copy is final as written above
- Company email: alexandre@beemoconsulting.com
- Legal entity: Beemo Consulting FZCO
- Location: Dubai, UAE
- Founder background (for context, not displayed): Google (Marketing, Paris), Amazon, IOG/Cardano, Cybergun, Graffiti
