# Kenneth Tablang - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Full Stack Developer. Built with clean, semantic HTML, custom CSS, and vanilla JavaScript for optimal performance and maintainability.

![Portfolio Preview](assets/Screenshot%202025-11-30%20182417.png)

## Features

- **Responsive Design** - Fully responsive across all devices (mobile, tablet, desktop)
- **Dark/Light Mode** - Toggle between dark and light themes with smooth transitions
- **Interactive Animations** - Smooth scroll animations, floating orbs, and gradient backgrounds
- **Dynamic Skills Showcase** - Interactive skill cards with progress bars
- **Project Gallery** - Featured projects with descriptions and links to GitHub repositories
- **Theme Persistence** - Your theme preference is saved in localStorage
- **Modern UI/UX** - Clean, contemporary design with gradient accents and smooth transitions
- **Performance Optimized** - Pure vanilla JavaScript, no heavy frameworks

## Tech Stack

### Frontend
- **HTML5** - Semantic markup structure
- **CSS3** - Custom styling with CSS variables for theming
- **JavaScript (ES6+)** - Vanilla JS for interactivity and theme management

### Design & Styling
- **CSS Grid & Flexbox** - Modern layout techniques
- **CSS Variables** - Dynamic theming system
- **CSS Animations** - Smooth transitions and keyframe animations
- **Google Fonts** - Inter font family
- **Custom SVG Icons** - Scalable vector graphics for social links

### Features Implementation
- **Intersection Observer API** - Scroll-based animations
- **LocalStorage API** - Theme preference persistence
- **Smooth Scroll** - Native CSS smooth scrolling
- **Responsive Images** - Theme-aware image switching

## Project Structure

```
kenneth-portfolio/
│
├── assets/
│   ├── icons/           # Technology skill icons
│   ├── fonts/           # Custom fonts (if any)
│   ├── Hero-dark.JPG    # Hero profile image (dark theme)
│   ├── Hero-light.png   # Hero profile image (light theme)
│   ├── Kenneth-dark.png # About section image (dark theme)
│   ├── Kenneth-light.png# About section image (light theme)
│   └── KENNETH TABLANG - Resume.pdf
│
├── index.html           # Main HTML structure
├── styles.css           # All styling and animations
├── script.js            # Interactive functionality
└── README.md            # Project documentation
```

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML, CSS, and JavaScript (for customization)

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/kennethtablang/kenneth-portfolio.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd kenneth-portfolio
   ```

3. **Open in browser**
   - Simply open `index.html` in your preferred web browser

4. **View the portfolio**
   - Local: file:///C:/ThisIs/Your/FileLocation/kenneth-portfolio/index.html
   - Live: Visit [https://kennethtablang.github.io/kenneth-portfolio/](https://kennethtablang.github.io/kenneth-portfolio/)

## Customization Guide

### Changing Colors
Edit CSS variables in `styles.css`:
```css
:root {
  --bg-primary: #0a0a0f;
  --bg-secondary: #141420;
  --text-primary: #ffffff;
  --text-secondary: #a0a0b0;
  --accent-1: #6366f1;
  --accent-2: #8b5cf6;
}
```

### Adding New Projects
Add a new project card in the `index.html` projects section:
```html
<article class="project-card">
  <div class="project-image">
    <img src="your-image.png" alt="Project" />
  </div>
  <div class="project-info">
    <div class="project-date">Month Year</div>
    <h3 class="project-title">Your Project Name</h3>
    <p class="project-description">Description here...</p>
    <div class="project-tags">
      <span class="tag">Technology</span>
    </div>
  </div>
</article>
```

### Updating Skills
Modify skill cards in the skills section with appropriate `data-skill-width` attribute (0-100):
```html
<div class="skill-card" data-skill-width="90">
  <div class="skill-icon">
    <img src="assets/icons/your-icon.svg" alt="Skill" />
  </div>
  <div class="skill-name">Your Skill</div>
  <div class="skill-level">
    <div class="skill-progress"></div>
  </div>
</div>
```

## Responsive Breakpoints

- **Desktop**: 1400px and above
- **Tablet**: 769px - 1399px
- **Mobile**: 768px and below

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

**Kenneth Tablang**
- Email: kennethreytablang@gmail.com
- Phone: +63 995 812 3933
- GitHub: [@kennethtablang](https://github.com/kennethtablang)
- LinkedIn: [kennethtablang](https://www.linkedin.com/in/kennethtablang/)
- Upwork: [Kenneth Tablang](https://www.upwork.com/freelancers/~01fddf02ef494ee037)
- Portfolio: [kennethtablang.github.io](https://kennethtablang.github.io/kenneth-portfolio/)

## Acknowledgments

- Font: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
- Icons: Custom SVG icons
- Inspiration: Modern web design trends and best practices

---

**Built with ❤️ by Kenneth Tablang**

*Last Updated: November 2025*