# MyFinanceTeam Website

A professional, responsive website for MyFinanceTeam - a complete finance department solution for growing businesses in Southwestern Ontario.

## About MyFinanceTeam

MyFinanceTeam provides integrated financial services including bookkeeping, accounting, payroll, fractional CFO services, tax planning, and cash flow management for SMBs across Woodstock, London, Kitchener-Waterloo, Cambridge, Hamilton, Guelph, and Windsor.

**Founder:** David Rew  
**Phone:** 519-608-9883  
**Email:** info@myfinanceteam.ca  
**Website:** https://www.myfinanceteam.ca

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Styling:** Custom CSS with CSS Variables
- **Forms:** FormSubmit.co integration
- **Hosting:** GitHub Pages
- **Analytics:** Ready for Google Analytics integration
- **SEO:** Structured data, Open Graph, Twitter Cards

## Design System

### Colors
- **Navy Primary:** #1e3a52
- **Gold Primary:** #d4af37
- **Cream:** #faf8f5
- **White:** #ffffff
- **Text Dark:** #2d2d2d

### Typography
- **Font Stack:** -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif
- **Responsive sizing:** clamp() functions for fluid typography

## File Structure

```
myfinanceteam.ca/
├── index.html              # Homepage
├── bookkeeping.html         # Bookkeeping services
├── accounting.html          # Accounting & reporting services
├── payroll.html            # Payroll services
├── cfo.html                # Fractional CFO services
├── tax.html                # Tax planning services
├── cashflow.html           # Cash flow management services
├── about.html              # About the company
├── process.html            # Company process
├── resources.html          # Resources hub
├── contact.html            # Contact page
├── contact-thank-you.html  # Contact form thank you
├── thank-you.html          # General thank you page
├── sitemap.xml             # SEO sitemap
├── CNAME                   # GitHub Pages domain config
├── favicon.ico             # Website favicon
├── site.webmanifest        # PWA manifest
├── apple-touch-icon.png    # iOS icon
├── favicon-16x16.png       # Small favicon
├── favicon-32x32.png       # Medium favicon
├── android-chrome-192x192.png  # Android icon
├── android-chrome-512x512.png  # Android icon large
└── images/                 # Image assets directory
    ├── logo.png
    ├── og-image.jpg
    ├── hero-images/
    └── icons/
```

## Key Features

### Performance
- Critical CSS inlined for above-the-fold content
- Lazy loading for non-critical images
- Optimized image formats (WebP with fallbacks)
- Minimal JavaScript footprint

### SEO & Accessibility
- Semantic HTML structure
- ARIA labels and roles
- Structured data (JSON-LD)
- Open Graph and Twitter Card metadata
- Proper heading hierarchy
- Alt text for all images
- Focus management for keyboard navigation

### Mobile-First Design
- Responsive grid layouts
- Touch-friendly interactive elements
- Collapsible mobile navigation
- Optimized form inputs for mobile

### Business Features
- Contact form with FormSubmit integration
- Service-specific landing pages
- Resource download tracking
- Phone number click-to-call
- Location-based SEO optimization

## Setup Instructions

### Local Development
1. Clone the repository
```bash
git clone https://github.com/username/myfinanceteam.ca.git
cd myfinanceteam.ca
```

2. Serve locally (Python example)
```bash
python -m http.server 8000
```

3. Open http://localhost:8000 in your browser

### Deployment
The site is configured for GitHub Pages deployment:
1. Push changes to the main branch
2. GitHub Pages automatically deploys from root directory
3. Custom domain configured via CNAME file

## Content Management

### Adding New Service Pages
1. Create new HTML file following the existing template structure
2. Update navigation menus in all pages
3. Add new page to sitemap.xml
4. Create corresponding images in /images/ directory

### Form Configuration
Contact forms use FormSubmit.co with the following configuration:
- Endpoint: `https://formsubmit.co/info@myfinanceteam.ca`
- Captcha disabled
- Custom thank you page redirect
- Honeypot spam protection

### Image Requirements
Each service page requires:
- Hero image (600x500px, WebP format)
- Service icons (64x64px, SVG format)
- Shared assets: logo, og-image, favicons

## SEO Configuration

### Meta Tags
- Page-specific titles and descriptions
- Canonical URLs
- Open Graph metadata
- Twitter Card metadata
- Structured data for organization and services

### Analytics Setup
To add Google Analytics:
1. Add GA4 tracking code to all pages
2. Configure conversion tracking for form submissions
3. Set up goal tracking for resource downloads

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile Safari iOS 14+
- Chrome Mobile 90+

## Performance Metrics

Target scores:
- Lighthouse Performance: 95+
- Lighthouse Accessibility: 100
- Lighthouse Best Practices: 100
- Lighthouse SEO: 100

## Contributing

### Code Style
- Use semantic HTML5 elements
- Follow BEM methodology for CSS classes
- Maintain consistent indentation (2 spaces)
- Comment complex CSS calculations and layouts

### Testing Checklist
- [ ] Cross-browser compatibility
- [ ] Mobile responsiveness (320px to 1920px)
- [ ] Form submission functionality
- [ ] Contact information accuracy
- [ ] Image optimization and loading
- [ ] SEO metadata completeness
- [ ] Accessibility compliance (WCAG 2.1 AA)

## Contact & Support

For technical issues or updates to the website:
- **Development:** Contact the web development team
- **Content Updates:** David Rew (david@myfinanceteam.ca)
- **Hosting Issues:** Check GitHub Pages status

## License

All content and code is proprietary to MyFinanceTeam. Unauthorized reproduction or distribution is prohibited.

---

*Last updated: December 2024*
