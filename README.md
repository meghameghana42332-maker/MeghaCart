# MEGHANA MART

A React + Vite e-commerce frontend project for B.K. Meghana.

## Features
- Home page and responsive design
- Men, Women, Kids, Senior Citizens, Shoes and Groceries
- 60 products (10 per category)
- Search and category filtering
- Product details
- Wishlist
- Shopping cart and quantity controls
- Coupons and discount calculation
- Checkout and simulated payment
- Registration/login UI
- Account page
- Order confirmation
- Ready to extend with Node/Express + MySQL and Playwright

## Run
```bash
npm install
npm run dev
```

Open the local URL printed by Vite, usually http://localhost:5173

## Notes
Product photos are loaded from Unsplash URLs for demonstration. For production, download/use licensed product assets and add a backend/database. Payment is simulated and does not process real card credentials.


## MySQL + Node/Express backend

The project now includes a MySQL database schema and Express API.

1. Install Node.js and MySQL.
2. Run `npm install`.
3. Execute `database/meghana_mart.sql` in MySQL Workbench.
4. Copy `backend/.env.example` to `backend/.env` and enter your MySQL password.
5. Start the API with `npm run server`.
6. Start the frontend with `npm run dev`.
7. API health check: `http://localhost:5000/api/health`.

The frontend currently keeps its shopping state locally; `src/api.js` provides the backend API functions for wiring product/auth/order screens to MySQL next.
