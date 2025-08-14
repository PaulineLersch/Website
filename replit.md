# PL IMMO - Property Management Website

## Overview

PL IMMO is a professional property management company website built as a single-page application for Pauline Lersch's real estate management business in Eschweiler, Germany. The site serves as a comprehensive digital presence showcasing property management services including rental management, technical management, and commercial administration. Built as a complete standalone HTML file with integrated CSS and JavaScript, it features a modern corporate design, responsive layout, and GDPR-compliant structure.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The application follows a **single-file architecture** approach, combining HTML, CSS, and JavaScript into one comprehensive index.html file. This design choice eliminates external dependencies and ensures fast loading times while maintaining professional presentation.

**Design System:**
- Corporate color scheme centered around primary blue (#556280)
- Inter font family for modern typography
- Mobile-first responsive design using CSS Grid and Flexbox
- Component-based styling with CSS custom properties (variables)
- Modern architectural background pattern with inline SVG data-URL integration
- Realistic city skyline with detailed building silhouettes, windows, rooftops, and architectural features
- Multi-tonal blue color scheme (#556280, #657090, #445370) with white accents for contrast
- Special Hero-section overlay with enhanced visibility using white gradients and blend modes

**Page Structure:**
- Single-page application with hash-based navigation
- Section-based content organization (Hero, Services, Contact, Legal)
- Collapsible service listings using HTML5 `<details>` elements
- Integrated legal pages (Impressum, Privacy Policy) as separate sections

### Content Management
**Static Content Architecture:**
- All content embedded directly in HTML
- No external content management system
- Service catalog implemented as expandable sections
- Contact information hardcoded for reliability

**Navigation System:**
- Smooth scrolling navigation between sections
- Mobile-responsive hamburger menu
- Quick access to legal compliance pages

### Communication Features
**Contact Integration:**
- Direct mailto: links for email communication
- WhatsApp integration with click-to-chat functionality
- Tel: links for immediate phone contact
- Contact form using browser's native mailto handler

### Legal Compliance Framework
**GDPR Architecture:**
- Complete privacy policy integrated as dedicated section
- Cookie-free design to minimize data collection
- Explicit mention of external image usage from stock photo services
- Comprehensive legal disclaimers and liability limitations

## External Dependencies

### Third-Party Services
**Font Services:**
- Google Fonts (Inter font family) via CDN
- Fallback to system fonts for reliability

**Image Resources:**
- Unsplash/Pixabay for stock photography
- External image URLs for hero backgrounds and visual elements
- No local image storage to maintain single-file architecture

**Communication Platforms:**
- WhatsApp Business integration (wa.me links)
- Standard email services (mailto: protocol)
- Telephone system integration (tel: protocol)

**Social Media:**
- Instagram profile linking
- Open Graph meta tags for social media sharing
- Twitter Card integration for enhanced social presence

### Browser Dependencies
**Native Features:**
- HTML5 semantic elements for structure
- CSS Grid and Flexbox for responsive layouts
- CSS Custom Properties for theming
- Native form validation
- Smooth scrolling behavior

**No External Frameworks:**
- No JavaScript libraries or frameworks
- No CSS preprocessors
- No build tools or bundlers required
- Direct browser compatibility approach