# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Infinite Looper Studios hosted on GitHub Pages. The site is a company landing page showcasing their work in software development and design, specializing in minimalist and retro-themed applications and WearOS watch faces.

## Repository Structure

- `index.html` - Main landing page with sections for About, Services, and Contact
- `privacy.html` - Privacy policy page
- `styles.css` - All styling for the website
- `assets/` - Brand assets and images
  - `icon.png` - Company logo
  - `header.png` - Hero section header image
  - `examples/` - Example images (e.g., beam-up.png)

## Development Setup

This is a pure static HTML/CSS website with no build process:
- Open `index.html` directly in a browser for local development
- No installation or dependencies required
- Changes are immediately visible upon page refresh

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the main branch. Access at: https://[username].github.io

## Key Design Elements

- **Color Scheme**: Dark theme with turquoise accent (#40E0D0)
- **Typography**: Inter font from Google Fonts
- **Layout**: Responsive design with mobile breakpoint at 768px
- **Effects**: Glassmorphism cards, smooth transitions, hover states

## Common Tasks

### Adding a New Page
1. Create new HTML file in root directory
2. Copy the basic structure from existing pages
3. Add navigation link in the header nav section
4. Apply consistent styling using existing CSS classes

### Modifying Styles
- All styles are in `styles.css`
- Follow existing naming conventions
- Maintain dark theme consistency
- Test responsiveness at mobile and desktop sizes

### Updating Content
- Service offerings are in the services grid section of `index.html`
- Contact information is in the contact section
- Privacy policy content is in `privacy.html`