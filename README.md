# Form Input Wave Animation

An interactive landing page interface featuring a custom text-wave animation on input field labels. This project demonstrates how to create clean, responsive micro-interactions using native HTML, CSS transitions, and JavaScript DOM manipulation without relying on external UI frameworks.

## Core Features
- Staggered Wave Effect: Input placeholder labels automatically split and cascade upward in a wave pattern when fields are focused or active.
- Fluid Micro-Interactions: Utilizes fine-tuned cubic-bezier CSS timing functions for smooth animation feedback.
- Dynamic DOM Manipulation: Uses functional JavaScript methods to inject individual span architectures dynamically, keeping the core HTML layout clean.
- Responsive Design: A centered form container box built using CSS Flexbox layout mechanics for cross-device support.

## Technical Implementations
- Advanced CSS Selectors: Combines the `:focus` and `:valid` pseudo-classes with adjacent sibling combinators (`+ label`) to track text input states.
- Inline Styling Computations: Generates progressive `transition-delay` modifiers mathematically through JavaScript array indices.
- String Restructuring: Implements string `.split()`, `.map()`, and `.join()` methods to process static text node structures programmatically.

## Built With
- HTML5 (Semantic Forms)
- CSS3 (Flexbox Layouts & Staggered Transitions)
- JavaScript (ES6+ Array Methods & DOM Injection)

## Project Structure
- index.html: Semantic markup for the login layout window.
- style.css: Absolute positioning, timing curves, and styling properties.
- script.js: Logical breakdown and character wrapping scripts.

