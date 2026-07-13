<div align="center">

# 🍳 Recipiiy — Culinary & Recipe Portal

### *A vibrant, fully responsive multi-page web platform for recipe discovery, community forum discussion, and culinary events*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-6.4-528DD7.svg?style=flat-square&logo=fontawesome&logoColor=white)](https://fontawesome.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

> **Recipiiy** is an interactive, multi-page web ecosystem crafted for home cooks and food enthusiasts. Explore detailed categories, filter and expand ingredients on cards, read culinary blogs, register for masterclasses, join forum discussions, and subscribe to premium meal plans.

### 🌐 [**Live Demo → anasq2003.github.io/Recipiiy**](https://recipiiy.netlify.app/)

</div>

---

## ✨ Features & Architecture

| Module / Page | Feature Details | Technical Implementation |
|---|---|---|
| 🏠 **Home Page** | Dynamic category navigation, featured recipes slider, newsletter CTA, testimonials | CSS Grid cards, CSS variables |
| 📖 **Recipes Archive** | Interactive filtering by category, search bar query parsing, recipe cards | Flexbox filters, toggle states |
| 🥗 **Recipe Details** | Accordion-like drop-downs listing precise ingredients & step-by-step instructions | Expand/collapse JS transitions |
| 🏷️ **Categories** | Diets & category catalog grid (Breakfast, Lunch, Dinner, Vegan, Healthy, Baking) | CSS Grid layout with image overlay |
| 💬 **Community Forum** | Discussion board layout featuring topics, replies counter, views count, creation widget | Semantic HTML tables, clean listing cards |
| 📅 **Culinary Events** | Class grids (Pasta making, Wine dinners) with location, date metadata, registration link | Interactive Eventbrite links, flex cards |
| ✍️ **Food Blog** | Grid listing of expert culinary tips, prep hacks, and seasonal articles | Flex layouts with card hovers |
| ⚙️ **Utility Modals** | Sign-up forms, interactive email subscription checkers, Karachi Map integrations | CSS transitions, Leaflet Map frames |

---

## 🖥️ Tech Stack

Recipiiy is designed as a modular **multi-page static platform** with zero backend requirements:

| Technology | Purpose | Description |
|---|---|---|
| **HTML5** | Content Structure | Semantic HTML5 structure, navigation dropdowns, modal configurations |
| **CSS3** | Aesthetics & Responsive | Responsive design with Custom Properties (variables), CSS Grid, Flexbox, media query breakpoints |
| **JavaScript (ES6)** | Page Interactivity | Mobile menu toggling, smooth scroll animations, recipe ingredient dropdown controls, form verifications |
| **Google Fonts** | Typography | Aesthetic pairing of *Poppins* for headers and *Playfair Display* for content |
| **Font Awesome 6.4** | Icons | Crisp vector icons for metadata (cooking times, ratings, bookmarks) |

---

## 🚀 Getting Started

### Option 1 — Open Files Directly
```bash
git clone https://github.com/AnasQ2003/Recipiiy.git
cd Recipiiy
start index.html      # Windows
open index.html       # macOS
```

### Option 2 — Serve Locally (Recommended)
```bash
python -m http.server 3000
# http://localhost:3000/index.html
```

---

## 📂 Directory Layout

```
Recipiiy/
├── index.html        # 🏠 Home page
├── recipes.html      # 🥗 Recipe cards archives
├── categories.html   # 🏷️ Food categories grids
├── about.html        # ℹ️ Portal mission & core ideals
├── contact.html      # 📞 Contact forms with map
├── login.html        # 🔑 User login screens
├── faq.html          # ❓ Collapsible FAQ sections
├── blog.html         # 📝 Cooking tips articles grid
├── forum.html        # 💬 Discussion thread listings
├── events.html       # 📅 Cooking masterclass workshops
├── newsletter.html   # 📧 Subscription email signup
├── a.png to n.png    # 📸 Platform screenshots
└── README.md
```

---

## 📸 Screen Preview Gallery

### 🏠 Navigation & Hero

**Hero & Landing Page**
![Hero banner home](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/a.png)

---

**Category Portals**
![Categories on landing](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/b.png)

---

**Dropdown Overlays**
![Footer & Category Dropdown](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/c.png)

---

### 🥗 Recipes & Categories

**Recipes Archive**
![Recipes search page](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/d.png)

---

**Interactive Details**
![Ingredient list details dropdown](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/e.png)

---

**Dedicated Category Guide**
![Category page grids](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/f.png)

---

### 💼 Culinary Community & Events

**Culinary Workshops**
![Events masterclass listings](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/m.png)

---

**Recipe Forums**
![Forum threads board](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/l.png)

---

### 📖 Blog, FAQ & Info Sections

**Food Blog**
![Culinary blog grid](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/k.png)

---

**FAQ Accordions**
![Frequently Asked Questions page](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/j.png)

---

**About Recipiiy**
![About page](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/g.png)

---

**Contact Us & Location Maps**
![Contact form and map](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/h.png)

---

### 🔑 Authentication & Newsletters

**Secure Login**
![User login page](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/i.png)

---

**Email Subscriptions**
![Newsletter signup](https://raw.githubusercontent.com/AnasQ2003/Recipiiy/main/n.png)

---

## 🎨 Design System

```css
:root {
  --primary-color:   #ff5a5f;   /* Warm coral red - primary accent */
  --secondary-color: #3a3a3a;   /* Charcoal grey - body text */
  --light-color:     #f8f9fa;   /* Cream white - backgrounds */
  --accent-color:    #ffc107;   /* Amber gold - rating stars */
  --success-color:   #28a745;   /* Green - complete items */
}
```

---

## 🤝 Contributing

1. Fork the project.
2. Create your Feature Branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'feat: add AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request.

---

## 📄 License

```
MIT License

Copyright (c) Recipiiy---2026 AnasQ2003

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 👨‍💻 Author

**Anas Ahmed Qureshi** — [@AnasQ2003](https://github.com/AnasQ2003)

---

<div align="center">

Built with ❤️ by **Anas**

Made with 🔥 and a lot of ☕

**⭐ If you found this useful, please star the repository!**

</div>
