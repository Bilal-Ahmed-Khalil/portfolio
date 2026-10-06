# Bilal Ahmed Khalil - Security Researcher Portfolio

Professional portfolio showcasing academic publications, certifications, professional experience, and security research expertise.

## Features

- **Professional Design**: Modern, responsive portfolio website
- **Publications Showcase**: Featured research papers in security
  - MEMORYRIFT: Windows Buffer Overflow and Exploitation Analysis
  - SMOKESCREEN: Active Honeypot Framework
- **Skills Section**: Technical expertise in security, programming, and tools
- **Certifications**: Professional certifications (CEH, CCNA, Python, etc.)
- **Social Links**: Direct links to GitHub and email
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices

## What's Included

```
portfolio/
├── index.html          # Main portfolio website (fully self-contained)
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── certificates/       # Your certificate files (ready to reference)
```

## Getting Started

### View Locally
1. Open `index.html` in any modern web browser
2. No server or build process required - it's a standalone HTML file

### Deploy to GitHub Pages

1. **Create a new GitHub repository**:
   - Go to [github.com/new](https://github.com/new)
   - Name it: `portfolio` (or similar)
   - Make it public

2. **Push to GitHub**:
   ```bash
   cd /path/to/portfolio
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Set source to "main" branch / root folder
   - Your portfolio will be live at: `https://YOUR_USERNAME.github.io/portfolio/`

## Sections

- **Hero**: Introduction with call-to-action buttons
- **Publications**: Your peer-reviewed research papers
- **Skills**: Technical expertise organized by category
- **Certifications**: Professional certifications and training
- **Contact**: Social media and email links

## Customization

The portfolio uses CSS custom properties for easy theming. To customize:

1. Open `index.html`
2. Modify the `:root` section (colors, fonts)
3. Update content in HTML sections
4. Add your own certificate descriptions

Example color changes:
```css
:root {
    --primary-color: #05AD98;      /* Teal accent */
    --page-bg: #E6E9E8;            /* Page background */
    /* ...more variables */
}
```

## Additional Resources

- **Publications**: 
  - MEMORYRIFT: https://ijournalar.com/site/index.php/ijar/article/view/405
  - SMOKESCREEN: https://ijournalar.com/site/index.php/ijar/article/view/838
- **GitHub**: https://github.com/Bilal-Ahmed-Khalil/

## Features Implemented

- Responsive design (mobile-first)
- Smooth scrolling navigation
- Hover animations and transitions
- Smooth scrolling with scroll-linked card animations
- Publication card with links
- Skills organized by category
- Certificate cards with official certificate images
- Social media integration
- Professional color scheme
- Modern typography

## Contact

- **Email**: bilalahmedkhalil05@gmail.com
- **GitHub**: https://github.com/Bilal-Ahmed-Khalil/

## License

© 2026 Bilal Ahmed Khalil. All rights reserved.
