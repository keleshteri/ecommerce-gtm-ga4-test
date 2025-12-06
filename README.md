# E-commerce GTM & GA4 Test Site

A simple e-commerce test site for testing Google Tag Manager (GTM) and Google Analytics 4 (GA4) implementation.

## 🎯 Purpose
Test and validate e-commerce tracking events through the complete purchase funnel.

## 📊 Tracking Events
- `view_item_list` - Product listing page
- `view_item` - Product detail page  
- `add_to_cart` - Add to cart action
- `begin_checkout` - Checkout page
- `purchase` - Order confirmation

## 🛍️ Purchase Journey
1. **index.html** - Product Listing
2. **product.html** - Product Details
3. **cart.html** - Shopping Cart
4. **checkout.html** - Checkout Form
5. **thankyou.html** - Order Confirmation

## 🏷️ Products
- Smart Phone X - $599.99 (Electronics)
- Laptop Pro - $1,299.99 (Electronics)
- Wireless Headphones - $199.99 (Audio)
- Smart Watch - $349.99 (Wearables)

## 🔧 Setup
- **GTM Container ID**: GTM-PC2LWP59
- **GA4 Measurement ID**: (To be added)
- **Domain**: shop.keleshteri.eu.org

## 🚀 Deployment
Deployed via Cloudflare Pages with automatic deployments from `main` branch.

## 📝 Local Testing
1. Open `index.html` in your browser
2. Go through the purchase flow
3. Check browser console for event logs
4. Use GTM Preview mode for validation

## 🔗 Live URL
https://shop.keleshteri.eu.org (after deployment)

## 📅 Last Updated
December 2024
