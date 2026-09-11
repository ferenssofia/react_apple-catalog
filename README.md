# Phone Catalog

An e-commerce React application for browsing, searching, and managing tech devices (phones, tablets, accessories). The app provides a modern shopping experience with custom product catalog management, item details, favorites list, shopping cart, sorting, pagination, and theme switching.

## Live Preview
[Live Demo](https://ferenssofia.github.io/react_apple-catalog/)


## Key Technical Highlights & Functionality
- Interactive UI & Components: Engineered custom visual elements, including dynamic dynamic photo sliders (PictureSlider, ProductsSlider), product details pages with image selectors, and breadcrumb navigation.
- State Management & Persistence: Implemented global state handling (React Context / Redux) integrated with localStorage to seamlessly retain shopping cart items, item quantities, and favorited products across user sessions.
- Data Handling & Navigation: Integrated server-side pagination, sorting dropdowns, real-time search, smooth UI loading/error states, and custom dynamic routing (NotFoundPage).
- Advanced Features: Added multi-theme support (light/dark mode), custom SVG sprite icons processing, and internationalization readiness.


## Engineering Challenges & Solutions
- Complex Feature Coordination: Orchestrated seamless interactions between independent UI components—including interactive sliders, sorting filters, server-side pagination, and dynamic product detail views—without breaking layout or data flow.
- Persistent State Management: Designed a robust state architecture (via React Context / Redux) connected with localStorage to preserve shopping cart contents, favorite items, and user preferences seamlessly across browser sessions.
- Responsive & Adaptive Design: Engineered fluid layouts from Figma specs that maintain full usability, interactive touch targets, and visual fidelity across all mobile, tablet, and desktop viewports.
- State Sync & Performance Tuning: Prevented unnecessary component re-renders during high-frequency state updates (such as live search inputs, theme toggles, and item quantity adjustments) to maintain smooth 60fps animations.
- Resilient Error Handling: Built comprehensive fallback states, custom NotFound routes, and user-friendly error banners to gracefully capture API failures and missing media resources without crashing the app.
- Cross-Browser Quality Assurance: Performed systematic cross-browser testing and debugging, configuring code quality tools (ESLint, Prettier) to enforce strict formatting and prevent regressions.


## Installation & Setup
To install the project and run it locally, follow these steps:

**Clone the repository:**

```bash
   git clone https://github.com/username/react_device-catalog.git
   ```
**Navigate to the project directory:**

```bash
   cd react_device-catalog
   ```
**Install dependencies:**

```bash
   npm install
   ```
**Start the local development server:**

```bash
   npm start
   ```
**Build & deploy:**

```bash
   npm run build
   npm run deploy
   ```

## Technologies Used

- React: For building the user interface.
- TypeScript: For type safety and better development experience.
- Vite: For fast and optimized build tooling.
- pnpm: For package management.
- CSS Modules: For scoped and modular CSS styling.
- React Context / Redux: For state management of cart and favorites.
- Sass: For advanced CSS styling capabilities.
- React Router: For routing and navigation.
- @vitejs/plugin-react-swc: For React and TypeScript support.
- vite-svg-sprite-wrapper: For handling SVG sprites.
- Husky: For Git hooks to enforce code quality.
- ESLint: For linting JavaScript and TypeScript code.
- Prettier: For code formatting.