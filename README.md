# 🎯 Button Hover Effects

A clean and modern **HTML & CSS** project showcasing **four unique hover button animations** on a single page.
Each button demonstrates a different hover interaction technique using pure CSS.

> This project showcases different creative hover animations for buttons, useful for enhancing UI/UX in modern web applications

---

## 📁 Project Structure

```bash
Button-Hover-Effects/
│
├── index.html         # Main HTML file containing all buttons
├── styles.css         # Combined and scoped CSS for all hover effects
├── LICENSE
└── README.md          # Project documentation
```

---

## ✨ Features

- Four distinct hover button animations
- Fully responsive layout
- Pure HTML & CSS (no JavaScript)
- Clean, scoped CSS to avoid conflicts
- Beginner-friendly and easy to customize
- Smooth transitions and modern UI effects
- Works across all modern browsers

---

## 🧠 How It Works

Each button is wrapped inside a uniquely scoped container:

- `.btn-1`
- `.btn-2`
- `.btn-3`
- `.btn-4`

This prevents CSS selector conflicts and allows all hover animations to coexist on the same page without breaking.

### Core Concept (Scoped CSS)

```css
.btn-1 a::before {
  content: "DOWNLOAD";
  transform: translateY(-100%);
}

.btn-1 a:hover::before {
  transform: translateY(0);
}
```

Each button uses a different combination of:
- `::before` / `::after`
- `transform`
- `transition`
- `perspective`
- `mix-blend-mode`

---

## 🎨 Button Effects Overview

| Button | Effect Type |
|------|-------------|
| Button 1 | Slide-down overlay text |
| Button 2 | 3D flip animation |
| Button 3 | Perspective layered hover |
| Button 4 | Expanding ripple + lift |

---

## 🚀 Getting Started

1. Download or clone the project.
2. Open `index.html` in any modern browser.
3. Scroll through the page.
4. Hover over each button to see the animations ✨

---

## 📌 Use Cases

- UI animation demos
- CSS hover effect practice
- Frontend portfolio components
- Learning CSS transitions & transforms
- Button animation inspiration

---

## Author

> **Developer:**  **Sakshi Chavan**

> **Github:** **[sagesakshi27](https://github.com/sagesakshi27)**

---
