# ⚡ Jaswanth's Portfolio

A modern, responsive, interactive portfolio website showcasing skills, projects, certifications, and contact information with a terminal-inspired design aesthetic.

**Live Demo:** [https://jaswanthyandrapalli.github.io/CodeAlpha_Jaswanth-sPortfolio](https://jaswanthyandrapalli.github.io/CodeAlpha_Jaswanth-sPortfolio)

---

## 🎯 Project Overview

This portfolio is a fully responsive web application featuring:
- Interactive terminal-based home page with command navigation
- Modern, minimalist design with CRT scanline effects and neon glows
- Complete responsive design for mobile, tablet, and desktop devices
- Dark/Light mode toggle across all pages
- Animated components with smooth transitions
- Professional project showcase and certifications display
- Contact page with social media integration

---

## ✨ Key Features

### 🎨 **Design & UX**
- ✅ Custom SVG favicon with animated cursor design
- ✅ CRT scanline effects and retro visual styling
- ✅ Terminal-inspired command interface with typing animations
- ✅ Dark/Light mode toggle with persistent theme
- ✅ Glitch animations and border glow effects
- ✅ Smooth scroll behavior and transition effects

### 📱 **Responsive Design**
- ✅ **Mobile First Approach** - Optimized for phones (up to 480px)
- ✅ **Tablet Support** - Perfect layout for tablets (481px - 768px)
- ✅ **Desktop Experience** - Enhanced experience on larger screens (769px+)
- ✅ Touch-friendly buttons with 44px minimum height
- ✅ Flexible grid layouts that adapt to screen size
- ✅ Optimized typography for each breakpoint

### 🔧 **Technical Features**
- ✅ HTML5 semantic markup
- ✅ CSS3 with custom animations and media queries
- ✅ Vanilla JavaScript (no frameworks)
- ✅ Tailwind CSS integration
- ✅ SVG-based favicon system with PNG/ICO fallbacks
- ✅ Git version control with meaningful commits
- ✅ GitHub Pages deployment ready

---

## 📁 File Structure

```
jaswant_updated_protfolio/
├── index.html                          # Root entry point (terminal home)
├── README.md                           # Project documentation
├── LICENSE                             # MIT License
├── about-me/
│   ├── styles.css                      # Shared styles
│   └── script.js                       # Utility scripts
├── portfolio-cmd/
│   ├── about.html                      # About/Home page
│   ├── projects.html                   # Projects showcase
│   ├── skills.html                     # Technical skills
│   ├── certifications.html             # Certifications display
│   ├── connect.html                    # Contact & Social links
│   ├── favicon.svg                     # Animated SVG favicon
│   ├── favicon.ico                     # ICO fallback
│   ├── icons8-circled-j-50.png         # Icon asset
│   ├── css/
│   │   ├── styles.css                  # Page-specific styles
│   │   └── tailwind.css                # Tailwind configuration
│   ├── js/
│   │   └── terminal.js                 # Terminal command engine
│   └── assets/
│       └── resume.pdf                  # CV/Resume download
└── node_modules/                       # Dependencies (optional)
```

---

## 🛠️ Technology Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic markup structure |
| **CSS3** | Styling, animations, media queries |
| **JavaScript** | Interactivity, terminal commands |
| **Tailwind CSS** | Utility-first CSS framework |
| **SVG** | Vector graphics & favicon |
| **Git** | Version control |
| **GitHub Pages** | Deployment & hosting |

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)
- Git installed locally

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jaswanthyandrapalli/CodeAlpha_Jaswanth-sPortfolio.git
   cd jaswant_updated_protfolio
   ```

2. **Start a local server:**
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Python 2
   python -m SimpleHTTPServer 8000
   ```

3. **Open in browser:**
   ```
   http://localhost:8000
   ```

### Making Changes

1. Edit files in the `portfolio-cmd/` directory
2. Refresh browser to see changes
3. Commit and push when ready:
   ```bash
   git add -A
   git commit -m "Description of changes"
   git push origin main
   ```

---

## 📄 Pages Overview

### **Root Index** (`/index.html`)
Interactive terminal-style homepage with command navigation
- Commands: `cd about`, `cd projects`, `cd skills`, `cd certifications`, `cd connect`
- Typing animation on page load
- CRT scanline visual effects

### **About** (`/portfolio-cmd/about.html`)
Personal introduction and background
- Animated terminal cards with glitch effects
- About section with detailed information
- Smooth scroll animations
- Dark/Light mode toggle

### **Projects** (`/portfolio-cmd/projects.html`)
Showcase of completed projects
- Grid layout with project cards
- Project descriptions and tech stacks
- GitHub repository links
- Responsive multi-column layout

### **Skills** (`/portfolio-cmd/skills.html`)
Technical skills and proficiency levels
- Skill categories with progress bars
- Visual proficiency indicators
- Organized skill grouping
- Responsive card layout

### **Certifications** (`/portfolio-cmd/certifications.html`)
Professional certifications and courses
- Certification cards with details
- Issuer and completion dates
- Animated card reveal effects
- Hover interactions with glitch effects

### **Connect** (`/portfolio-cmd/connect.html`)
Contact information and social media links
- Email contact section
- Social media links (GitHub, Instagram, LinkedIn)
- CV/Resume download
- Dark mode support

