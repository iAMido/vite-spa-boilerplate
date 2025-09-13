# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Structure

This repository contains two separate projects:

1. **Resume Website** (Root directory): A static HTML/CSS resume website for Ido Mosseri
   - `index.html` - Main resume content and structure
   - `styles.css` - Responsive styling with mobile-first design

2. **Vite SPA Boilerplate** (`vite-spa-boilerplate/`): A modern single-page application template
   - Built with Vite for fast development
   - Uses ES modules and modern JavaScript
   - Includes Hot Module Replacement (HMR)

## Common Development Commands

### For Vite SPA Boilerplate (`vite-spa-boilerplate/` directory):
```bash
cd vite-spa-boilerplate
npm install          # Install dependencies
npm run dev          # Start development server (http://localhost:5173)
npm run build        # Build for production
npm run preview      # Preview production build locally
```

### For Resume Website (Root directory):
- No build process required - static HTML/CSS files
- Open `index.html` directly in browser for development
- Use a local server for testing (e.g., `npx serve .`)

## Architecture Notes

### Resume Website
- Pure HTML/CSS implementation with no JavaScript dependencies
- Responsive design with mobile breakpoints at 768px and 480px
- Two-column layout: 60% content, 40% profile image
- Uses Inter font family from Google Fonts
- Color scheme based on #8B9A8E accent color

### Vite SPA Boilerplate
- Standard Vite project structure with `src/main.js` as entry point
- Modular JavaScript with ES6 imports
- Vanilla JavaScript counter component example
- CSS imports handled by Vite's build system
- Production builds output to `dist/` directory

## Development Notes

- The repository is not currently a Git repository
- Node.js version 18+ required for Vite project
- No linting or testing configurations present
- Projects are completely independent and can be worked on separately
- after each code change, make sure to commit and push it
- please commit and push the code into https://github.com/iAMido/vite-spa-boilerplate