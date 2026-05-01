🛒 E-Commerce Frontend (React Only)

Problem Statement:
Ek fully functional e-commerce frontend application build karo using React only (no backend). App ka goal hai users ko products browse karne, filter karne, cart manage karne, aur checkout flow simulate karne ka smooth experience dena.

🎯 Objective

Students ko React ke core + advanced concepts practically use karne hain by building a real-world scalable UI system.

🔑 Core Features

1. Product Listing Page
   Products grid (image, title, price, rating)
   Static JSON data (local file ya mock API)
   “Add to Cart” button
2. Product Detail Page
   Individual product view
   Image gallery (multiple images)
   Product description
   Quantity selector
   Add to cart
3. Search & Filtering
   Search bar (by product name)
   Filter by:
   Category
   Price range
   Rating
   Sort options (Low to High, High to Low)
4. Cart Management
   Add / Remove items
   Increase / Decrease quantity
   Total price calculation
   Persist cart using localStorage
5. Checkout Flow (Frontend Only)
   Address form
   Order summary
   “Place Order” button (no real payment)
   Success screen
   ⚛️ React-Specific Requirements (Important)
   Component Architecture
   Reusable components:
   ProductCard
   Navbar
   CartItem
   FilterSidebar
   State Management
   Use:
   useState (local state)
   useContext (global cart state)
   (Redux optional bonus)
   Routing
   Use React Router:
   / → Product listing
   /product/:id → Product details
   /cart → Cart page
   /checkout → Checkout
   Hooks Usage
   useEffect (data loading, localStorage sync)
   Custom hooks (optional bonus)
   Performance Optimization (Bonus)
   useMemo / useCallback
   Lazy loading (React.lazy)
   🎨 UI Expectations
   Clean, modern UI
   Responsive (mobile + desktop)
   Loading states & empty states
   ⭐ Bonus Features (Advanced Students)
   Wishlist functionality
   Dark mode toggle
   Pagination / Infinite scroll
   Debounced search
   Skeleton loaders
