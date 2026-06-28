# 💅 Luxe Nails Studio — Website Template

A stunning, fully responsive nail tech business website designed for TikTok marketing and client conversion. Built with pure HTML & CSS — no frameworks, no dependencies (except Google Fonts).

---

## ✨ Features

- **Full-bleed hero** with animated floating nail art cards and a signature diagonal rose slash
- **Auto-scrolling ticker** strip for services
- **Services grid** with hover reveals and a featured card highlight
- **About / trust section** with credentials and floating badge
- **Gallery grid** with hover overlays
- **Testimonials** with featured center card
- **Transparent pricing tables** — no hidden fees
- **Booking CTA** section with hours
- **Contact form + social links**
- **Sticky nav** with scroll effect and mobile hamburger menu
- **Scroll-reveal animations** (IntersectionObserver)
- **Fully responsive** — mobile, tablet, desktop
- **Respects `prefers-reduced-motion`** for accessibility

---

## 🎨 Design System

| Token | Value |
|-------|-------|
| Background | `#FAF6F1` (cream) |
| Primary Accent | `#F2A7BB` (rose) |
| Deep Accent | `#E08098` (rose-deep) |
| Gold | `#E8C87A` |
| Black | `#0D0D0D` |
| Display Font | Playfair Display |
| Body Font | DM Sans |

---

## 📁 File Structure

```
luxe-nails-studio/
├── index.html       ← Main page
├── style.css        ← All styles
└── README.md        ← This file
```

---

## 🚀 Getting Started

1. Clone or download the repo
2. Open `index.html` in your browser — no build step needed
3. Replace placeholder content:
   - Business name, address, email, phone
   - Social media links (TikTok, Instagram)
   - Service prices (search `from £`)
   - Nail artist name (search `Mia`)
   - Gallery images (replace `.gi--*` backgrounds with `background-image: url(...)`)
   - About photo (replace `.about__img-placeholder--main` with a real `<img>`)

---

## 🖼️ Replacing Gallery Images

In `style.css`, find:
```css
.gi--1 { background: linear-gradient(...); }
```
Replace with:
```css
.gi--1 { background-image: url('images/set1.jpg'); background-size: cover; background-position: center; }
```

---

## 📱 TikTok Marketing Tips

This site is designed with TikTok conversion in mind:
- **Fast visual impact** — the hero tells the full story in 3 seconds
- **Social proof** right on the page (stats, reviews)
- **Single CTA** per section — no decision paralysis
- **WhatsApp booking** button for frictionless DM-to-book flow
- Add `?ref=tiktok` to your booking link to track TikTok conversions

---

## 📝 Customisation Checklist

- [ ] Replace `Luxe Nails Studio` with your business name
- [ ] Update contact email and phone
- [ ] Add real studio address
- [ ] Link TikTok and Instagram
- [ ] Upload real nail photos to `/images/`
- [ ] Replace artist name and bio
- [ ] Update pricing
- [ ] Set correct opening hours
- [ ] Add promo code or remove that section
- [ ] Update favicon

---

## 📄 License

Free to use and adapt for personal or commercial projects. No attribution required.

---

*Made with 💅 for nail tech businesses everywhere.*
