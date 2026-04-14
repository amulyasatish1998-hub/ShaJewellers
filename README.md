# SHA Jewellers — Luxury Jewellery Website

A full-featured jewellery e-commerce landing page inspired by Tanishq.co.in, built with pure HTML, CSS, and vanilla JavaScript. Zero dependencies, no build step.

## 🚀 Deploy to GitHub Pages

1. **Fork / Upload** this repo to your GitHub account
2. Go to **Settings → Pages**
3. Under *Source*, select **Deploy from a branch → main → / (root)**
4. Click **Save** — your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

## 📁 File Structure

```
/
├── index.html      ← entire website (single file)
└── README.md
```

## ✨ Sections Included

| Section | Description |
|---|---|
| **Announcement Ticker** | Scrolling marquee with offers |
| **Sticky Navbar** | Logo, nav links, search, wishlist, cart counter |
| **Hero Banner** | Full-screen with decorative mandala SVG |
| **Category Grid** | 8 jewellery categories with hover effects |
| **Collection Banners** | Bento-style grid with 3 featured collections |
| **Gold Rate Band** | Live-simulated 22K / 18K / Silver rates |
| **New Arrivals Grid** | 8 product cards with wishlist & add-to-bag |
| **Trust Strip** | Hallmark, exchange, shipping, EMI badges |
| **Testimonials** | 3 customer reviews |
| **Newsletter Signup** | Email capture form |
| **Footer** | Brand, 3 link columns, payment badges |

## 🎨 Customisation

All colors are CSS variables in `:root` — change them to match your brand:

```css
:root {
  --gold:      #C9A84C;  /* primary accent */
  --cream:     #FAF6EF;  /* page background */
  --charcoal:  #2B2B2B;  /* text / dark sections */
}
```

Replace emoji placeholders in `.product-img` and `.cat-icon-wrap` with real `<img>` tags pointing to your product photos.

## 📱 Responsive

- Desktop: full multi-column layout
- Tablet: 2-column collections, hamburger menu
- Mobile: stacked single column, 4-col compact categories

## 🔧 Swap Brand Name

Search and replace `Sha Jewellers` / `Sha Jewellers` in `index.html` with your brand name.
