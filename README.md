# 🌐 Oak Academy – Modern Portfolio Website

A fully responsive and modern portfolio website designed for Oak Academy, featuring light & dark mode, smooth scroll animations, a mobile hamburger menu, and a clean UI inspired by current design trends.

This project is built using HTML, CSS, and vanilla JavaScript, with animations powered by AOS (Animate On Scroll).

## 🚀 Live Demo

🔗 Live Website: (https://abiraisingh.github.io/Personal-Portfolio/)

## ✨ Features
### 🎨 Modern UI/UX

Soft light theme (default) + Dark mode

Smooth gradients, soft shadows, glassmorphism

Floating orbit animation around hero image

Clean, readable typography

### 🌗 Dark Mode Toggle

One-click theme switch

Theme preference stored using localStorage

### 📱 Fully Responsive Design

Works perfectly on all screen sizes

Includes animated hamburger menu for mobile

Navigation automatically closes on link click

### ✨ Scroll Animations

AOS (Animate On Scroll) for fade, zoom, and reveal animations

Performant and smooth across devices

## 🧩 Website Sections

Hero Section

About Us

Services

Portfolio / Projects

Contact Form

Footer with Back-to-top button

## ⚡ Performance-Oriented

Lightweight (no heavy frameworks)

Clean semantic HTML

Optimized CSS and animations

## 🛠️ Tech Stack
Technology	Purpose
HTML5	Structure
CSS3	Styling, gradients, responsiveness
JavaScript (ES6)	Theme toggle, mobile menu
AOS Library	Scroll animations
Font Awesome	Icons
## 📂 Project Structure
```
/
├── index.html
├── style.css
├── images/
│   ├── hero.png
│   ├── project.webp
│   ├── logo.avif
│   └── …
└── README.md

```

## ⚙️ Installation & Usage

Clone the repository:
```
git clone https://github.com/abiraisingh/Socially.git
```

Open the project folder:
```
cd Socially

Open index.html in your browser.

No build steps — just open and run.
```

## 🌤 Switching Themes (How It Works)

The theme toggle button:

Adds/removes .dark class from <body>

Saves preference in localStorage

Automatically applies saved theme on page load

const storedTheme = localStorage.getItem('oak-theme');
if (storedTheme === 'dark') body.classList.add('dark');

## 📱 Mobile Menu Interaction

The hamburger button:

Opens/closes the navigation

Animates into an "X"

Closes automatically on menu link click

navbar.classList.toggle('open');

## 🚀 Deployment
▶ GitHub Pages

Go to your GitHub repo

Open Settings → Pages

Choose Branch: main and Folder: /root

Save

Your site will deploy at:

https://USERNAME.github.io/REPO-NAME/

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a pull request.

## 📝 License

This project is free to use for personal and educational purposes.

## 💡 Author

Oak Academy
Built by Abirai Singh
