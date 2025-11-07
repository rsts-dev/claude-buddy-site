# Claude Buddy Official Website

Official website for Claude Buddy - Enterprise-Ready AI Development Platform for Claude Code.

**Live Site**: [https://claude-buddy.dev](https://claude-buddy.dev)

## About

This repository contains the source code for the Claude Buddy official website, featuring:

- Professional landing page with light/dark theme support
- Comprehensive feature showcase and documentation links
- Responsive design optimized for all devices
- Performance-optimized static site

## Quick Start

### Local Development

```bash
# Clone the repository
git clone https://github.com/rsts-dev/claude-buddy-site.git
cd claude-buddy-site

# Open in browser
open index.html
# or
python -m http.server 8000  # Then visit http://localhost:8000
```

### File Structure

```
claude-buddy-site/
├── index.html              # Main landing page
├── assets/
│   ├── css/
│   │   └── style.css       # Styling with theme support
│   ├── js/
│   │   └── main.js         # Interactive functionality
│   └── images/
│       └── *.svg           # Logo and brand assets
├── sitemap.xml             # SEO sitemap
├── robots.txt              # Search engine directives
├── CNAME                   # Custom domain configuration
├── DESIGN.md               # Detailed design documentation
└── README.md               # This file
```

## Features

- **Light/Dark Mode**: Automatic theme detection with manual toggle
- **Responsive Design**: Optimized for desktop, tablet, and mobile
- **Fast Loading**: Minimal dependencies, optimized assets
- **Accessibility**: WCAG-compliant with keyboard navigation
- **SEO Optimized**: Semantic markup, structured data, sitemap

## Technologies

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern CSS with custom properties, Grid, and Flexbox
- **Vanilla JavaScript**: No external dependencies
- **Styrene Font Stack**: Typography matching Claude Code design

## Design System

The website follows Claude Code's design principles with:
- Warm brown accent colors (#D4A27F)
- Professional, developer-focused aesthetic
- Minimal animations for better performance
- Clean, readable typography

See [DESIGN.md](DESIGN.md) for detailed design documentation.

## Deployment

The site is deployed to GitHub Pages at [claude-buddy.dev](https://claude-buddy.dev).

### Deploy to GitHub Pages

1. Push changes to the `main` branch
2. GitHub Actions automatically deploys to gh-pages
3. Site updates in ~1-2 minutes

### Deploy to Other Platforms

**Netlify**:
```bash
# Deploy directory: ./
netlify deploy --prod
```

**Vercel**:
```bash
# Deploy directory: ./
vercel --prod
```

## Related Repositories

- **Plugin Marketplace**: [rsts-dev/claude-buddy-marketplace](https://github.com/rsts-dev/claude-buddy-marketplace) - Claude Code plugin distribution
- **Main Repository**: [rsts-dev/claude-buddy](https://github.com/rsts-dev/claude-buddy) - Core development repository

## Contributing

We welcome contributions to improve the website:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes
4. Push to your fork
5. Open a Pull Request

## License

MIT License - see [LICENSE](../LICENSE) in the main repository

Copyright (c) 2025 Claude Buddy Contributors

## Support

- **Website Issues**: [GitHub Issues](https://github.com/rsts-dev/claude-buddy-site/issues)
- **Plugin Support**: [Marketplace Issues](https://github.com/rsts-dev/claude-buddy-marketplace/issues)
- **Documentation**: [claude-buddy.dev](https://claude-buddy.dev)

---

**Made with ♾️ for the Claude Code community**
