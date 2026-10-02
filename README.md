# HomeMart Furniture & Decor — Frontend Internship Project

A complete responsive furniture e-commerce frontend based on the supplied internship brief/screenshots.

## Included
- Home page with hero banner, room categories, featured products and benefits
- Product listing with category navigation and search
- Product detail page with quantity selector, specs and wishlist
- Shopping cart with quantity adjustment and totals
- Checkout page with shipping + simulated payment selection
- Header login/logout controls and account dashboard
- Create new account / registration
- Account dashboard with profile and simulated order history
- Wishlist saved in browser localStorage
- About Us and Contact Us pages
- Responsive desktop/tablet/mobile design
- Warm brown / cream / gold design system from the brief
- Real furniture/interior photography loaded from Unsplash image URLs
- No database required; data is stored in localStorage for the demo

## Run
Open `index.html` in a browser. For the best development experience, use VS Code Live Server or any simple static HTTP server.

## Demo authentication
Create an account from **Create account**. The user account and session are simulated with localStorage. This is intentionally frontend-only and does not provide production-grade password security.

## Photos
The product/category images use Unsplash-hosted photographs. The supplied project can be run without downloading image assets because the image URLs are embedded in the frontend. Internet access is required for those photographs to display.

Photo references include free-to-use Unsplash pages for living-room, bedroom, dining and office imagery, including:
- https://unsplash.com/photos/a-living-room-filled-with-furniture-and-a-flat-screen-tv-3wSe-BHJ1kI
- https://unsplash.com/photos/a-bedroom-with-a-bed-in-a-room-_-VFMl0TKlg
- https://unsplash.com/photos/a-dining-table-with-plates-and-utensils-on-it-zeuJtC4-g1Q
- https://unsplash.com/photos/an-empty-office-desk-in-front-of-a-window-HsMVmGngmWM
- https://unsplash.com/photos/a-bright-living-room-with-a-sofa-and-coffee-table-GCboWw1wwxk

## Main files
- `index.html` — page shell and navigation
- `styles.css` — complete responsive styling
- `app.js` — products, routing, cart, auth, wishlist, checkout and localStorage logic
