# Shopamp! – Clothing Store Landing Page

A fully responsive, production-grade clothing store landing page built with pure **HTML5** and **CSS3** — no frameworks, no dependencies (except Google Fonts & Font Awesome CDN).

---

## 📁 Project Structure

```
clothing-store/
├── index.html      → Main HTML file
├── style.css       → Complete stylesheet
└── README.md       → This file
```

---

## 🚀 How to Run

1. Download both `index.html` and `style.css` into the **same folder**
2. Open `index.html` in any modern browser
3. No build step, no npm install — it just works!

---

## 🎨 Sections Included

| # | Section | Description |
|---|---------|-------------|
| 1 | **Navbar** | Fixed top bar with logo, nav links, "Buy Now" CTA, hamburger menu |
| 2 | **Hero** | Full-screen image with zoom animation, headline & CTA button |
| 3 | **About Us** | 3-column card grid with images and descriptions |
| 4 | **Sale Banner** | Full-width banner with "SALE TO –70%" and animated "70" number |
| 5 | **Features** | 4 feature icons — Sale, Delivery, Our Choice, Warranty |
| 6 | **Our Products** | 2×2 product grid with hover overlay & Add to Cart button |
| 7 | **Newsletter** | Email subscribe form with confirmation state |
| 8 | **Lookbook** | Asymmetric 3-column image grid with New/Hot/Sale tags |
| 9 | **Latest News** | 3-column news cards with Learn More links |
| 10 | **Last Collection** | 5-column photo grid showcase |
| 11 | **Testimonials** | Auto-sliding carousel with arrows, dots & star ratings |
| 12 | **Our Location** | 2 store info cards + embedded Google Map |
| 13 | **Footer** | 4-column footer with social icons and links |

---

## ✨ Features & Interactions

- **Scroll Reveal Animations** — every section fades in as you scroll down
- **Sticky Navbar** — becomes white with shadow on scroll
- **Hero Zoom** — subtle Ken Burns zoom effect on hero image
- **Product Hover** — image zoom + "Add to Cart" overlay slides up
- **Cart Toast** — popup notification when item is added
- **Auto Testimonial Slider** — auto-advances every 5 seconds
- **Subscribe Confirmation** — button shows "✓ Subscribed!" on submit
- **Back to Top Button** — appears after scrolling 400px
- **Animated Sale Number** — floating "70" red number in sale banner
- **Mobile Hamburger Menu** — smooth open/close animation

---

## 🎨 Color Theme

```css
--blue:       #3aa3d4   /* Primary brand color */
--blue-dark:  #2287b5   /* Hover state */
--blue-light: #e8f6fb   /* Backgrounds */
--dark:       #1a1a2e   /* Footer background */
--dark-2:     #2d2d2d   /* Body text */
--gray:       #666666   /* Secondary text */
--red:        #c0392b   /* Sale accent */
--gold:       #f39c12   /* Star ratings */
```

---

## 🔤 Fonts Used

| Font | Usage | Source |
|------|-------|--------|
| **Playfair Display** | Headings, logo, titles | Google Fonts |
| **Poppins** | Body text, buttons, nav | Google Fonts |
| **Font Awesome 6** | Icons throughout | CDN |

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout Changes |
|------------|----------------|
| `> 992px` | Full desktop layout |
| `≤ 992px` | Hamburger nav, 2-col grids, stacked features |
| `≤ 640px` | Single column, stacked subscribe form, simplified grids |

---

## 🌐 External CDNs Used

```html
<!-- Google Fonts -->
https://fonts.googleapis.com/css2?family=Playfair+Display&family=Poppins

<!-- Font Awesome Icons -->
https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css

<!-- Google Maps Embed (Location section) -->
https://www.google.com/maps/embed?...

<!-- Unsplash Images (placeholder photos) -->
https://images.unsplash.com/...
```

> ⚠️ **Note:** An internet connection is required to load fonts, icons, and placeholder images. To use offline, download these assets locally.

---

## 🛠️ Customization Guide

### Change Brand Color
In `style.css`, update the `--blue` variable:
```css
:root {
  --blue: #3aa3d4; /* Replace with your color */
}
```

### Replace Images
In `index.html`, replace Unsplash URLs with your own image paths:
```html
<img src="your-image.jpg" alt="Description" />
```

### Update Products
Find the `Our Products` section in `index.html` and edit each `.product-card`:
```html
<h4>Your Product Name</h4>
<p class="product-price">$XX.00</p>
```

### Change Map Location
In the `Our Location` section, replace the Google Maps embed `src` URL with your own embed link from [Google Maps](https://maps.google.com).


### Live View Of Landing Page

https://www.loom.com/share/a950acd500544116aa31c635bd4f45b4


## 👨‍💻 Built For

> This project was created as an **AI-Assisted learning task** for a trainee at **The TechnerLab Academy**.

---

