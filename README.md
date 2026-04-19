# Dr. Ella Chioma Ezeadilieje — Portfolio Website

## 📁 Project Structure

```
dr-ella-portfolio/
├── index.html          ← Main HTML file
├── css/
│   └── style.css       ← All styles (Deep Purple × Rose Gold theme)
├── js/
│   └── main.js         ← Scroll reveals, nav, mobile menu, form
├── images/
│   └── dr-ella.jpg     ← ⚠️  ADD THIS — Dr. Ella's photo
└── README.md
```

## 🚀 Setup

1. **Add the photo**: Drop Dr. Ella's photo into the `images/` folder and name it `dr-ella.jpg`.
   - Best size: at least **600×800px**, portrait orientation
   - The image will be cropped to fill the hero frame automatically

2. **Update social links**: In `index.html`, search for `href="#"` in the social links section and replace with real Instagram/Facebook/LinkedIn URLs.

3. **Open in browser**: Simply open `index.html` in any modern browser — no server required.

## ✏️ Customization

| What to change | Where |
|---|---|
| Profile photo | `images/dr-ella.jpg` |
| Social media links | `index.html` — sidebar socials + contact section |
| Contact form action | `js/main.js` — `handleSubmit` function |
| Colors | `css/style.css` — `:root` CSS variables |
| Text content | `index.html` — each section |

## 🎨 Color Palette

| Variable | Value | Usage |
|---|---|---|
| `--purple-deep` | `#2D1B4E` | Primary dark, sidebar, text |
| `--purple-soft` | `#5A4080` | Accents, icons |
| `--gold` | `#C9973A` | Eyebrows, badges, highlights |
| `--rose-gold` | `#D4A0A0` | Soft accents, gradients |

## 🌐 Hosting

To put this online for free:
- **Netlify**: Drag the whole folder into netlify.com/drop
- **GitHub Pages**: Push to a repo and enable Pages
- **Vercel**: `npx vercel` in the folder

---
Built for Dr. Ella Chioma Ezeadilieje · Veronica's Daughter · 2026
