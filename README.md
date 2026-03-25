# Aurelia — DTC Formal Dress Brand Landing Page

A high-conversion landing page prototype for a DTC (Direct-to-Consumer) affordable formal dress brand targeting the US market ($120 average order value).

## Live Preview

Open `index.html` directly in any modern browser — no build step or server required.

## Design Strategy

Based on the core framework: **Shorten Value Discovery → Quick Value Delivery → Build Trust**

Addressing four key user barriers:
| Barrier | Solution |
|---------|----------|
| No interest | Visual-first hero with aspirational lifestyle imagery |
| No perceived benefit | AI-powered personalized dress quiz with instant recommendations |
| Trust concerns | 3,200+ customer reviews, real photos, transparent policies |
| High info cost | One-click interactions, smart size finder, quick-reply chatbot |

## Core Features

### 1. Hero Carousel
- 3-slide auto-rotating hero with crossfade transitions
- Featured product card with dynamic content per slide
- Dual CTA: AI Quiz entry + Shop by Occasion

### 2. AI Style Quiz (Core Conversion Engine)
- 6-step interactive quiz: Occasion → Vibe → Color → Length → Silhouette → Size
- Image-based option cards for visual selection
- Smart Size Finder with height/weight/preference inputs
- Personalized product results grid
- Integrated lead capture: "Email my results + get 15% off"

### 3. Shop by Occasion
- 4 scene cards: Wedding Guest / Prom / Cocktail / Date Night
- Atmospheric imagery with hover effects

### 4. Real Stories (Reviews)
- 10 customer review cards with photos
- Auto-scrolling carousel with hover-pause
- Each card includes star rating, review text, and "Shop this Look" link

### 5. Multi-Touch Lead Capture
- Quiz results email capture
- Newsletter subscription ("Stay in the Glow")
- Floating "Be the First to Know" panel with email signup
- Coupon modal (15% off first order)
- All touchpoints include privacy policy and unsubscribe messaging

### 6. AI Chatbot
- Modern chat UI with typing indicators
- 6 quick-reply chips: Shipping, Returns, Size Guide, Order Tracking, Styling Tips, Deals
- Contextual auto-responses per topic
- Free-text input with fallback response

### 7. Floating Action Buttons
- "Get My 15% Off" — opens coupon modal
- "Be the First to Know" — opens trend alert signup panel
- "Ask a Question" — opens chatbot

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 | Single-file architecture |
| Tailwind CSS (CDN) | Utility-first styling |
| Vanilla JavaScript | All interactivity, no framework dependency |
| Google Fonts (loli.net mirror) | Playfair Display + Inter |
| Font Awesome 6 | Icons |

## Project Structure

```
DTC_Onboarding/
├── index.html              # Complete landing page (HTML + CSS + JS)
├── README.md               # This file
├── images/
│   ├── hero1.png           # Hero carousel slide 1
│   ├── hero2.png           # Hero carousel slide 2
│   ├── hero3.png           # Hero carousel slide 3
│   ├── scene-wedding.png   # Occasion card
│   ├── scene-prom.png      # Occasion card
│   ├── scene-cocktail.png  # Occasion card
│   ├── scene-datenight.png # Occasion card
│   ├── quiz/               # Quiz step option images
│   │   ├── occasion-*.png  # 6 occasion atmosphere photos
│   │   ├── vibe-*.png      # 6 style moodboard images
│   │   ├── length-*.png    # 4 gold line-art illustrations
│   │   └── silhouette-*.png# 6 gold silhouette illustrations
│   └── reviews/            # Customer review photos
│       └── review-01~10.jpg
```

## Design Highlights

- **Color palette**: Gold (#C9A84C) primary, Rose Gold (#D4A974) secondary, Ivory (#FAF8F5) background
- **Typography**: Playfair Display (headings) + Inter (body) for elegant readability
- **Animations**: Hero crossfade, scroll reveal, quiz glow border, AI button pulse, auto-scroll reviews
- **Mobile-ready structure**: Built with responsive Tailwind classes (optimized for desktop showcase)

## Notes

- This is a **front-end prototype** — form submissions are simulated (no backend)
- Quiz product recommendations use a client-side filtering algorithm
- All assets are local — works fully offline after download
- Fonts use `fonts.loli.net` CDN mirror (accessible from mainland China)
