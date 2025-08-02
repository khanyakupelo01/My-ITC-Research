# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an academic portfolio website for Sibulele Khanya Kupelo showcasing IT services and technology solutions research. The repository demonstrates academic work in mobile assessment technology and design science research methodology. The website serves as a digital portfolio highlighting research achievements, particularly the "Mobile Assessment and Annotation Tool V2" developed as part of a Bachelor of Commerce degree at Nelson Mandela University.

## Academic Context

The research documented in `treatise.txt` focuses on:

- **Mobile Assessment Technology**: Development of Android-based assessment tools for educational institutions
- **Design Science Research Methodology**: Following systematic research phases including artifact design, development, demonstration, and evaluation
- **User Experience Research**: Conducting usability studies with lecturers to evaluate mobile assessment tools
- **Academic Standards**: Peer-reviewed research with quality assurance and institutional partnerships

## Repository Structure

The project follows clean separation of concerns:

- `Research/` - Main project directory containing:
  - `index.html` - Clean HTML structure showcasing academic portfolio (442 lines)
  - `styles.css` - Separated CSS file with modern academic design system
  - `treatise.txt` - Academic research document: "Mobile Assessment and Annotation Tool V2" (Bachelor of Commerce thesis)
  - `treatise.pdf` - PDF version of the research document
  - `SK KUPELO 212301195 - Copy (1).docx` - Additional academic document

## Architecture

### HTML Structure
The `index.html` file is a clean academic portfolio featuring:
- Semantic HTML structure with academic content focus
- Research-focused navigation (Research, Methodology, Achievements)
- Mobile Assessment Tool V2 as primary research showcase
- Academic credentials and Design Science Research methodology
- Links to external CSS file (`styles.css`)
- Font Awesome icons via CDN
- Google Fonts (Inter) integration

### Design System
- Color scheme: Primary (#191654), Secondary (#43C6AC)
- CSS custom properties for theming (`--bg-primary`, `--text-primary`, etc.)
- Gradient system with hero and card gradients
- Shadow system with multiple elevation levels
- Spacing and radius variables for consistency

### Page Sections

- Navigation with smooth scrolling and academic focus
- Hero section highlighting Mobile Assessment & Annotation Tool V2 research
- Research Focus Areas section (Mobile Assessment Technology, Symbol Recognition, etc.)
- Design Science Research Methodology section (systematic research phases)
- Academic Achievements section (university credentials, research validation)
- Contact section for academic collaboration and research inquiries

## Development Commands

This is a static HTML project with no build system. To work with it:

### Local Development

```bash
# Serve the file locally (using any static server)
python -m http.server 8000
# or
npx serve Research/
```

### File Editing

- The entire application is in `Research/index.html`
- No build process required - changes are immediately visible
- Use browser developer tools for testing responsive design

## Key Technical Details

### CSS Architecture

- Uses CSS custom properties extensively for theming
- Dark mode implementation via `[data-theme="dark"]` attribute
- Modern CSS with flexbox and grid layouts
- Animation system using CSS transitions and transforms

### Responsive Design

- Mobile-first responsive breakpoints
- Flexible navigation that collapses on mobile
- Responsive typography and spacing
- Touch-friendly interaction targets

### Clean Architecture
- Vanilla HTML/CSS/JavaScript only
- No package.json or build tools
- Separated CSS file (styles.css) for maintainability
- CDN dependencies: Font Awesome, Google Fonts

## Coding Guidelines

- Use comments sparingly. Only comment complex code.

## Git Workflow
- Main branch: `main`
- Current status shows modified `Research/index.html`
- No specific branching strategy defined