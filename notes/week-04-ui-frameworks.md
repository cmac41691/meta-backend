# Week 04 – UI Frameworks & Bootstrap

## Topics
- UI Libraries
- Responsive Design
- Bootstrap basics
- Grid system
- Components

## Goal
Understand how frontend frameworks help present backend data

## Questions
- How does Bootstrap fit into backend flow?
- What problem does grid solve?


## Bootstrap basics

Bootstrap is a CSS framework that provides prebuilt styles and components  
Helps build UI faster without writing custom CSS

Backend connection:
Server returns HTML → Bootstrap classes apply styling

---

## Getting started with Bootstrap

Bootstrap can be added using a CDN link in HTML

Once added, you can use predefined classes like:
- btn
- container
- row
- col

---

## Using Bootstrap styles

Styles are applied using class attributes

Example:
<button class="btn btn-primary">Click</button>

No CSS needed → Bootstrap handles styling

---

## Bootstrap Grid System

Layout system based on 12 columns

Structure:
- container → row → columns

Example:
<div class="row">
  <div class="col-6">Left</div>
  <div class="col-6">Right</div>
</div>

Grid is responsive:
- adjusts layout based on screen size

---

## Key Insight

Bootstrap separates:
- Structure (HTML)
- Styling (Bootstrap classes)

This allows backend systems to send clean HTML  
and rely on frameworks for presentation


## 2026-03-27 (Friday)
(Self Review + Bootstrap Components intro)
# TLDR Notes
- Reviewed Bootstrap grid concepts (container → row → column)
- Reinforced responsive behavior (col-12, col-lg-6)
- Introduced Bootstrap components (buttons, cards, basic UI elements)
- Learned that Bootstrap provides prebuilt styled elements to speed up development


## 2026-03-28

### Completed

- ✅ Working with Bootstrap components (Lab)
- ✅ Self review: Working with Bootstrap components (Practice Assignment – 100%)
- ✅ Using Bootstrap documentation (Reading)
- ✅ Other CSS frameworks and libraries (Reading)

---

### Key Takeaways

- Bootstrap provides prebuilt components using classes (e.g. `alert`, `badge`, `btn`)
- Grid system uses:
  - `row` → container
  - `col-*` → layout columns
- Components added in lab:
  - Alert → for notifications
  - Badge → for highlighting "New"
  - Button → for user actions
- Importance of placing elements correctly within the grid structure

---

### Notes

- Practiced translating instructions into code instead of copying
- Used Emmet to speed up HTML structure
- Improved understanding of Bootstrap layout vs custom CSS




## 2026-03-29

### Completed
- React intro topics + case study

### Key Takeaways
- Static vs dynamic content difference
- SPA loads once and updates dynamically
- React helps manage complex UI updates

### Notes
- Focused on understanding concepts instead of memorizing

## 2026-03-30

### Completed
- How React works
- Virtual DOM
- Component hierarchy
- React + libraries

### Key Takeaways
- React uses components to structure UI
- Virtual DOM improves performance by minimizing real DOM updates
- Component hierarchy organizes UI into reusable pieces
- React focuses on UI, not full application logic

### Notes
- Focused on understanding how React manages updates
- Saving knowledge check for next session