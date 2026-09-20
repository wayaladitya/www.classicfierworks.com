# Classic Fireworks 🎆

A clean, mobile-first, single-page promotional website for **Classic Fireworks** — built for promotion and lead generation.

## 🌐 Live Demo

After deploying to GitHub Pages, your site will be live at:
```
https://<your-username>.github.io/classic-fireworks/
```

## 🚀 Deploy to GitHub Pages (3 steps)

1. **Create a repo** — Go to [github.com/new](https://github.com/new), name it `classic-fireworks`, set it to **Public**
2. **Upload files** — Click "uploading an existing file", drag in the entire contents of this folder (`index.html`, `img/`, `README.md`, `.nojekyll`)
3. **Enable Pages** — Go to **Settings → Pages → Source** → select `main` branch, folder `/ (root)`, click **Save**

Your site will be live within a minute at `https://<your-username>.github.io/classic-fireworks/`

## 📁 Project Structure

```
classic-fireworks/
├── index.html      ← Complete single-page website (HTML + CSS + JS all-in-one)
├── img/
│   └── logo.png    ← Company logo
├── .nojekyll       ← Tells GitHub Pages to skip Jekyll processing
└── README.md       ← This file
```

## ✏️ How to Customize

All content is in one file — `index.html`. Open it in any text editor and search-replace:

| Find | Replace with |
|------|-------------|
| `(555) 123-4567` | Your real phone number |
| `info@classicfireworks.com` | Your real email |
| `123 Sparkle Lane, Fireworks City, FC 12345` | Your real address |
| `YOUR_FORM_ID` | Your Formspree form ID (see below) |
| Social `href="#"` | Your Facebook / Instagram / YouTube URLs |

### Connect the Contact Form

1. Sign up free at [formspree.io](https://formspree.io/)
2. Create a new form — you'll get an ID like `xyzabcde`
3. In `index.html`, find `https://formspree.io/f/YOUR_FORM_ID` and replace `YOUR_FORM_ID` with your real ID
4. All form submissions will go straight to your email

### Replace Placeholder Photos

Swap the Unsplash image URLs in `index.html` with your own fireworks show photos. Search for `unsplash.com` to find all image references.

## 🎨 Design

- **Colors**: Navy `#1a1a2e` · Crimson `#9b1b30` · Gold `#d4a843`
- **Fonts**: Playfair Display (headings) · Inter (body)
- **Framework**: Bootstrap 5.3.2 (CDN)
- **Icons**: Bootstrap Icons (CDN)
- **Form Backend**: Formspree (free, no server required)

## 📱 Responsive

Fully mobile-first with breakpoints at 576px, 768px, and 992px.

---

© 2026 Classic Fireworks
