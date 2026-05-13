# 🖌️ Sticker Haven

A modern, responsive e-commerce website for premium stickers. Built with pure HTML, CSS, and vanilla JavaScript - no dependencies required!

## ✨ Features

### Core Functionality
- 🛒 **Shopping Cart** - Add/remove items with quantity management
- 💾 **Cart Persistence** - Cart data saved to browser's LocalStorage
- 🔍 **Category Filtering** - Filter stickers by nature, abstract, funny, and gaming categories
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- 🎨 **Modern UI** - Beautiful gradients, smooth animations, and hover effects

### Product Features
- 8 Featured stickers with images and pricing
- Dynamic grid layout that adapts to screen size
- Product cards with smooth hover animations
- Real-time cart count display

### User Experience
- 🔔 **Toast Notifications** - Smooth notifications when items are added to cart
- 🎯 **Modal Cart Display** - Clean, organized shopping cart modal
- ⚡ **Instant Updates** - Real-time cart total and item count
- 🎭 **Smooth Animations** - Professional transitions and effects

## 📁 Project Structure

```
stickers/
├── index.html          # Single-file web application (17.5 KB)
└── README.md          # This file
```

## 🚀 Getting Started

### Option 1: Open Directly
Simply download `index.html` and open it in your browser. No installation or server required!

### Option 2: Live Preview
1. Go to your GitHub repository
2. Enable GitHub Pages in settings
3. Access your site at `https://imhasib359-bot.github.io/stickers`

## 🛠️ How It Works

### Sticker Data Structure
```javascript
{
  id: 1,
  name: "Mountain Sunset",
  price: 3.99,
  category: "nature",
  image: "https://..."
}
```

### LocalStorage Cart Management
The cart is automatically saved when you:
- Add items to cart
- Remove items from cart
- Complete checkout

The cart persists across browser sessions!

### Category Filtering
Click category buttons to filter stickers:
- **All** - Show all stickers
- **Nature** - Nature-themed stickers
- **Abstract** - Abstract and geometric designs
- **Funny** - Humorous and cute stickers
- **Gaming** - Gaming and tech stickers

## 💻 Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - No frameworks or libraries
- **LocalStorage API** - Browser-based data persistence

## 📊 Included Stickers (8 Total)

| Name | Price | Category |
|------|-------|----------|
| Mountain Sunset | $3.99 | Nature |
| Abstract Waves | $2.99 | Abstract |
| Funny Cat | $2.49 | Funny |
| Forest Path | $3.49 | Nature |
| Gaming Controller | $4.99 | Gaming |
| Retro Geometric | $2.79 | Abstract |
| Dancing Doggo | $2.99 | Funny |
| Cyberpunk City | $4.49 | Gaming |

## 🎯 Key Functions

### `addToCart(stickerId)`
Adds a sticker to the cart or increases quantity if already present.

### `filterStickers(category)`
Filters the sticker grid by selected category.

### `toggleCart()`
Opens/closes the shopping cart modal.

### `checkout()`
Processes checkout and clears the cart.

### `saveCartToStorage()` / `loadCartFromStorage()`
Manages LocalStorage persistence.

### `showToast(message)`
Displays a toast notification.

## 🎨 Customization

### Change Colors
Update the gradient colors in the CSS:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Add More Stickers
Add to the `stickers` array in the JavaScript:
```javascript
{
  id: 10,
  name: "Your Sticker",
  price: 3.99,
  category: "nature",
  image: "https://..."
}
```

### Modify Pricing
Edit individual sticker prices in the `stickers` array.

## 🌐 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

## 📝 Notes

- This is a demo e-commerce site. The checkout button shows a success message but doesn't process real payments.
- Images are loaded from Unsplash (external URLs)
- Cart data is stored locally in your browser only

## 🚀 Future Enhancements

Consider adding:
- Backend API integration
- User authentication
- Real payment processing (Stripe, PayPal)
- Product reviews and ratings
- Search functionality
- Wishlist feature
- Order history
- Admin dashboard for inventory management

## 📄 License

Free to use and modify!

## 👨‍💻 Created By

**imhasib359-bot**

---

**Happy shopping! 🎉**
