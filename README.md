# Web-Development

A small collection of static HTML projects showcasing frontend UI designs and vanilla JavaScript interactivity. These are example projects you can open in your browser to explore layout, components, and simple DOM-based app logic.

## Files

- `ecommerce-site.html` — A polished mock online store (ShopHub) with a responsive layout, hero section, features, products grid, special offers, testimonials, and a footer. It includes an interactive shopping cart implemented in vanilla JavaScript that stores the cart in `localStorage`, adds/removes items, shows a cart modal, and updates totals and cart counts.

- `todo-list.html` — A focused to-do list application with a clean card UI. Features include adding tasks, marking tasks complete, deleting tasks, and live statistics (total/completed/pending). Tasks persist in `localStorage` and user input is safely escaped before rendering.

## How to view

These are static HTML files — no build or server required. To run locally:

```bash
# from the repository root, open either file in your browser
open ecommerce-site.html
# or
open todo-list.html
```

Or simply double-click the files in your file explorer; they will open in your default browser.

## Highlights & implementation notes

- Both projects use only HTML/CSS/JavaScript (no frameworks) and are responsive for mobile and desktop.
- `ecommerce-site.html` uses a JavaScript array of sample products and renders the product cards dynamically; the cart is saved to `localStorage` and shown in a modal.
- `todo-list.html` stores tasks in `localStorage`, updates stats on each change, and sanitizes user input to prevent HTML injection.

## Suggestions

- Add brief comments at the top of each HTML file explaining how to customize the product list or initial tasks.
- Consider extracting shared CSS into a separate file if you plan to add more projects.

## Try asking

- How can I add a product image field to `ecommerce-site.html` and persist it in the cart?
- Can you make `todo-list.html` support task due dates and sorting by date?
- Could we convert these samples into a single multipage site with a shared stylesheet and header component?
