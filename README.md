# Exploring Angkor Wat: A Digital Discovery Guide

An interactive, multi-page informational website about Khmer heritage, Angkor Wat history, temple architecture, visual exploration, and visitor planning.

## Table of Contents

- [Project Overview](#project-overview)
- [Course Information](#course-information)
- [Team Members](#team-members)
- [Team Task Assignment](#team-task-assignment)
- [Key Features](#key-features)
- [Page Structure](#page-structure)
- [Technical Implementation](#technical-implementation)
- [Project Folder Structure](#project-folder-structure)
- [Getting Started](#getting-started)
- [Development Notes](#development-notes)
- [Future Improvements](#future-improvements)

## Project Overview

Exploring Angkor Wat: A Digital Discovery Guide is a responsive, five-page website focused on Cambodia's most iconic Khmer temple. The project combines educational content with interactive website features to help users learn about Angkor Wat's history, architecture, cultural importance, and visitor experience.

The website is designed as a static web project using semantic HTML5, external CSS, and JavaScript. Each page shares consistent navigation, visual branding, and responsive layouts for desktop, tablet, and mobile screens.

## Course Information

- Course: INFO 250 - Web Development I
- Semester: Summer 2026
- Institution: American University of Phnom Penh
- Instructor: Ms. Buntoun Monyrath
- Submission Date: June 6, 2026

## Team Members

1. Lo Sovannara
2. Heng Munireach
3. Khorn Mengkhin
4. Ratha Raksmey
5. Por Pichpichet

## Team Task Assignment

Each team member is responsible for one main page and the related CSS and JavaScript files for that page. Shared files should be edited carefully because they affect the whole website.

| Team Member | Main Responsibility | Files to Handle |
| --- | --- | --- |
| Khorn Mengkhin | Home page and shared website structure | `index.html`, `js/main.js`, `css/global.css`, `css/layout.css`, `css/components.css`, `css/pages/home.css` |
| Ratha Raksmey | History page | `pages/history.html`, `js/pages/history.js`, `css/pages/history.css` |
| Lo Sovannara | Architecture page | `pages/architecture.html`, `js/pages/architecture.js`, `css/pages/architecture.css` |
| Heng Munireach | Gallery page | `pages/gallery.html`, `js/pages/gallery.js`, `css/pages/gallery.css` |
| Por Pichpichet | Visit planning page | `pages/visit.html`, `js/pages/visit.js`, `css/pages/visit.css` |

### Responsibility Notes

- Khorn Mengkhin should manage the shared files because the home page uses the global layout, navigation, reusable components, and shared JavaScript.
- Each member should mainly edit their own page's HTML file, page-specific CSS file, and page-specific JavaScript file.
- If a teammate needs to change shared files such as `css/global.css`, `css/layout.css`, `css/components.css`, or `js/main.js`, they should coordinate with Khorn Mengkhin first.
- Image, document, font, and video assets can be added by any teammate when needed, but filenames should be clear and organized.

## Key Features

- Five linked pages covering home, history, architecture, gallery, and visit planning
- Responsive design for mobile, tablet, and desktop layouts
- Shared header navigation across all pages
- Semantic HTML structure using elements such as `header`, `nav`, `main`, `section`, `article`, and `footer`
- Page-specific CSS files for organized styling
- JavaScript-powered interactive components planned for timeline tabs, gallery filters, modal previews, route selectors, checklist progress, accordion content, and form validation
- Visual content support through image, video, font, and document asset folders

## Page Structure

| Page | File | Purpose |
| --- | --- | --- |
| Home | `index.html` | Landing page with an introduction to Angkor Wat, hero content, key highlights, and links to the main guide sections. |
| History | `pages/history.html` | Historical timeline page planned to cover Origin, Faith, and Heritage, with milestone data and story cards. |
| Architecture | `pages/architecture.html` | Architecture explorer planned to highlight towers, galleries, bas-reliefs, moat design, materials, and setting. |
| Gallery | `pages/gallery.html` | Photo gallery page planned for filterable categories such as Exterior, Details, and Water, with modal image previews. |
| Visit | `pages/visit.html` | Visitor planning page planned for route selection, checklist progress, etiquette accordion, and a validated contact form. |

## Technical Implementation

### HTML Structure

- Multi-page website with five linked pages
- Proper HTML5 document structure
- Semantic page layout for accessibility and readability
- Image support with descriptive `alt` attributes
- Planned structured data table for the History page
- Planned contact form with labels, fieldsets, validation, and error messaging for the Visit page

### CSS Styling and Layout

- Shared global, layout, and component stylesheets
- Page-specific stylesheets stored in `css/pages/`
- Responsive layouts using Flexbox and CSS Grid
- Consistent typography, spacing, buttons, cards, tables, and forms
- Planned responsive breakpoints for mobile, tablet, and desktop screens
- Planned transitions and keyframe animations for polished user interactions

### JavaScript Interactivity

- Shared navigation behavior in `js/main.js`
- Page-specific scripts stored in `js/pages/`
- Planned tabbed timeline for the History page
- Planned dynamic architecture detail panel
- Planned gallery filtering and modal preview overlay
- Planned route selector, checklist progress tracker, accordion, and form validation for the Visit page

## Project Folder Structure

```text
angkor-wat-digital-guide/
|-- css/
|   |-- components.css
|   |-- global.css
|   |-- layout.css
|   `-- pages/
|       |-- architecture.css
|       |-- gallery.css
|       |-- history.css
|       |-- home.css
|       `-- visit.css
|-- docs/
|-- fonts/
|-- images/
|   |-- Logo.png
|   `-- angkor-wat-greenery.jpg
|-- js/
|   |-- main.js
|   `-- pages/
|       |-- architecture.js
|       |-- gallery.js
|       |-- history.js
|       `-- visit.js
|-- pages/
|   |-- architecture.html
|   |-- gallery.html
|   |-- history.html
|   `-- visit.html
|-- videos/
|-- index.html
`-- README.md
```

## Getting Started

No package installation is required because this is a static HTML, CSS, and JavaScript project.

1. Open the project folder.
2. Open `index.html` in a web browser.
3. Use the navigation menu to move between Home, History, Architecture, Gallery, and Visit pages.

For a smoother local development workflow, open the project in Visual Studio Code and run it with the Live Server extension.

## Development Notes

- `css/global.css` stores base styles and shared visual rules.
- `css/layout.css` stores page layout and structural styles.
- `css/components.css` stores reusable component styles.
- `css/pages/` stores styles that belong to individual pages.
- `js/main.js` stores shared JavaScript used across the website.
- `js/pages/` stores JavaScript for individual pages.
- `images/` stores image assets such as the logo and Angkor Wat photography.
- `docs/`, `fonts/`, and `videos/` are reserved for supporting documents, typography files, and multimedia content.

## Future Improvements

- Add complete final content for all five pages
- Build the tabbed historical timeline on the History page
- Build the interactive architecture explorer on the Architecture page
- Add gallery images, category filters, and modal previews
- Add visit route planning, checklist progress, etiquette accordion, and form validation
- Add a branded footer across all pages
- Add image credits and source documentation
- Test responsiveness and accessibility across common screen sizes
