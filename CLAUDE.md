# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal academic portfolio website for Mingyuan Chen, a Postdoctoral Research Fellow at University of Exeter. The site is a static single-page website with no build process.

## Architecture

- **index.html**: Single-page static site containing all content and styling
- **Doc/**: PDF documents (CV, research papers)
- **Image/**: Profile photo and other images

## Technology Stack

- Pure HTML with inline CSS
- Tailwind CSS loaded via CDN (v2.2.19)
- Google Fonts (Inter)
- No JavaScript framework, build tools, or package manager

## Development

To preview the site locally, open `index.html` directly in a browser or use any static file server:

```bash
python3 -m http.server 8000
```

## Deployment

The site is hosted via GitHub Pages at https://mingyuanchen94.github.io/website/

## Design System

- Color scheme: Gray backgrounds with red (#ef4444) accents
- Typography: Inter font family
- Layout: Responsive grid (single column on mobile, 8/4 split on desktop)
- Custom CSS classes: `.profile-img`, `.skill-tag`, `.hover-underline-animation`
