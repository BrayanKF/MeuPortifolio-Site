# Kaell Brayan Portfolio

Personal portfolio website for Kaell Brayan Soares Ferraz, built with pure HTML5, CSS3, and JavaScript ES6+.

## 📁 Project Structure

```
MeuPortifolio-Site/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── js/
│   └── script.js       # Interactive JavaScript (i18n, smooth scroll, etc.)
├── img/                # Image assets
│   ├── perfil.jpg.jpeg
│   ├── radartop-hero.jpg.jpeg
│   ├── radartop-cta.jpg.jpeg
│   ├── radartop-galeria.jpg.jpeg
│   ├── aura-home.png.png
│   └── aura-login.png.png
└── assets/
    └── curriculo-kaell.pdf  # Resume/CV (to be added)
```

## 🚀 How to Run Locally

This is a static website that can be opened directly in a browser or served via any static server.

### Option 1: Open directly in browser
Simply open `index.html` in your preferred browser (Chrome, Firefox, Safari, Edge).

### Option 2: Use a local development server
For better performance and to avoid potential CORS issues, you can use a local server:

#### Using Python
```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000
```

#### Using Node.js (http-server)
```bash
# Install http-server globally (if not installed)
npm install -g http-server

# Start server
http-server -p 8000

# Then visit: http://localhost:8000
```

#### Using VS Code Live Server
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 📝 Features

- **Dark theme** inspired by Game of Thrones/HBO aesthetic
- **Internationalization** (Portuguese/English) with localStorage persistence
- **Smooth scrolling** and scroll reveal animations (AOS)
- **Responsive design** with mobile-first approach
- **Interactive skill bars** with IntersectionObserver
- **3D tilt effects** on project cards
- **Image clipping** for RadarTop screenshots (hiding mobile status bar)
- **Contact form** with client-side validation
- **Language toggle** in navbar
- **Download CV** button

## 🖼️ Image Assets

All images should be placed in the `img/` directory with the exact filenames referenced in the HTML:

- `perfil.jpg.jpeg` - Profile photo for hero section
- `radartop-hero.jpg.jpeg` - RadarTop hero screenshot
- `radartop-cta.jpg.jpeg` - RadarTop CTA screenshot
- `radartop-galeria.jpg.jpeg` - RadarTop gallery screenshot
- `aura-home.png.png` - AURA Cosméticos home page screenshot
- `aura-login.png.png` - AURA Cosméticos login page screenshot

Note: The double extensions (`.jpg.jpeg`, `.png.png`) are intentional and match the actual files provided.

## 📄 Resume/CV

Place your resume/CV PDF file at `assets/curriculo-kaell.pdf` and link it from the "Baixar Currículo" button in the hero section.

## 🌐 Deployment

This site is 100% static and can be deployed to any static hosting service:

- GitHub Pages
- Vercel
- Netlify
- Firebase Hosting
- Or any traditional web server

## 🛠️ Technologies Used

- HTML5 Semantic Elements
- CSS3 Custom Properties (CSS Variables)
- JavaScript ES6+
- [AOS - Animate On Scroll](https://michalsnik.github.io/aos/) (via CDN)
- Google Fonts: Space Grotesk + Inter
- Intersection Observer API (for skill bar animations)
- localStorage (for language preference persistence)

## ✨ Design Highlights

- **Color palette**: Dark backgrounds (`#0a0e17`, `#111827`) with electric blue accents (`#4f6ef7`)
- **Typography**: Space Grotesk for headings, Inter for body text
- **Atmospheric details**: SVG noise texture, glow orbs in hero section
- **Interactive elements**: Hover effects, smooth transitions, 3D tilt on cards
- **Accessibility**: Proper ARIA labels, semantic structure, focus styles

## 📱 Responsive Breakpoints

- Mobile: < 768px
- Tablet: ≥ 768px
- Desktop: ≥ 1024px

## 👨‍💻 About the Developer

**Kaell Brayan Soares Ferraz**
- Estudante de Sistemas de Informação (IFBA) - 2º período
- Técnico em Informática (IFNMG) - Concluído
- Estagiário em Tecnologia na Geniusis
- Front-end developer focusing on clean, functional interfaces
- GitHub: [github.com/BrayanKF](https://github.com/BrayanKF)
- LinkedIn: [linkedin.com/in/kaellb](https://linkedin.com/in/kaellb)
- Email: kaellfrz@gmail.com
- WhatsApp: (33) 99811-4392
- Localização: Vitória da Conquista - BA

---

Feito com ❤️ por Kaell Brayan