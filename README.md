# LUVMIO Fashion Store (prototype)

A single-file website prototype for the LUVMIO fashion brand. Open `index.html` in any browser, no installation needed.

## What is included
- Homepage, shop with filters and sorting, product pages, search, wishlist and bag
- Mobile number and OTP login screens (demo)
- Checkout with 5 steps (demo)
- LUVMIO Hearts: one heart per order, gifts at 5, 7 and 10 orders
- LUVMIO Style Studio: customisable AI model preview (placeholder)
- Rewards games: Spin Wheel, Pick a Bloom, Six Hitter, Blossom Catch, Mind Guess
- Admin dashboard: products, orders, inventory, offers and games, loyalty hearts

## Important
This is a front-end demo. OTP, payments, AI try-on, order storage and admin login are simulated.
A real launch needs a server, database, SMS/OTP provider, payment gateway and secure admin login.
The admin page here is not secure: do not store real customer data in it.

## Put it online with GitHub Pages
1. Create a new repository on github.com (for example `luvmio`).
2. Upload `index.html`, `README.md`, `.nojekyll` and `.gitignore`.
3. Open Settings > Pages. Under "Build and deployment" choose "Deploy from a branch", branch `main`, folder `/ (root)`, then Save.
4. After a minute your site is at `https://YOUR-USERNAME.github.io/luvmio/`.

## Or use git on your computer
```
git init
git add .
git commit -m "LUVMIO store prototype"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/luvmio.git
git push -u origin main
```
