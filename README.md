# Product Store

This project is a sleek and modern e-commerce storefront for electronics, built entirely with HTML, CSS, and vanilla JavaScript. It's a fully client-side application that demonstrates a range of interactive features common in online stores.

 <!-- Replace with a screenshot of your project -->

## ✨ Features

*   **Dynamic Product Catalog:** Products are rendered dynamically from a JavaScript array.
*   **Search, Sort & Filter:**
    *   Live search through product names and descriptions.
    *   Sort products by name (A-Z, Z-A) or price (Low-High, High-Low).
    *   Filter products by category.
*   **Interactive UI:**
    *   A responsive design that works on mobile, tablet, and desktop.
    *   A "glassmorphism" design with blurred, transparent elements.
    *   A light/dark theme toggle to suit user preference.
    *   A "quick view" modal to see product details without leaving the page.
*   **Shopping Cart & Wishlist:**
    *   Add/remove items to a shopping bag and a wishlist.
    *   Adjust item quantities directly in the bag.
    *   All data is persisted in the browser's local storage, so the cart and wishlist are saved between visits.
*   **Simulated Checkout:** A complete checkout flow from the shopping bag to a final payment form, including basic email validation.

## 🛠️ Tech Stack

*   **HTML5**
*   **CSS3** (with CSS Variables for theming)
*   **Vanilla JavaScript** (ES6+)
*   **Font Awesome** for icons.

## 🚀 Getting Started

This is a static website. No build steps or dependencies are required.

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/product-store.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd product-store
    ```
3.  Open the `index.html` file in your favorite web browser.

## 📂 File Structure

```
├── css/
│   └── style.css       # All styles for the application
├── images/             # Product images and logos
├── js/
│   └── script.js       # All application logic and product data
├── index.html          # Main product page (homepage)
├── admin.html          # Admin panel for managing products
├── contact.html        # Contact information page
├── privacy.html        # Privacy policy page
└── terms.html          # Terms of service page
```
