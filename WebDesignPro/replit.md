# Overview

This is a frontend developer portfolio website for Jashita Rachakonda. The project is a single-page application built with pure HTML, CSS, and JavaScript, showcasing professional skills, projects, and contact information. The portfolio features a modern, responsive design with smooth animations and a clean aesthetic using a lavender and purple color scheme.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Static Single-Page Application**: Built with vanilla HTML, CSS, and JavaScript for simplicity and fast loading
- **Responsive Design**: Mobile-first approach using Tailwind CSS framework for consistent styling across devices
- **Component-Based Structure**: Organized into logical sections (navbar, hero, about, skills, projects, contact) within a single HTML file
- **Animation System**: Implements AOS (Animate On Scroll) library for smooth scroll-triggered animations and custom CSS keyframe animations

## Styling Framework
- **Tailwind CSS**: Utility-first CSS framework loaded via CDN for rapid styling and consistent design system
- **Custom Color Palette**: Extended Tailwind configuration with custom lavender color variants and theme customizations
- **Typography**: Inter font for body text and Playfair Display for headings, creating visual hierarchy
- **Animation Engine**: Custom CSS animations (float, glow) combined with AOS library for interactive user experience

## Design Patterns
- **Progressive Enhancement**: Core content accessible without JavaScript, with animations as enhancement layer
- **Atomic Design**: Modular approach with reusable utility classes and consistent spacing/sizing patterns
- **Performance Optimization**: CDN-based dependencies for faster loading and minimal custom CSS

# External Dependencies

## CSS Framework
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **Google Fonts**: Inter and Playfair Display font families for typography
- **Font Awesome**: Icon library for visual elements

## Animation Libraries
- **AOS (Animate On Scroll)**: Scroll-triggered animation library for enhanced user interactions
- **Custom CSS Animations**: Keyframe-based animations for floating and glowing effects

## Development Approach
- **Static Hosting Ready**: No build process required, can be deployed directly to any static hosting service
- **CDN Dependencies**: All external libraries loaded via CDN for reduced bundle size and faster initial load