# Project 1: Responsive E-Commerce Web Application (STYLEO Ceylon)

### Student Information
- **Name:** M. Reezma Hanan
- **Module:** IT2308 - Web Application Development (Project 1)
- **GitHub Repository:** [https://github.com/reezmahanan/Project-01](https://github.com/reezmahanan/Project-01)

---

## 📌 Project Overview
This project is a fully responsive e-commerce web application created for **STYLEO Ceylon**, a modern Sri Lankan clothing and lifestyle brand. I developed this project for Project 1 to practice and demonstrate fundamental frontend web development skills.

The application is built completely from scratch using **pure HTML, CSS, and Vanilla JavaScript**, without using any CSS frameworks (such as Bootstrap or Tailwind) or JavaScript libraries/frameworks (such as React or jQuery).

---

## 🛠️ Technologies Used
- **HTML5:** Semantic tags used throughout the layout (`<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>`).
- **CSS3:** Mobile-first approach, CSS Grid for the main layout, Flexbox for UI components, CSS custom properties (variables), and fluid typography with `clamp()`.
- **Vanilla JavaScript (ES6+):** Pure JavaScript for state management, catalog rendering, cart actions, search/filter, and modal popups.
- **Browser LocalStorage:** To store cart items, saved wishlist items, user login session, and placed orders so that data persists after refreshing the page.

---

## ✨ Key Features Implemented

1. **Product Catalog & Filtering:**
   - 16 curated fashion items with realistic Sri Lankan pricing (in LKR).
   - Category filter tabs (All, Clothing, Footwear, Accessories, Jewelry).
   - Search bar to filter products by name or keywords with an instant clear button.
   - Sort dropdown to sort by price (low to high, high to low) and customer ratings.

2. **Shopping Bag & Cart Management:**
   - Slide-out side drawer for the shopping bag.
   - Increase (`+`), decrease (`-`), and remove item controls with live price calculations.
   - Dynamic progress bar showing how much more to add to unlock free islandwide delivery (free above Rs. 8,500).

3. **User Authentication (Sign In & Sign Out):**
   - Clean sign-in modal dialog with email/phone and password fields.
   - Top header button switches between **Sign In** and **Sign Out** based on the login state.
   - **Cart Protection Gate:** Users must sign in before adding items to the shopping bag. If an unauthenticated user clicks "Add to Bag", the sign-in modal opens automatically, and once signed in, the item is added to their bag.
   - Logging out clears the current cart so guest visitors cannot see previous session items.

4. **Order Checkout & Live Dashboard:**
   - Checkout modal to enter customer details (name, phone, email, district, city, address) and select payment method (Cash on Delivery, Koko Pay in 3, Bank Transfer, Visa/Mastercard).
   - Submitting an order creates a traceable courier tracking number (e.g. `DOMEX-LK-XXXXX`).
   - The sticky sidebar dashboard displays total orders placed, total spent, and live order status.

5. **Wishlist:**
   - One-click heart toggle on product cards to save items to wishlist, updated live in the header badge.

6. **Customer Care & Information Modals:**
   - Islandwide Delivery Rates table (Domex & Koombiyo timelines across Colombo, Suburbs, and Outstation).
   - 7-Day Returns & Exchanges policy details.
   - Frequently Asked Questions (FAQ) accordion.
   - Direct WhatsApp Concierge contact link (+94 77 123 4567).

---

## 📱 Responsive Layout & Breakpoints
The layout was designed mobile-first and tested for smooth adaptability across screen sizes:
- **Mobile (< 768px):** Single-column layout, touch-friendly tap targets, hamburger slide-down menu.
- **Tablet (768px – 1023px):** Two-column product grid, inline horizontal navigation bar, multi-column search controls.
- **Desktop (≥ 1024px):** Three-column product grid, top announcement bar, and a sticky order tracking sidebar.

---

## 📁 Project Structure
```text
Project 1/
│
├── index.html      # Main HTML page with semantic landmarks and modals
├── style.css       # Complete stylesheet (CSS Grid, Flexbox, Mobile-First media queries)
├── app.js          # Vanilla JS state engine, product catalog, cart logic, and event listeners
└── README.md       # Project documentation
```

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/reezmahanan/Project-01.git
   ```
2. Open the project directory:
   ```bash
   cd Project-01
   ```
3. Open `index.html` in any web browser (Chrome, Firefox, Edge, Safari) by double-clicking the file.  
   *(No server setup or npm install is needed)*

---

## 👤 Author
- **M. Reezma Hanan**
- GitHub: [@reezmahanan](https://github.com/reezmahanan)
