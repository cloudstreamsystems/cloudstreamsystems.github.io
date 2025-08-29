# Overview

This is a personal portfolio website for Cloudstream Systems, a full-stack developer based in Accra, Ghana. The site is built using Jekyll static site generator and is designed to showcase the developer's skills, projects, and professional information. It features a modern design with a hero section, about page, and projects showcase, serving as an online presence for potential clients and employers.

**Status**: ✅ Successfully configured for Replit environment and deployed
- Jekyll development server running on port 5000 
- Configured for Replit proxy compatibility (0.0.0.0 host)
- Custom layouts and includes created for proper rendering
- Deployment configuration set up for production

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Static Site Generation
The project uses Jekyll as the static site generator, which transforms Markdown files into HTML. This approach provides excellent performance, security, and hosting simplicity since no server-side processing is required. The site can be easily deployed to GitHub Pages or any static hosting service.

## Theme and Layout System
Built on the Minima theme for Jekyll, the site uses a clean, minimalist design approach. The theme provides a responsive foundation with customizable components including headers, footers, and navigation. Custom styling is added through additional CSS to enhance the visual presentation.

## Content Management
Content is organized using Markdown files for easy editing and maintenance:
- `index.md` serves as the homepage with hero section
- `about.md` contains detailed information about the developer
- `projects.md` showcases completed projects and work samples

## Frontend Architecture
The site uses semantic HTML5 structure with responsive CSS design. Custom styling includes a full-viewport hero section with centered content, smooth scrolling effects, and mobile-friendly navigation. JavaScript is minimal, focusing on progressive enhancement for scroll-based header effects.

## File Structure Organization
```
├── _includes/          # Reusable HTML components
├── _site/             # Generated static files
├── assets/            # CSS, JS, and other assets
├── *.md               # Content pages in Markdown
└── README.md          # Project documentation
```

# External Dependencies

## Jekyll Framework
- **Jekyll 3.10.0**: Static site generator that processes Markdown and Liquid templates
- **Minima Theme**: Provides base styling and layout structure
- **Jekyll SEO Tag**: Automatic meta tag generation for search engine optimization

## Web Standards
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox and responsive design
- **JavaScript ES6+**: Minimal client-side interactions

## Hosting Platform
- **GitHub Pages**: Designed for deployment on GitHub's static hosting service
- Compatible with any CDN or static hosting provider

## Development Tools
- **Git**: Version control system for code management
- **Markdown**: Content authoring format for easy editing