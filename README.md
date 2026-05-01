# VIVID — Pakistan's Premier Fashion Store

A modern multi-category e-commerce fashion website built with React 18. The platform features 10 distinct store sections, a complete shopping cart with WhatsApp checkout, wishlist functionality, and a responsive dark-themed interface with custom animations.

## Features

- **Multi-category store**: Home, Men, Women, Kids, Streetwear, Accessories, Shoes, Luxury, New In, Sale
- **Dynamic theming**: Each category has its own color scheme and visual identity
- **Product cards**: Display pricing, discounts, ratings, color variants, and detailed descriptions
- **Shopping cart**: Slide-out panel with quantity controls and real-time total calculation
- **Wishlist**: Save products to a separate list with quick add-to-cart option
- **WhatsApp checkout**: One-click order summary sent directly to the business WhatsApp number
- **Search and filters**: Real-time product search, sort by price or rating, filter by product tags
- **3D hero section**: Animated floating product cards with rotating rings and particle effects
- **Responsive design**: Optimized for desktop, tablet, and mobile screens
- **Image fallback**: Automatic placeholder for missing product images

## Pages

| Page | Products | Primary Color |
|------|----------|---------------|
| Home | Hero + Categories | Pink |
| Men | 12 | Blue |
| Women | 12 | Soft Pink |
| Kids | 8 | Yellow |
| Streetwear | 10 | Green |
| Accessories | 10 | Gold |
| Shoes | 10 | Purple |
| Luxury | 6 | Vintage Gold |
| New In | 8 | Teal |
| Sale | 12 | Orange |

## Technology Stack

- **React 18** (UMD via CDN) with ReactDOM
- **Babel Standalone** for in-browser JSX compilation
- **CSS** with custom keyframe animations
- **Google Fonts**: Bebas Neue and Outfit
- **Pexels** and Unsplash for product photography

## Project Structure

The entire application is contained in a single `index.html` file. No build tools, package managers, or server setup required.

## Getting Started

1. Clone or download the repository
2. Open `index.html` in any modern web browser

## WhatsApp Configuration

To link your WhatsApp Business number, update the following line in the source code:

```javascript
const WA_NUMBER = '923001234567';
