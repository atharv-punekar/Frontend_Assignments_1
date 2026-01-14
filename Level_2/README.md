# Assignment 2 – Pricing Card Grid


## Task 

Create a responsive pricing grid with:
- Plan titles (e.g., Free, Pro, Enterprise)
- Features
- Highlighted "Recommended" plan
- CTA buttons (e.g., “Get Started”)

---

## Focus Areas in Design:

- Reusable card styles
- Equal height columns
- Emphasis on selected pricing tier
- Clear CTA buttons
  
---

## What Developers Will Learn

- CSS Grid or Flexbox for multi-column layout
- Card hover/active states

---

## Technologies Used

- **HTML5** – Semantic structure of the pricing layout  
- **CSS3** – Styling, layout, and responsiveness  
- **CSS Grid** – Responsive multi-column pricing grid  
- **Flexbox** – Equal height cards and internal alignment  

---

## Steps Followed to Build the Project

### 1. HTML Structure
- Created a main page wrapper for vertical and horizontal alignment.
- Added a header section for the page title and description.
- Used a pricing grid container to hold all pricing cards.
- Wrapped each pricing plan inside an `<article>` element for semantic clarity.

---

### 2. Multi-Column Layout Using CSS Grid
- Implemented CSS Grid to create equal-width columns.
- Used `auto-fit` and `minmax()` for responsiveness across screen sizes.
- Ensured smooth stacking of cards on smaller devices.

---

### 3. Reusable Pricing Card Component
- Created a shared `.pricing-card` class for all plans.
- Used Flexbox inside each card to:
  - Stack content vertically
  - Push CTA buttons to the bottom
- Maintained equal height across all cards.

---

### 4. Highlighting the Recommended Plan
- Added a `.recommended` class to visually emphasize the Pro plan.
- Applied:
  - Different background color
  - Stronger box shadow
  - Slight upward transform
- Added a “Recommended” badge using absolute positioning.

---

### 5. Feature List Styling
- Used unordered lists to display plan features.
- Added subtle separators for better readability.
- Maintained consistent spacing across all cards.

---

### 6. CTA Buttons
- Created reusable button styles:
  - Primary button for the recommended plan
  - Outline button for other plans
- Added hover effects to improve user interaction.

---

### 7. Hover and Interaction States
- Added hover animations to pricing cards:
  - Slight upward movement
  - Enhanced shadow
  - Border highlight
- Added smooth transitions for CTA buttons.

---

### 8. Responsive Design
- Used media queries to adjust padding and font sizes.
- Ensured pricing cards stack neatly on mobile devices.
- Maintained readability and usability on all screen sizes.

---

## Key Concepts Used

- Semantic HTML structure
- CSS Grid for responsive layouts
- Flexbox for internal card alignment
- Reusable UI components
- Hover and active state design
- Visual hierarchy and emphasis
- Responsive design using media queries

---

## Assignment Outcome

- Fully responsive pricing card grid
- Equal height pricing cards
- Clear emphasis on the recommended plan
- Consistent styling and spacing
- Clean, modern, and accessible UI design

---

## Author

**Atharv Punekar**  

---
