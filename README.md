# 🏠 Airbnb UI Clone

A pixel-accurate, responsive front-end clone of the Airbnb homepage — built with pure HTML and CSS, no frameworks or libraries.

---

## ✨ What's Included

- **Sticky navbar** with logo, navigation tabs, and a hover-triggered dropdown menu
- **Search bar** with destination, check-in, check-out, and guests fields
- **Category icon row** — horizontally scrollable with hover underline effect
- **Experiences grid** — upcoming and past experiences in a 4-column responsive card layout
- **Full footer** with inspiration table, support links, and copyright row
- **Fully responsive** — adapts to mobile, tablet, and desktop

---

## 🛠️ Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=flat&logo=fontawesome&logoColor=white)

**No JavaScript. No frameworks. No build tools.**

---

## 🚀 Getting Started

```bash
git clone https://github.com/ajarmeh-oroub/airbnb-clone.git
cd airbnb-clone
```

Open `index.html` in your browser.

---

## 📁 Project Structure

```
airbnb-clone/
├── index.html          # Full page markup — semantic HTML5
├── css/
│   └── style.css       # All styling — CSS custom properties, Flexbox, Grid
├── images/             # All assets — icons, cards, logo, social
└── .gitignore
```

---

## 💡 CSS Highlights

- **CSS custom properties** (`--red`, `--border`, `--shadow`) for consistent theming
- **CSS Grid** for responsive card layouts — switches from 4 → 3 → 2 → 1 columns
- **Flexbox** for navbar, search bar, footer, and icon row
- **Sticky positioning** for the navbar — stays at top on scroll
- **Hover transitions** on cards, nav items, dropdown, and search bar
- **`overflow-x: auto` with hidden scrollbar** for the category icon strip
- **`object-fit: cover`** for consistent image proportions across all cards

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| > 1024px | 4-column card grid |
| 768px – 1024px | 3-column card grid |
| 480px – 768px | 2-column card grid |
| < 480px | 1-column card grid |

---

## 👩‍💻 Author

**Oroub Ajarmeh** — Full-Stack Software Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Oroub_Ajarmeh-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oroub-ajarmeh-86493a233)
[![GitHub](https://img.shields.io/badge/GitHub-ajarmeh--oroub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ajarmeh-oroub)

---

## 📄 License

MIT — free to use and modify.
