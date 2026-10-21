# Prateek's Blog 📝

Hi! I'm **Prateek Behera**, a passionate 7th-grade student at **Phoenix Greens School**. I created this blog to share my journey of learning, exploring new technologies, and expressing my thoughts on various topics.

**Live site:** [https://prateekbehera14.github.io/blog](https://prateekbehera14.github.io/blog)

## 🌟 Classic Site Features (`classic.html`)

- **Microsoft-Inspired Design**: Professional dark navy hero section with polished blue-gray theme
- **Rounded Card Design**: Modern cards with 12px border-radius and elegant shadows
- **Responsive Layout**: Fully optimized for desktop, tablet, and mobile devices
- **Sticky Navigation Bar**: Easy navigation with Home, About, Achievements, Blog, and Contact sections
- **Achievements Gallery**: 8 achievement cards with golden badges and decorative backgrounds
- **Blog Cards**: 6 beautifully designed blog post cards with gradient headers and pill-shaped tags
- **Smooth Animations**: Lift effects on hover, smooth scrolling, and polished transitions
- **Mobile-Friendly**: Hamburger menu with slide-in animation for seamless mobile navigation

## 🏆 Achievements Highlights

- **Gold Medals**: SOF NSO and IMO (Grades 5 & 6)
- **Excellence Certificates**: Ei Asset Talent Search (Grades 3, 5, 6)
- **Special Recognition**: TGES English Certificate (Grade 5)
- **Sports**: Hyderabad Marathon 5K Run (2025)
- **Inter-School Competition**: Mathematics Representative (Grade 5)

## 📚 Blog Topics

- My Blogging Journey
- Web Development Learning
- School Life Adventures
- Hobbies & Interests
- 2026 Goals
- Creative Projects

## 🎨 Design Elements

- **Color Palette**: Dark navy hero (#1b2631, #2c3e50), blue accents (#4a90e2, #63b3ed), professional grays (#5a6c7d, #7f8c8d)
- **Typography**: Segoe UI font family (Microsoft standard), 600 font-weight for headings
- **Card Shadows**: Soft 0 2px 8px shadows with 0 12px 24px on hover
- **Interactive Effects**: 8px translateY lift on hover for cards, smooth 0.3s transitions
- **Golden Badges**: Gradient badges (#ffc107 → #ff9800) with pill shape (20px border-radius)
- **Decorative Backgrounds**: Wave and radial gradient effects on card images
- **Rounded Elements**: Consistent 12px border-radius on all cards, 20px on tags and badges
- **Grid Layout**: Responsive 3-column grid (desktop) → 2-column (tablet) → 1-column (mobile)

## 🚀 Getting Started

Simply open `index.html` (the Field Notebook site) in your web browser to view the blog. The previous design is kept at `classic.html`.

## 📓 Field Notebook edition (`index.html`)

A reimagined version of the site styled as a hand-kept notebook: ruled paper, sticky notes, an explorer ID card, a filterable **trophy shelf**, and a timeline journal.

Each achievement has its own **photo gallery** (polaroid stack → lightbox with arrows, keyboard ←/→, swipe, and thumbnails).

**Adding photos:** put images in `images/achievements/<id>/` and list them in the `ACHIEVEMENTS` array near the bottom of `index.html`:

```js
{ id: "hyderabad-5k", ..., photos: [
  { src: "finish.jpg", caption: "Crossed the finish!" }
]}
```

Missing photos show a placeholder that tells you the exact path to add. Full URLs (`https://...`) or paths containing `/` (e.g. `images/fundraising-certificate.png`) are used as-is in `src`.

Keep photos under ~1600px on the long side (≈300 KB) so the page loads fast on phones. `images/prateek-profile.jpeg` is the Explorer ID photo, and `images/og-preview.jpg` (1200×630) is the preview shown when the link is shared.

## 📧 Contact

Feel free to reach out through the Contact section on the website!

---

© 2026 Prateek's Blog | Made with 🖤 by Prateek Behera
