# Pet Behaviour Services - Booking Widget CDN

## 🚀 Live Deployment
**Website**: https://pbsglenn.github.io/booking-widget-cdn/

This repository hosts the Pet Behaviour Services booking widget as a public CDN via GitHub Pages.

## 📦 Contents

- **React Build Files**: Complete production build of the booking widget
- **Static Assets**: CSS, JavaScript, images, and other resources
- **CORS Headers**: Configured for cross-origin loading from WordPress
- **Cache Optimization**: Proper caching headers for performance

## 🔧 Usage

The booking widget is loaded by WordPress sites using:

```html
<script src="https://pbsglenn.github.io/booking-widget-cdn/static/js/main.925eee3b.js"></script>
<link rel="stylesheet" href="https://pbsglenn.github.io/booking-widget-cdn/static/css/main.a6fea9ea.css">
```

## 🌐 Integration

This CDN is integrated with:
- **Website**: petbehaviourservices.com.au/booking-construction
- **WordPress Theme**: Elementor HTML widget
- **Payment System**: Vercel serverless functions
- **Backend API**: api.petbehaviourservices.com.au

## 🔄 Updates

To update the widget:
1. Build new React files locally
2. Replace files in this repository
3. Push changes to GitHub
4. GitHub Pages automatically updates

## 📊 Features

- ✅ **Public CDN**: No authentication required
- ✅ **Global Performance**: GitHub's worldwide CDN
- ✅ **Automatic HTTPS**: Secure by default
- ✅ **CORS Enabled**: Cross-origin resource sharing
- ✅ **Cache Optimized**: Fast loading and updates

## 🎯 Architecture

```
WordPress → GitHub Pages CDN → Production API + Payment API
```

This provides a robust, free, and fast hosting solution for the booking widget assets.