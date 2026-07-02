# Project Prototype: Daibuy Discount & Shopping Demo

## Overall Visual Direction
- Follow the visual style established in `design3.html`.
- Make the design approachable and friendly for non-technical users (e.g., homemakers or people less familiar with technology).
- Use clear labels, generous spacing, simple language, and intuitive navigation.

---

## Part 1: Restaurant Discount Search Page

Build a single-page website where users can search for restaurant discounts. The page should display both regular and "suggested" discounts, with search results ranked by relevance.

### Data
- Create a JSON file named `restaurants.json` containing **20 dummy restaurants**.
- Restaurants should span **3 distinct food styles** (e.g., Italian, Japanese, Mexican).
- Each food style should have multiple restaurants.
- Restaurant names should be immediately recognizable as belonging to their food style.
- Within each food style, mark **one specific restaurant as "suggested"**.

### Discounts
- Discounts should be capped at **20% value**.
- Include multiple discount types, for example:
  - `$20 off`
  - `20% off`
  - `Buy 2 Get 1 Free`
- Store discount data in a separate JSON file named `discounts.json`.

### Page Behavior
- Create an HTML file (e.g., `discounts.html`) that loads both `restaurants.json` and `discounts.json` as dependencies.
- Implement a simple search function that:
  - Ranks restaurants by relevance to the user's query.
  - Always places the top "suggested" restaurant for the matched food style at the top of the results.
  - When a user searches for a specific restaurant, also surfaces a relevant similar restaurant that is marked as "suggested" near the top.

---

## Part 2: Mobile Shopping Demo Page

Build a mobile-style demo page that simulates a shopping app. The demo starts on a product list and transitions to a checkout screen, where a notification appears offering a cheaper alternative.

### Layout
- Design the page to look like a mobile phone screen in the center of the page.
- Use an aspect ratio of approximately **20:9**, similar to common modern smartphones.

### Data
- Create a JSON file named `products.json` containing a list of **daily-use items** (e.g., toothbrush, trousers, shampoo, notebook).
- Each item should have its own detail view/page within the HTML file.

### Product Detail / Checkout Page
For each product, create a checkout-style page that displays:
- Product name and image.
- Product price.
- Shipping price.
- Estimated shipping time.
- Dummy user delivery address.
- Dummy factory/warehouse address.
- A "Checkout" button.

### Daibuy App Notification
- First, design a Daibuy app icon that matches the visual style of `design3.html`.
- When the user taps the checkout button on a product page, display an iPhone-style notification.
- The notification must include:
  1. The Daibuy app icon.
  2. A clear message stating that a cheaper alternative exists.
  3. The source of the cheaper alternative.
  4. The cheaper price.

---

## Deliverables
1. `restaurants.json` — 20 dummy restaurants across 3 food styles with suggested flags.
2. `discounts.json` — discount data with capped 20% value and varied discount types.
3. `discounts.html` — search page for restaurant discounts.
4. `products.json` — list of daily-use shopping items.
5. `shopping.html` — mobile demo page with product list, checkout views, and Daibuy notification.
6. Any image assets for the Daibuy app icon (or inline SVG).
