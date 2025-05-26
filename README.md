# Admin Dashboard (Grid Practice Project)

This project is a frontend layout built as part of a CSS Grid practice exercise. It is not connected to a backend and is intended primarily for educational purposes.

## Overview

The layout simulates a basic admin dashboard. It includes:

- A header with logo and account access
- Sidebar navigation with multiple sections
- A main grid of project cards
- A right-hand sidebar with announcements and trending content

## Key Skills Demonstrated

### CSS Grid Layout
The project makes extensive use of CSS Grid to organize major layout areas:
- `#grid-container`: A 3-column grid layout for project cards
- `#side` and `#sidenav`: Grid-based vertical stacking of sidebar sections

### Flexbox for Alignment
Flexbox is used alongside Grid to handle alignment within components, such as:
- Horizontal spacing in the header
- Vertical alignment of navigation lists and buttons

### Custom Styling and Fonts
- Uses `@font-face` to load and apply custom fonts (`Poppins Regular` and `Poppins Bold`)
- Cards and buttons styled with consistent padding, borders, and hover effects
- Background images, color themes, and rounded borders for visual appeal

### Reusable Components
Elements like `.nav-tile`, `.project`, and `.side-tile` are structured for consistency and reuse, helping maintain a clean, modular design.

### Basic Interactivity
- Hover scaling effect on interactive tiles
- Blurred background hover effect on the "Create +" button

## Purpose

This project was created as part of [The Odin Project](https://www.theodinproject.com/) curriculum to gain hands-on experience with modern CSS layout techniques, particularly CSS Grid.