---

## 🎨 Design Features

### **Responsive Breakpoints**

#### Mobile (Up to 480px)
- Single column layouts
- Font-size: 12-14px for body text
- Touch-friendly buttons (44px min-height)
- Optimized padding and margins
- Better word-breaking

#### Tablet (481px - 768px)
- 2-column grid layouts
- Font-size: 14px for body text
- Medium padding: 16-20px
- Balanced spacing
- Improved readability

#### Desktop (769px+)
- Multi-column layouts with auto-fill
- Font-size: 16px for body text
- Comfortable padding: 20-32px
- Full animations enabled
- Enhanced visual depth

### **Visual Effects**
- CRT scanline overlay
- Noise texture background
- Animated glitch text effects
- Border glow animations
- Smooth transitions (0.3s - 0.8s)
- Hover scale transformations

---

## 📦 Updates & Improvements

### Version 1.0 - Initial Release
- ✅ Root index.html with terminal interface
- ✅ 5 main portfolio pages
- ✅ Favicon system (SVG + PNG + ICO)
- ✅ Dark/Light mode toggle
- ✅ Mobile responsive design
- ✅ Terminal command navigation
- ✅ Animated welcome messages
- ✅ CRT visual effects

### Latest Updates
- ✅ Enhanced mobile responsive design
- ✅ Better touch target sizing (44px minimum)
- ✅ Improved typography hierarchy
- ✅ Added stylesheet linkage across all pages
- ✅ Fixed navigation paths
- ✅ Responsive improvements for all breakpoints
- ✅ Professional button and link styling
- ✅ Better spacing and visual hierarchy on mobile

---

## 🔄 Navigation Flow

```
Root (index.html)
    ↓
Terminal Interface (terminal.js)
    ├─→ cd about → portfolio-cmd/about.html
    ├─→ cd projects → portfolio-cmd/projects.html
    ├─→ cd skills → portfolio-cmd/skills.html
    ├─→ cd certifications → portfolio-cmd/certifications.html
    ├─→ cd connect → portfolio-cmd/connect.html
    └─→ help → Shows available commands

Each Page:
    ↓
Back Button (>>>)
    ↓
Returns to Root (index.html)
```

---

## 🎯 Responsive Design Features

### Mobile Optimizations
- ✅ Minimum touch target size of 44px × 44px
- ✅ Readable font sizes (12-14px minimum)
- ✅ Proper line-height for readability (1.5+)
- ✅ Adequate spacing between interactive elements
- ✅ Single-column layouts
- ✅ Optimized images and assets

### Tablet Optimizations
- ✅ 2-column grid layouts
- ✅ Better use of horizontal space
- ✅ Balanced typography
- ✅ Improved spacing

### Desktop Enhancements
- ✅ Multi-column layouts
- ✅ Advanced animations
- ✅ Full visual effects
- ✅ Optimal viewing experience

---

## 📋 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| IE 11 | ⚠️ Limited (no CSS3 animations) |

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### MIT License Summary
- ✅ Free to use, modify, and distribute
- ✅ Commercial and private use allowed
- ✅ Must include license and copyright notice
- ✅ No warranty provided
- ✅ No liability for authors/contributors

**Copyright © 2026 YANDRAPALLI JASWANTH**

For the full license text, see [LICENSE](LICENSE) file.

---

## 🤝 Contributing

While this is a personal portfolio, suggestions and feedback are welcome!

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Commit with clear messages
5. Push to your fork
6. Submit a pull request

---

## 📞 Contact

**Jaswanth Yandrapalli**
- 📧 Email: [yandrapallijaswanth@gmail.com](mailto:yandrapallijaswanth@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/yandrapalli-jaswanth-412161339](https://www.linkedin.com/in/yandrapalli-jaswanth-412161339)
- 🐙 GitHub: [github.com/jaswanthyandrapalli](https://github.com/jaswanthyandrapalli)
- 📸 Instagram: [@jaswanth22_chowdary](https://www.instagram.com/jaswanth22_chowdary?igsh=bXF5eDd2NGRudTZi)

---

## 📚 Resources Used

- [MDN Web Docs](https://developer.mozilla.org/)
- [Tailwind CSS Documentation](https://tailwindcss.com/)
- [CSS-Tricks](https://css-tricks.com/)
- [Web Design Best Practices](https://www.w3.org/WAI/)
- [Responsive Design Patterns](https://www.smashingmagazine.com/)

---

## 🎓 Certifications & Learning

This portfolio showcases expertise in:
- HTML5 & Semantic Markup
- CSS3 & Advanced Animations
- Responsive Web Design
- JavaScript & DOM Manipulation
- Git & Version Control
- GitHub Pages Deployment
- UI/UX Design Principles
- Accessibility Standards

---

## 📝 Notes

- All changes are version controlled with Git
- Portfolio is automatically deployed via GitHub Pages
- Responsive design is mobile-first approach
- All assets are optimized for performance
- Dark mode toggle is persistent across sessions

---

**Last Updated:** March 18, 2026  
**Status:** ✅ Complete and Deployed  
**Repository:** [CodeAlpha_Jaswanth-sPortfolio](https://github.com/jaswanthyandrapalli/CodeAlpha_Jaswanth-sPortfolio)

