---
Project: Advanced CSS — Techium Project
Description

This project builds upon the Advanced HTML Techium project by adding advanced CSS styling. The goal is to style the Techium agency webpage using modern CSS techniques, including custom properties (variables), transitions, transforms, animations, and a float-based grid system — targeting Chrome 78.x compliance.

Learning Objectives

By completing this project, you should be able to:

Explain CSS selectors, properties, and values

Understand block vs inline styling

Ensure consistency across browsers using CSS resets

Use CSS variables (custom properties) efficiently

Know the differences between inline, embedded, and external CSS

Create layouts using float-based grid systems

Use icon webfonts and SVG icons correctly

Apply pseudo-classes (:hover) and pseudo-elements (::before, ::after)

Create background gradients

Animate elements in CSS

Transform elements in 2D and 3D

Use vendor prefixes when needed

CSS Architecture
CSS Variables (Custom Properties)

All design tokens are declared in :root:

Variable	Purpose
--color-primary	Brand red #d73953
--color-black / --color-white	Base colors
--font-family-base	Body font — Open Sans
--font-family-title	Heading font — Raleway
--transition-duration	Global transition timing .3s
--transition-cubic-bezier	Custom easing curve
Dark Theme

Sections with data-section-theme="dark" override text and background colors via CSS variable re-declaration. No extra classes are needed.

Grid System

Float-based layout system:

.row — clearfix container

.col-1-3 — one-third width (33.33%)

.col-1-2 — one-half width (50%)

Key Components
Component	Description
.card-services	Service cards with hover color change
.card-work	Portfolio cards with image zoom and overlay on hover
.card-testimonial	Testimonial cards with decorative quote mark
.card-blog	Blog/news article cards
.button	CTA button with border and hover background fill
.nav	Float-based navigation with animated underline on hover
Transitions & Transforms (Task 32 Highlights)

Navigation links — underline slides in smoothly on hover (::before pseudo-element)

Buttons — smooth background and text color transition on hover

Work cards — image scales up (scale(1.2)) and card container scales down (scale(0.95)) on hover, revealing a dark overlay with the title

Project Requirements

Allowed editors: vi, vim, emacs, VSCode, Atom

All files tested on Chrome 78.x

Each file ends with a newline

Each file starts with a comment describing the task

A README.md is mandatory at the project root

Code should be W3C compliant (Validator
)

Resources

CSS Reference — A visual guide

Can I use… — CSS/HTML support

CSS Properties | HTML Dog

Box Sizing Guide

CSS Specificity Guide

CSS Specificity Calculator

Play with CSS Selectors

Author

Sara Rebati

Student at Holberton School

Track: Holberton School web front-end

GitHub: SaraEstelle

Project: Advanced CSS
