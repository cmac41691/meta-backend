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
