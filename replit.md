# BG Neighbors

## Overview
BG Neighbors is a community service website for Bowling Green, KY that connects neighbors in need with neighbors who care. The site provides information about getting help, volunteering, donating, and learning about the organization.

## Project Type
Static HTML website with client-side page transitions

## Technology Stack
- HTML5
- CSS3 (with Pico CSS framework)
- JavaScript (Barba.js for page transitions, GSAP for animations)
- Python HTTP server for local development

## Project Structure
```
├── index.html          # Home page with main navigation
├── help.html           # Information for those needing help
├── volunteer.html      # Volunteer opportunities
├── donate.html         # Donation information
├── learn.html          # About the organization
├── about.html          # Additional about page (fragment)
├── script.js           # Barba.js page transitions
├── style.css           # Custom styles
└── public/             # Static assets
    └── vite.svg
```

## Features
- Smooth page transitions using Barba.js
- Responsive design with Pico CSS
- Clean, accessible interface
- Multiple pathways for community engagement

## Pages
1. **Home** (`index.html`) - Main landing page with four call-to-action buttons
2. **Need Help** (`help.html`) - Resources for community members seeking assistance
3. **Volunteer** (`volunteer.html`) - Information about volunteering opportunities
4. **Donate** (`donate.html`) - Donation options and information
5. **Learn** (`learn.html`) - About the organization and its mission

## Development
The site runs on a Python HTTP server on port 5000 for Replit compatibility.

## Recent Changes
- 2025-11-09: Initial import and Replit environment setup
