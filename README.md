# Materialism

<p align="center">
  <img src="https://img.shields.io/badge/🆓_FREE-Open_Source-brightgreen?style=for-the-badge" alt="Free & Open Source">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Blogger-orange?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/Material_Design-3-purple?style=flat-square" alt="Material Design 3">
</p>

<p align="center">
  <strong>🎉 100% FREE & OPEN SOURCE</strong><br>
  A premium looking, Material Design 3-inspired Blogger template with modern aesthetics, blazing-fast performance, and exceptional user experience. Built with clean code and attention to detail.
</p>

---

## ✨ Why Materialism?

| Feature | Description |
|---------|-------------|
| 🎨 **Premium Design** | Google Material Design 3 inspired aesthetics with glassmorphism, smooth animations, and premium typography using Geist font |
| ⚡ **Blazing Fast** | Optimized for Core Web Vitals with lazy loading, preconnect hints, and minimal render-blocking resources |
| 📱 **Fully Responsive** | Perfect experience on desktop, tablet, and mobile with adaptive layouts and touch-friendly interactions |
| 🔍 **SEO Optimized** | Structured data (JSON-LD), semantic HTML, Open Graph, Twitter Cards, and optimized meta tags out of the box |
| 💬 **Threaded Comments** | Beautiful Material Design comment system with nested replies, author badges, and tree connectors |
| 🚀 **AJAX Navigation** | Smooth page transitions without full reloads (SSR version) |
| 🎯 **Featured Post Hero** | Eye-catching hero section with featured post widget integration |
| 🏷️ **Smart Label Pages** | Dynamic label filtering with elegant status indicators |
| 🌐 **Mobile-First** | No `?m=1` parameter - single responsive experience for all devices |
| ⬆️ **Back to Top** | Smooth scroll-to-top button with visibility toggle |
| 💀 **Skeleton Loading** | Beautiful loading animation when navigating between posts |
| 🕐 **Reading Time** | Automatic reading time estimation for posts |
| 🖼️ **High-Res Images** | Auto-upgrade Blogger images to full resolution (s1600) |

---

## 📦 Two Versions Available

This template comes in **two flavors** to suit different needs:

### 1. Materialism OG (Original)
> Location: `/Non SSR/Materialism_OG_v1.xml`

