# Phone Catalog

An e-commerce React application for browsing, searching, and managing tech devices (phones, tablets, accessories). The app provides a modern shopping experience with custom product catalog management, item details, favorites list, shopping cart, sorting, pagination, and theme switching.

## Live Preview

🔗 [Live Demo](https://ferenssofia.github.io/react_apple-catalog/)
> ⚠️ Make sure to test the live preview link in incognito mode to verify public accessibility.

## Design Reference

🎨 [Figma Design Guidelines](https://www.figma.com/file/your-figma-link-here)

## Key Features

* **Product Catalog:** Seamless navigation across Phones, Tablets, and Accessories categories.
* **Shopping Cart & Favorites:** Full cart management (add/remove, quantity adjustment, persistent storage via `localStorage`).
* **Product Details Page:** Interactive image selection, tech specs, color/capacity selectors, and dynamic product recommendations.
* **Search & Filters:** Debounced search input, dynamic URL parameters (`?query=`, `?sort=`, `?page=`, `?perPage=`), multi-attribute sorting, and full pagination support.
* **Theme & UI:** Color theme switching, custom picture slider, skeleton loaders, and smooth hover effects.

## Technologies Used

* **Core:** React, TypeScript
* **State Management:** React Context API (or Redux Toolkit)
* **Routing:** React Router v6
* **Styling:** CSS Modules, SCSS
* **Code Quality & Workflow:** ESLint, Prettier, Husky, GitHub Actions (Auto-deploy)

## Project Structure

```text
src/
├── components/          # Global shared UI components
├── modules/             # Page-specific feature modules
│   ├── HomePage/
│   ├── PhonesPage/
│   ├── CartPage/
│   ├── FavoritesPage/
│   └── shared/          # Shared components across modules
├── types/               # TypeScript interfaces & types
└── styles/              # Global SCSS styles & variables
