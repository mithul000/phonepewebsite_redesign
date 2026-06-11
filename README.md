# 📱 PhonePe Website Redesign

A clean, modern multi-page redesign of the [PhonePe](https://www.phonepe.com/) website — built with pure **HTML, CSS, and vanilla JavaScript**. No frameworks, no build tools, just open the file and run.

![PhonePe Redesign](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-purple?style=flat-square)

---

## 🌐 Live Preview

> Open `phonepe-redesign.html` directly in your browser — no server needed.

You can also host it instantly on:
- **GitHub Pages** — push to `main`, enable Pages in Settings → Pages → Source: `main` / `/(root)`
- **Netlify Drop** — drag the HTML file to [netlify.com/drop](https://app.netlify.com/drop)
- **Vercel** — `vercel --prod` in the project folder

---

## ✨ Features

| Feature | Details |
|---|---|
| 🌙 Dark / Light Theme | Toggle with the moon/sun button — persists across all pages |
| 📄 6 Pages | Home, Payments, Invest, Insurance, Business, About |
| ⚡ Smooth Transitions | Fade + slide-up animation on every page change |
| 📱 Fully Responsive | Mobile-friendly with hamburger menu |
| 🎨 PhonePe Brand Colors | Signature purple gradient `#5f259f` throughout |
| 🖱️ Hover Micro-interactions | Cards, buttons, and nav links all animate |
| 📲 Phone Mockup Hero | Animated balance card in the homepage hero |
| 🚫 Zero Dependencies | No npm, no framework, no build step |

---

## 📂 Project Structure

```
phonepe-redesign/
│
├── phonepe-redesign.html   ← All-in-one file (HTML + CSS + JS)
└── README.md               ← You are here
```

All styles and scripts are inlined — single file deployment.

---

## 🗂️ Pages Overview

### 🏠 Home
- Hero section with phone mockup and stats (500M users, ₹10L Cr processed)
- 6-card services grid (Payments, Invest, Insurance, Gold, Bills, Business)
- Two feature split sections (UPI speed, Smart investing)
- Testimonials from real user personas
- App download CTA banner

### 💳 Payments
- Step-by-step UPI how-it-works guide
- 6 payment feature cards (Recharge, Bills, Travel, Food, Bank Transfer, Rewards)

### 📈 Invest
- 6 investment product cards with live return rates
- Products: Liquid Funds, Balanced Funds, Equity Funds, Digital Gold, Fixed Deposits, ELSS

### 🛡️ Insurance
- 6 insurance categories with starting prices
- Health, Life, Car, Bike, Travel, Home insurance

### 🏢 Business
- Merchant payment tools (QR, Gateway, POS, Dashboard, Payroll, API)
- Scale stats (3.5Cr merchants, 99.99% uptime)

### ℹ️ About
- Company founding story and mission
- Leadership team cards
- Company values

---

## 🚀 Getting Started

### Option 1 — Open Directly
```bash
# Just double-click phonepe-redesign.html
# Or from terminal:
open phonepe-redesign.html          # macOS
start phonepe-redesign.html         # Windows
xdg-open phonepe-redesign.html      # Linux
```

### Option 2 — GitHub Pages (Recommended)

1. Create a new GitHub repository
2. Upload `phonepe-redesign.html` and `README.md`
3. **Rename** `phonepe-redesign.html` → `index.html` *(GitHub Pages serves `index.html` by default)*
4. Go to **Settings → Pages → Source → Deploy from branch → `main` → `/ (root)`**
5. Click **Save** — your site will be live at:

```
https://<your-username>.github.io/<repo-name>/
```

> ⚠️ **Important:** GitHub Pages requires the file to be named `index.html` to auto-serve at the root URL.

### Option 3 — Local Server (optional)
```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .

# Then visit: http://localhost:8000/phonepe-redesign.html
```

---

## 🎨 Design Tokens

| Token | Value | Usage |
|---|---|---|
| `--purple` | `#5f259f` | Primary brand color |
| `--purple-light` | `#7c3ac4` | Hover states |
| `--purple-dark` | `#3d1466` | Hero gradient start |
| `--indigo` | `#6c3be8` | Gradient end, accents |
| `--accent` | `#ffd700` | Hero headline highlight |
| `--green` | `#22c55e` | Investment returns |
| `--radius` | `16px` | Card border radius |

Dark mode swaps all `--bg`, `--card`, `--text`, and `--border` variables automatically.

---

## 🔧 Customisation

### Change brand color
Find and replace `#5f259f` with your color throughout the `<style>` block.

### Add a new page
1. Add a nav link: `<a onclick="showPage('newpage')">New Page</a>`
2. Add a page div: `<div class="page" id="page-newpage">...</div>`
3. Add `'newpage'` to the `pages` array in the `<script>` block

### Modify dark mode colors
Edit the `[data-theme="dark"]` CSS block at the top of the `<style>` section.

---

## 📸 Screenshots

> Run the project locally and take screenshots to add here.

| Light Mode | Dark Mode |
|---|---|
| *(add screenshot)* | *(add screenshot)* |

---

## 🛠️ Browser Support

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| IE 11 | ❌ Not supported |

---

## 📄 License

This project is for **educational and portfolio purposes only.**  
PhonePe® is a registered trademark of PhonePe Pvt. Ltd.  
This redesign is not affiliated with or endorsed by PhonePe.

Released under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- Design inspired by [phonepe.com](https://www.phonepe.com/)
- Fonts: [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts
- Icons: Unicode emoji (no external icon library needed)

---

<p align="center">Made with 💜 using pure HTML, CSS & JS</p>
