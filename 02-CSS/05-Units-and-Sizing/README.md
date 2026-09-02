# CSS Module 05 — Units & Sizing

A practical CSS learning module focused on understanding and applying CSS units and sizing functions to create flexible, responsive layouts.

This module is part of my **Web Development From Scratch** learning journey.

---

## Topics Covered

### CSS Units

- `px` — Fixed pixel-based sizing
- `%` — Relative sizing based on the parent/container
- `em` — Relative to the current element's font size
- `rem` — Relative to the root (`html`) font size
- `vw` — Relative to the viewport width
- `vh` — Relative to the viewport height
- `vmin` — Relative to the smaller viewport dimension
- `vmax` — Relative to the larger viewport dimension

### CSS Sizing Functions

- `min()` — Uses the smallest calculated value
- `max()` — Uses the largest calculated value
- `clamp()` — Creates a flexible value with a minimum and maximum limit

---

## Learning Objectives

By completing this module, I learned how to:

- Choose appropriate CSS units for different situations
- Create flexible widths using `%`
- Use `rem` for scalable typography and spacing
- Understand the difference between `em` and `rem`
- Size elements relative to the viewport using `vw` and `vh`
- Use `vmin` and `vmax` for viewport-based sizing
- Create responsive constraints with `min()` and `max()`
- Create fluid typography with `clamp()`
- Combine different CSS units to build responsive layouts

---

## Practical Project — Aura Coffee

The concepts from this module were implemented in a practical coffee website called **Aura Coffee**.

The project uses CSS units and sizing functions throughout different sections of the page.

### Implemented Examples

- `%` for responsive container widths
- `px` for borders
- `rem` for typography and spacing
- `em` for component-level button padding
- `vw` inside responsive typography
- `vh` for hero section height
- `vmin` for image sizing
- `vmax` for viewport-based sizing
- `min()` for responsive maximum widths
- `max()` for minimum font sizing
- `clamp()` for fluid heading sizes

---

## Project Structure

```text
Module-05-Units-and-Sizing/
│
├── index.html
├── style.css
├── images/
│   ├── coffee.jpg
│   └── our-story.jpg
└── README.md
```

## Responsive CSS

This module introduced the foundation for responsive sizing without relying entirely on fixed values.

For example:

`width: min(90%, 1200px);`

This allows an element to remain responsive while preventing it from becoming excessively wide.

Fluid typography:

`font-size: clamp(2rem, 5vw, 4rem);`

This allows the font size to grow and shrink with the viewport while maintaining minimum and maximum limits.

## Technologies Used
* HTML5
* CSS3
* VS Code

## Learning Status

### Module 05 — Completed

The goal of this module was not just to memorize CSS units, but to understand when and why each unit or sizing function should be used in real layouts.

## Part of My Web Development Journey

This module is part of my ongoing:

### Web Development From Scratch

learning journey, where I am building my web development skills step-by-step through concepts, exercises, and practical projects.