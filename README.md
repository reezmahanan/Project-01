# STYLEO CEYLON — Luxury Responsive E-Commerce Architecture

An ultra-modern, production-grade luxury fashion & lifestyle e-commerce storefront for the Sri Lankan market, modeled directly after world-class editorial fashion brands (such as **STYLEO** and **Revivy**).



---

## 🎨 Visual & Interactive Refinements

1. **Floating Rotating Stamp Badge**:
   - Continuous smooth SVG rotation (`NEW COLLECTION • STYLEO CEYLON`).
   - Frosted dark glass circular backing with depth blur and high contrast.
   - Positioned as a direct child of the hero arch card to guarantee zero clipping on any screen resolution.

2. **100% Real Vector SVG Icons (Zero Emojis)**:
   - Clean, professional SVG icons across the announcement bar, search box, product star ratings, payment methods, perks, and footer social links (Instagram, Facebook, Pinterest, and TikTok).
   - Removed all casual emojis to maintain a pure luxury editorial aesthetic.

3. **Interactive Customer Care Suite (Modals & Features)**:
   - **Islandwide Courier Rates Modal**: Comprehensive rate table and timelines for Colombo, Greater Western, Central, Southern, and Outstation regions with Domex and Koombiyo Express.
   - **7-Day Easy Returns & Exchanges Modal**: Step-by-step doorstep courier pickup process and guidelines.
   - **Interactive FAQs Modal**: Accordion-style expandable questions and answers covering Cash on Delivery, Koko Pay in 3, tracking, and handloom fabrics.
   - **WhatsApp Concierge Modal**: Direct WhatsApp launcher with 1-tap prefilled order, sizing, and tracking queries (+94 77 123 4567).

4. **Expanded 16-Piece Luxury Catalog**:
   - Tailored Mocha and Ivory Double-Breasted Blazers
   - Artisanal Handloom Dumbara Kimonos
   - Breathable Silk & Linen Cuban Collar Shirts
   - Minimal White Leather Sneakers & Loafers
   - Sculptural Leather Handbags & Woven Rush Studio Totes
   - Ratnapura Certified Ceylon Blue Sapphire & Star Ruby Jewelry

---

## 📐 Mobile-First Responsive Framework

- **Mobile (< 768px)**:
  - Single-column flow with full-width tap targets ($\ge 44\text{px}$).
  - Horizontal circular category avatar scroller.
  - Slide-down navigation drawer toggled by the hamburger button.
  - Responsive modals and sliding shopping bag drawer.
- **Tablet (`@media (min-width: 768px)`)**:
  - 2-column hero grid.
  - 2-column service ribbon.
  - 3-column featured collection cards.
  - 2-column product grid.
  - Horizontal inline desktop navigation.
- **Desktop (`@media (min-width: 1024px)`)**:
  - Full-scale 2D macro layout floor-plan.
  - 4-column horizontal service ribbon.
  - 3-column product grid.
  - Sticky customer dashboard and live order tracker (`top: 92px`).

---

## 🚀 How to Run

1. Double-click `index.html` in your file explorer to open in any web browser.
2. Or serve locally with:
   ```bash
   python -m http.server 8000
   # or
   npx serve .
   ```
3. Test responsiveness across devices using Chrome/Firefox DevTools (`Ctrl + Shift + M`):
   - **Mobile**: iPhone 14/15 (390px), Samsung Galaxy (360px)
   - **Tablet**: iPad Mini / Air (768px – 820px)
   - **Desktop**: 1024px, 1440px, 1920px
