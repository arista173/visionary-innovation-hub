# Visionary Innovation Hub - Website

A modern, interactive multi-page website for a fictional innovation organization based in Hong Kong. Built with plain HTML, CSS, and JavaScript — no build tools or dependencies required.

## Overview

Visionary Innovation Hub (VIH) is presented as a state-of-the-art research and development centre in Kowloon, Hong Kong. The site showcases the hub's zones, companies, internship opportunities, and visitor booking system through a fully responsive, JavaScript-enhanced experience.

## Quick Start

1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. Use the navigation menu to explore all pages

> No installation, server, or build step is required.
> Note: the **Visit** booking and **Information** video features load external resources from `personal.cs.cityu.edu.hk`, so an internet connection is needed for those to work.

## File Structure

```text
visionary-innovation-hub/
├── index.html
│
├── HTML/
│   ├── aboutpage.html
│   ├── applypage.html
│   ├── contactpage.html
│   ├── designpage.html
│   ├── informationpage.html
│   └── visitpage.html
│
├── CSS/
│   ├── header_footer.css   # Shared header, navigation, and footer styles
│   ├── index.css           # Home page
│   ├── about.css           # About page
│   ├── apply.css           # Apply page
│   ├── contact.css         # Contact page
│   ├── design.css          # Design page
│   ├── program.css         # Information page
│   ├── visit.css           # Visit page
│   └── printApply.css      # Print-only stylesheet for the Apply page
│
├── scripts/
│   ├── apply.js            # Internship ranking logic
│   ├── visit.js            # Booking validation and reservation
│   └── information.js      # Rotating text and video cycling
│
└── images/                 # Logos, location map, company and UI images
```

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Welcome introduction, hub information, address, and location map |
| About | `HTML/aboutpage.html` | Organization background with a highlights statistics table |
| Apply | `HTML/applypage.html` | Interactive internship ranking across three zones |
| Visit | `HTML/visitpage.html` | Open-day booking form with availability checking |
| Information | `HTML/informationpage.html` | Rotating promotional text and cycling background videos |
| Contact | `HTML/contactpage.html` | Contact details in a structured table |
| Design | `HTML/designpage.html` | Documentation of the CSS and JavaScript techniques used |

## Features

### Apply Page — Internship Ranking
- Browse 12 companies grouped into **Technology**, **Innovation**, and **Ecology** zones via clickable tabs
- Assign each company a rank from 1 to 10
- Validation prevents duplicate companies and duplicate ranks
- Submit checks for gaps in the ranking before confirming the application
- Clear button resets all selections

### Visit Page — Booking System
- Date, time-slot, and number-of-visitors form
- Client-side validation for empty and invalid input
- Availability checked through the `reserve()` function

### Information Page — Dynamic Content
- Promotional messages rotate automatically every 3 seconds
- Background videos cycle between two sources when one ends

### Design & Responsiveness
- Fully responsive layout with media queries across all pages
- Consistent animated header, navigation, and footer
- Print-friendly Apply page via a dedicated print stylesheet
- CSS3 gradients, animations, rounded corners, and table hover effects

## Tech Stack

- **HTML5** — semantic structure and forms
- **CSS3** — responsive design, gradients, keyframe animations
- **JavaScript (ES6)** — DOM manipulation, event handling, validation, timers

## Browser Support

Works in all modern browsers (Chrome, Edge, Firefox, Safari). JavaScript must be enabled for the interactive pages.