🔗 **[Live Demo](https://materialismog.blogspot.com/)**

The classic version with straightforward implementation. Perfect for beginners.

### 2. Materialism SSR (Server-Side Rendered) ⭐ Recommended
> Location: `/SSR/Materialism_SSR_v1.xml`

🔗 **[Live Demo](https://www.wahib.web.id/)**

The enhanced version with AJAX-powered navigation, skeleton loading, and dynamic content loading. Best for optimal user experience.

---

## ⚖️ Comparison: OG vs SSR

| Feature | OG Version | SSR Version |
|---------|:----------:|:-----------:|
| **Installation Complexity** | ⭐ Simple | ⭐⭐ Moderate |
| **Page Navigation** | Full reload | AJAX (no reload) |
| **Initial Load Speed** | Faster | Slightly slower |
| **Subsequent Navigation** | Normal | ⚡ Instant |
| **SEO Compatibility** | ✅ Excellent | ✅ Excellent |
| **Browser History** | Native | Custom pushState |
| **Label Page Filtering** | Server-side | Client-side AJAX |
| **Pagination** | Traditional | JSON Feed API |
| **Skeleton Loading** | ❌ No | ✅ Yes |
| **Back to Top Button** | ❌ No | ✅ Yes |
| **Reading Time** | ❌ No | ✅ Yes |
| **High-Res Image Upgrade** | ❌ No | ✅ Yes |
| **Header Scroll Shadow** | ❌ No | ✅ Yes |
| **Code Complexity** | Lower | Higher |

---

## 🆕 What's New in v1.0.0 SSR

### SEO Enhancements
- ✅ Theme-color meta tag for mobile browsers
- ✅ Robots meta (`index, follow`)
- ✅ Conditional author meta for posts
- ✅ Complete Open Graph tags (`og:locale`, `og:description`, `og:url`, `og:image`)
- ✅ Complete Twitter Card support (`summary_large_image` for posts, `summary` for homepage)
- ✅ Featured image support for social sharing

### UI/UX Improvements
- ✅ **Header Scroll Shadow** - Subtle shadow appears when scrolling
- ✅ **Back to Top Button** - Fixed button that appears after scrolling 400px
- ✅ **Skeleton Loading** - Smooth loading animation when clicking article links
- ✅ **Reading Time Estimation** - Automatically calculates and displays read time
- ✅ **High-Res Image Upgrade** - Blogger images automatically upgraded to s1600
- ✅ **Better Thumbnails** - Related posts use w800 resolution for crisp display

### CSS Refinements
- ✅ Read more pill: increased font-weight (600) for better visibility
- ✅ H2 headings: added letter-spacing (-0.2px) for premium look
- ✅ Image captions: increased font-size (0.875rem) for readability
- ✅ Breadcrumbs: improved selector with lighter font-weight
- ✅ Empty state: minimum height for search results
- ✅ Mobile sp-meta: flex-wrap and row-gap for better wrapping

---

## ✅ Pros & Cons

### Materialism OG

**Pros:**
- 🟢 Simpler to customize and maintain
- 🟢 Works without JavaScript (graceful degradation)
- 🟢 Faster initial page load
- 🟢 Better for blogs with minimal label navigation
- 🟢 Easier to debug

**Cons:**
- 🔴 Full page reload on every navigation
- 🔴 No smooth transitions between pages
- 🔴 Traditional Blogger pagination limitations
- 🔴 Missing advanced features (skeleton loading, back-to-top, reading time)

---

### Materialism SSR

**Pros:**
- 🟢 SPA-like experience with instant navigation
- 🟢 Smooth AJAX transitions between label pages
- 🟢 Dynamic content loading without reload
- 🟢 Better perceived performance after initial load
- 🟢 Modern web app feel
- 🟢 Skeleton loading for premium UX
- 🟢 Back-to-top button for long articles
- 🟢 Auto reading time estimation
- 🟢 High-res image auto-upgrade

**Cons:**
- 🔴 Requires JavaScript to function fully
- 🔴 More complex codebase
- 🔴 Slightly heavier initial payload
- 🔴 More difficult to customize

---

## 🚀 Quick Start

1. **Download** the XML file for your preferred version
2. **Go to** Blogger Dashboard → Theme → Customize → Edit HTML
3. **Backup** your current theme (important!)
4. **Replace** all code with the Materialism XML
5. **Save** and preview your new theme

---

## 🎨 Customization Guide

### Change Brand Name
Search for the SVG text element in the header and footer:
```xml
<text>YourBrand<tspan fill="#1A73E8">.</tspan></text>
```

### Change Accent Color
Modify the CSS variable in `:root`:
```css
:root {
    --color-accent: #1A73E8;     /* Primary accent color */
    --color-accent-bg: #E8F0FE;  /* Light accent background */
}
```

### Customize Navigation Links
Find the `.nav-links` section in the Header widget:
```xml
<div class='nav-links'>
    <a class='nav-link' href='/p/about.html'>About</a>
    <a class='nav-link' href='/search/label/Technology'>Technology</a>
    <!-- Add more links here -->
</div>
```

### Update Meta Description
Find the fallback description in the head section:
```xml
<meta content='Your custom description here.' name='description'/>
```

### Change Twitter Handle
Update the twitter:site meta tag:
```xml
<meta content='@your_twitter_handle' name='twitter:site'/>
```

### Customize Reading Time Language
Find the reading time script and update the text:
```javascript
readingTimeEl.textContent = readingTime + ' min read';
// Change to: readingTime + ' menit baca' for Indonesian
```

---

## 🏗️ Template Structure

```
Materialism/
├── SSR/
│   ├── Materialism_SSR_v1.xml    # Main SSR template (recommended)
│   └── current.xml               # Development version
├── Non SSR/
│   └── Materialism_OG_v1.xml     # Original version
└── README.md                      # This file
```

---

## 🔧 Key CSS Variables

| Variable | Default | Description |
|----------|---------|-------------|
| `--font-base` | `'Geist', sans-serif` | Primary font family |
| `--color-bg` | `#FFFFFF` | Background color |
| `--color-text` | `#212121` | Primary text color |
| `--color-meta` | `#5F6368` | Secondary/meta text color |
| `--color-accent` | `#1A73E8` | Accent/link color |
| `--color-accent-bg` | `#E8F0FE` | Light accent background |
| `--radius-l` | `24px` | Large border radius |
| `--radius-m` | `16px` | Medium border radius |
| `--radius-s` | `8px` | Small border radius |
| `--width-max` | `1240px` | Max container width |
| `--header-height` | `72px` | Header height |

---

## 📱 Responsive Breakpoints

| Breakpoint | Target |
|------------|--------|
| `> 1024px` | Desktop (3-column grid) |
| `768px - 1024px` | Tablet (2-column grid) |
| `< 768px` | Mobile (1-column grid, drawer menu) |

---

## 🔍 SEO Features

- ✅ **JSON-LD Structured Data** - BlogPosting schema for articles, WebSite schema for homepage
- ✅ **Open Graph Tags** - Complete OG meta for Facebook sharing
- ✅ **Twitter Cards** - Large image cards for posts, summary for homepage
- ✅ **Canonical URLs** - Proper canonical link tags
- ✅ **Semantic HTML** - Proper heading hierarchy and semantic elements
- ✅ **Robots Meta** - `index, follow` for search engines
- ✅ **Mobile Viewport** - Proper viewport meta tag
- ✅ **Theme Color** - Browser theme color for mobile

---

## 💬 Comment System Features

- Threaded/nested replies with visual tree connectors
- Author badge for post author's comments
- Admin detection via CSS probe method
- Reply button with inline form
- Material Design 3 styled comment blocks
- Responsive avatars (40px parent, 32px replies)

---

## ⚡ Performance Optimizations

- Non-blocking font loading with `media="print"` swap
- Preconnect hints for Google Fonts and Blogger CDN
- Lazy loading for below-fold images
- Content-visibility for off-screen cards
- Minimal render-blocking CSS
- Efficient AJAX pagination (no full page reloads)

---

## 📄 License

This project is licensed under the **MIT License** - feel free to use it for personal or commercial projects.

```
MIT License

Copyright (c) 2025 Wahib Irawan.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

---

## 📝 Changelog

### v1.0.0 (December 2024)
- 🎉 Initial public release
- ✨ Complete Material Design 3 styling
- ✨ AJAX navigation for SSR version
- ✨ Skeleton loading overlay
- ✨ Back-to-top button
- ✨ Reading time estimation
- ✨ High-res image auto-upgrade
- ✨ Complete SEO meta tags
- ✨ Threaded comment system
- ✨ Related posts section

---

<p align="center">
  Made with ❤️ for the Blogger community
</p>
