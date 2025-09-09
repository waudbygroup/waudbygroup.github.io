# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is the website for The Waudby Group (waudbylab.org), a static HTML website hosted via GitHub Pages. The site is built using the "Spectral" template from HTML5 UP and serves as an academic research group website.

## Site Structure

The website consists of several main HTML pages:

- `index.html` - Homepage with news and overview
- `publications.html` - Academic publications list organized by year
- `team.html` - Research group members and profiles  
- `research.html` - Research areas and projects
- `teaching.html` - Teaching materials and courses
- `software.html` - Software tools and resources
- `facilities.html` - Laboratory facilities and equipment
- `sustainability.html` - Sustainability initiatives
- `contact.html` - Contact information

## Key Files and Directories

- `assets/` - Contains CSS, JavaScript, fonts, and other static assets
- `images/` - All image assets including team photos, research images, etc.
- `CNAME` - Custom domain configuration for waudbylab.org
- `nmr-course-2015/` - Archived course materials
- `julia-slides.pdf` - Tutorial materials

## Content Management

### Publications
Publications in `publications.html` are organized in reverse chronological order by year. Each entry follows this structure:
- Author list with Waudby CA highlighted
- Journal name in italics with volume/page info
- Article title
- DOI links using `ai ai-doi` icon class
- PDF links using `icon solid fa-file-pdf` class

### Team Management  
Team member profiles in `team.html` include:
- Profile images stored in `images/` directory
- Academic positions and affiliations
- Brief research descriptions
- Contact information where appropriate

## Deployment

The site is automatically deployed via GitHub Pages when changes are pushed to the main branch. The custom domain waudbylab.org is configured via the CNAME file.

## Template Framework

Built on HTML5 UP's "Spectral" template which includes:
- Responsive design with mobile-first approach
- Font Awesome icons for navigation and links
- jQuery-based interactions and animations
- SASS-based CSS architecture (compiled CSS in assets/css/)

## Common Tasks

When updating content:
- Maintain consistent HTML structure and class names
- Use appropriate icon classes for links (DOI: `ai ai-doi`, PDF: `icon solid fa-file-pdf`)
- Follow existing patterns for team member profiles and publication entries
- Optimize images before adding to `images/` directory
- Test responsive behavior across different screen sizes