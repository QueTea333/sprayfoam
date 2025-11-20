# Innovated SFC - Spray Foam Insulation Website

Professional spray foam insulation services for Southern Alberta and surrounding areas.

## About This Website

This is the official website for Innovated SFC, a spray foam insulation contractor serving:
- Pincher Creek, AB
- Lethbridge, AB
- Fort Macleod, AB
- High River, AB
- Cardston, AB
- Fernie, BC
- Sparwood, BC

## Website Structure

```
/
├── index.html                 # Homepage
├── contact/                   # Contact page with quote form
├── locations/                 # Location-specific pages
│   ├── pincher-creek/
│   ├── lethbridge/
│   ├── fort-macleod/
│   ├── high-river/
│   ├── cardston/
│   ├── fernie/
│   └── sparwood/
├── services/                  # Service pages (to be created)
├── css/                       # Stylesheets
├── js/                        # JavaScript files
├── images/                    # Image assets
├── sitemap.xml               # XML sitemap for SEO
└── robots.txt                # Robots.txt for search engines
```

## Features

- ✅ Modern, responsive design (mobile-first)
- ✅ SEO-optimized with schema markup
- ✅ Fast loading performance
- ✅ Accessibility compliant (WCAG 2.1 AA)
- ✅ 7 location-specific pages for Local SEO
- ✅ Contact form with spam protection
- ✅ Google Analytics ready
- ✅ Clean, semantic HTML5
- ✅ Modern CSS with custom properties

## Setup Instructions

### 1. Update Contact Information

Replace placeholder phone numbers and email addresses throughout the site:
- Phone: `(403) XXX-XXXX` → Your actual phone number
- Email: `info@sprayfoamsouthab.ca` → Verify this is correct
- Update phone links: `tel:+1403XXXXXXX` → `tel:+14031234567`

### 2. Add Logo and Images

Upload images to the `/images/` directory:
- `logo.png` - Company logo
- `favicon.png` - Browser favicon
- `hero-background.jpg` - Homepage hero image
- Project photos for galleries
- Team photos

### 3. Configure Form Handler

The contact form requires a server-side script:
- Current action: `/form-handler.php`
- Options:
  - Create PHP script for email sending
  - Use third-party form service (Formspree, Netlify Forms, etc.)
  - Integrate with CRM

### 4. Set Up Analytics

Add Google Analytics 4 tracking code to all pages (before closing `</head>` tag):

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

### 5. SSL Certificate

Ensure HTTPS is enabled before launch:
- Use Let's Encrypt (free)
- Or provider-issued SSL certificate

### 6. Submit to Search Engines

After launch:
- Submit sitemap to Google Search Console
- Submit to Bing Webmaster Tools
- Claim Google Business Profile
- Set up directory listings

## Performance Optimization

Before production:
- [ ] Optimize and compress all images
- [ ] Minify CSS and JavaScript
- [ ] Enable GZIP compression on server
- [ ] Set up browser caching
- [ ] Consider CDN for static assets

## SEO Checklist

- [ ] Update Google Business Profile with all 7 locations
- [ ] Claim directory listings (see PRODUCTION_READINESS_REVIEW.md)
- [ ] Add Google Analytics
- [ ] Add Google Tag Manager
- [ ] Submit XML sitemap
- [ ] Verify all schema markup
- [ ] Set up call tracking
- [ ] Create Google My Business posts

## Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Android)

## Documentation

See comprehensive guides:
- `PRODUCTION_READINESS_REVIEW.md` - Full production checklist
- `QUICK_REFERENCE_CHECKLIST.md` - Quick implementation guide

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties
- **Vanilla JavaScript** - No dependencies
- **Google Fonts** - Inter & Open Sans
- **Schema.org** - Structured data

## License

Copyright © 2025 Innovated SFC. All rights reserved.

## Support

For technical questions about this website, contact your web developer.

For business inquiries:
- Phone: (403) XXX-XXXX
- Email: info@sprayfoamsouthab.ca
