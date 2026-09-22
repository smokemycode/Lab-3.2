## Practicing Implementation with Frontend Mentor
This repository contains my submission for the Figma Design Implementation lab, where I practiced translating Figma design files into polished, responsive, and accessible web components using Frontend Mentor challenges (QR Code Component and Blog Preview Card). It demonstrates my ability to interpret design specs, write clean HTML and CSS, and build professional components suitable for a development portfolio.

## 📋 Project Overview
Semantic HTML Structure
Used landmark HTML elements (<header>, <nav>, <main>, <section>, <article>, <footer>) instead of generic <div> containers to create meaningful document structure.

Implemented a logical heading hierarchy, starting with <h1> in the hero section, <h2> for major sections, and <h3> for individual cards and service items.

Structure follows accessibility standards and mirrors the layout organization from the Figma design files.

## 🎨 Layout & Responsive Design
Accuracy to Design
Matched the Figma design precisely — alignment, spacing, font sizes, and element dimensions follow the provided style guide.

Colors, typography, and component sizing all reflect the original design specifications.

Flexbox Implementation
Header & Navigation: Built with Flexbox to align the logo and navigation links. On desktop, items sit inline with space between; on smaller screens (under 600px), the layout gracefully stacks into a centered column.

CSS Grid Implementation
Services Section: Uses CSS Grid with adaptive column layouts:

Desktop (1025px+): 3-column layout (repeat(3, 1fr))

Tablet (601px–1024px): 2-column layout for better readability

Mobile (≤600px): Single-column layout for easy scrolling on phones

CSS Styling
CSS is well-organized and matches the style guide exactly — colors, fonts, and sizes align with the Figma specifications.

Custom properties and media queries keep the styling consistent across all breakpoints.

## ♿ Accessibility Features
Keyboard Navigation & Interactive Elements
Hover and focus states are implemented as specified in the design, with smooth transitions and responsive feedback.

Keyboard focus management ensures all interactive elements are reachable and clearly indicated.

Color Contrast
All text, buttons, and background combinations have been checked against WCAG 2.1 AA standards using contrast checking tools to ensure readability.

Decorative Elements
Service icons are purely decorative and include alt="" to prevent screen readers from announcing them unnecessarily.

## 🛠️ Technologies Used
HTML — Semantic markup and accessibility

CSS — Flexbox, Grid, media queries, and custom properties

Figma — Design interpretation and style guide adherence

Frontend Mentor — Challenge specifications and assets

## ✅ Assessment Criteria Met
☑ Matches design precisely — pixel-perfect alignment, spacing, and sizing
☑ CSS well-organized and matches style guide (colors, fonts, sizes)
☑ Hover and focus states implemented with smooth transitions
☑ Clean, semantic HTML structure following accessibility standards
☑ All challenge requirements met with full interactivity
☑ Responsive design using Flexbox and CSS Grid
☑ Media queries for multiple screen sizes
☑ Sufficient color contrast ratios
☑ Decorative vs. meaningful image handling

## REFLECTION
1. How did using Figma designs as references affect your coding process?
   I did not use Figma in this project. With level of difficulty of the projects I wanted to see if I would be able to code it just based of the pictures provided.
2. What challenges did you encounter when aligning your code with the design specifications?
   Most of my problems came from making sure that each element was in the place that it needed to be by using flexbox. I was very tempted to use padding and margin despite the rubric provided. But I was able to work          through those problems and get it done using flexbox.
3. How can the feedback and community resources on Frontend Mentor help you improve as a developer?
   Using the feedback and resources provided will be able to give me more insight onto my work and how to complete it out side of my fellow peers in my cohort and accountablility partners. By using the feedback, I can and will learn new ways to code.
