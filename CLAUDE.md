# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website project for "TalkUs", a customer service SaaS specialist company. The project consists of a single HTML file with embedded CSS and JavaScript that creates a professional landing page.

## Architecture

- **Single-page application**: All code is contained in `talkus-website.html`
- **Embedded styling**: CSS is included within `<style>` tags in the HTML head
- **Inline JavaScript**: All interactions handled by JavaScript at the end of the HTML body
- **No build process**: Direct HTML file that can be opened in browsers
- **No dependencies**: Uses only CDN resources (Font Awesome, Google Fonts)

## Key Components

- **Header**: Fixed navigation with blur effect on scroll
- **Hero section**: Gradient background with CTA buttons
- **Services grid**: Four service cards with hover animations
- **About section**: Two-column layout with stats grid
- **Testimonials**: Three client testimonial cards
- **Contact section**: WhatsApp integration with contact forms
- **Responsive design**: Mobile-first approach with media queries

## External Dependencies

- Font Awesome 6.0.0 (icons)
- Google Fonts Inter (typography)
- WhatsApp Business API integration

## Development Commands

Since this is a static HTML file:
- **Local development**: Open `talkus-website.html` directly in a web browser
- **Live server**: Use any static file server like Python's `python -m http.server` or VS Code Live Server extension

## Image Integration

The website includes a placeholder for a professional photo in the about section. To add an image:
1. Replace the CSS rule `.professional-photo` background-image URL
2. Or update line 552 in the CSS to point to the actual image file