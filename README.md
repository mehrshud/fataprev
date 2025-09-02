# Professional Preview Portfolio (Redesigned)

A polished, mobile-first portfolio page with live GitHub signals, refined cards, Quick View modals, and thoughtful motion design. Built with semantic HTML, modern CSS, and a small amount of vanilla JS—no build step required.

> This redesign was created after reviewing the existing single-file page and retaining the strongest ideas (dynamic GitHub hydration, reveal-on-scroll) while improving structure, accessibility, and aesthetics.

## ✨ Features

- **Clean, modern layout**
  - Sticky “glass” header with scroll-aware elevation
  - Split hero (copy + animated device preview)
  - Auto-fit project grid with density presets (Auto / Cozy / Compact)
- **Interactive project cards**
  - Live GitHub **Updated**, **Stars**, and **Languages**
  - **Quick View** modal with keyboard & screen-reader support
  - Live **search, sort**, and **category filters**
- **Tasteful animations**
  - Reveal-on-scroll, subtle hover scaling, shimmering skeletons
  - Animated starfield and parallax blobs (GPU-friendly)
  - All motion respects `prefers-reduced-motion`
- **Mobile-first & responsive**
  - Fluid typography (`clamp`) and flexible grids
  - Inputs sized for touch, content-visibility for snappy lists
- **Accessibility**
  - Semantic landmarks, skip link, focus rings, ARIA labels
  - High-contrast friendly; reduced motion support
  - Modal is escapable, restores focus, and disables background scroll
- **Performance-minded**
  - Lazy images, `content-visibility`, transform-only animations
  - LocalStorage caching for GitHub results (12h TTL)
  - Optional **service worker** caches static assets for repeat visits
- **State persistence**
  - Theme, layout density, and sort preference saved across visits

## 🧩 Technologies

- **HTML5**, **CSS3**, **JavaScript (ES Modules not required)**
- No frameworks; no build step
- Optional Service Worker for static asset caching

## 📦 Project Structure
