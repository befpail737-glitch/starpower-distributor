# Starpower Distributor Website

A professional, SEO-optimized website for LiTong Electronics, an authorized distributor of Starpower Semiconductor power modules.

## Project Overview

This website has been created according to the detailed requirements specified in the prompt document. It features:

- Modern, responsive design using Bootstrap 5
- Comprehensive SEO optimization with proper meta tags, structured data, and semantic HTML
- Complete site structure including:
  - Homepage
  - Products section with detailed module pages
  - Solutions section for industry applications
  - Technical support resources
  - News and company information
  - About Us and Contact pages
  - FAQ section
- Schema.org structured data markup for better search engine visibility
- XML sitemap and robots.txt for search engine indexing

## Key Features

1. **SEO Optimization**
   - Clean URL structure
   - Comprehensive meta tags
   - Schema.org structured data (Organization, Product, Article, NewsArticle)
   - Image alt attributes
   - Semantic HTML structure

2. **Responsive Design**
   - Mobile-first approach
   - Fully responsive layout for all device sizes
   - Touch-friendly navigation

3. **Content Organization**
   - Logical site architecture
   - Breadcrumb navigation
   - Related content modules
   - Clear CTAs throughout

4. **Technical Implementation**
   - Modern HTML5 and CSS3
   - Bootstrap 5 framework
   - Vanilla JavaScript for interactive elements
   - No external dependencies beyond CDN-hosted libraries

## File Structure

```
starpower-web/
├── index.html              # Homepage
├── about.html              # About Us page
├── contact.html            # Contact page
├── faq.html                # Frequently Asked Questions
├── 404.html                # Error page
├── styles.css              # Main stylesheet
├── sitemap.xml             # XML sitemap
├── robots.txt              # Search engine directives
├── DEPLOYMENT.md           # Deployment instructions
├── products/               # Products section
│   ├── index.html          # Products listing
│   ├── igbt-modules.html   # IGBT modules category
│   ├── igbt-modules/
│   │   ├── gd10pja120l2s.html  # IGBT module detail
│   │   ├── gd40pjt120l3s.html  # IGBT module detail
│   │   └── gd75pit120c5s.html  # IGBT module detail
│   ├── sic-modules.html    # SiC modules category
│   ├── sic-modules/
│   │   └── gcm300m12k-m1.html  # SiC module detail
│   ├── ipm-modules.html    # IPM modules category
│   ├── ipm-modules/
│   │   └── gd50lif060c5s.html  # IPM module detail
│   └── mosfet-modules.html # MOSFET modules category
├── solutions/              # Solutions section
│   ├── index.html          # Solutions listing
│   ├── ev-charging.html    # EV charging solution
│   ├── solar-inverters.html # Solar inverter solution
│   ├── industrial-control.html # Industrial control solution
│   ├── ups-systems.html    # UPS systems solution
│   └── home-appliances.html # Home appliances solution
├── support/                # Support section
│   ├── index.html          # Support overview
│   ├── guides/
│   │   └── module-selection.html  # Module selection guide
│   ├── application-notes/
│   │   └── index.html      # Application notes listing
│   └── troubleshooting/
│       └── index.html      # Troubleshooting guides listing
└── news/                   # News section
    ├── index.html          # News listing
    ├── litong-10-years-starpower.html  # Company news
    ├── reliable-distributor-guide.html # Industry insight
    └── distributor-advantages.html     # Industry insight
```

## Deployment

This is a static website that can be deployed to any web hosting service. Detailed deployment instructions for Cloudflare Pages are provided in `DEPLOYMENT.md`.

To deploy:
1. Upload all files to your web server
2. Configure your domain's DNS settings to point to your hosting service
3. Verify the site is accessible and all links work correctly

## Customization

To customize this website for your specific needs:
1. Replace placeholder content with your actual content
2. Update contact information in the contact page and footer
3. Add more product, solution, and support pages as needed
4. Update the sitemap.xml with new pages
5. Customize the color scheme by modifying the CSS variables in styles.css

## Browser Support

This website supports all modern browsers including:
- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome for Android)

## License

This website template is provided for use by LiTong Electronics as an authorized Starpower distributor. All content and design elements are proprietary to LiTong Electronics and Starpower Semiconductor.