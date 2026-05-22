# CBT HTML & CSS Basic Assignment 1

This repository contains the first basic assignment under the Competency-Based Training (CBT) program. The primary objective of this project is to implement core CSS Selectors and thoroughly understand how different **CSS Display Properties** control the layout and positioning of elements on a webpage.

##  Project Features
- **File Structure:** Clean separation of concerns with `index.html` and `style.css`.
- **CSS Selectors Used:** Universal (`*`), Element (`body`), ID (`#main-title`), and Class (`.box`, `.para`).
- **Layout Behavior:** Live demonstration of the 4 essential display values with a modern, professional card design.

---

##  Deep Dive: How CSS Display Properties Work

This assignment demonstrates the practical behavior of four major display states applied to individual boxes. Below is an explanation of how each style mechanics works:

### 1. Block Display (`display: block;`)
- **How it works:** A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).
- **Key Characteristics:**
  - It respects both `width` and `height` properties.
  - It naturally stacks vertically, one after another.
  - In this project, `Box 1` behaves as a block element, centered perfectly using `margin: auto`.

### 2. Inline Display (`display: inline;`)
- **How it works:** An inline element does not start on a new line. It only takes up as much width as its content requires and allows other elements to sit right next to it.
- **Key Characteristics:**
  - **Limitation:** Top and bottom `margin` and `padding` are not fully respected, and setting a specific `width` or `height` has **no effect**.
  - In this project, `Box 2` shows this behavior—it wraps strictly around its text content and flows with the line.

### 3. Inline-Block Display (`display: inline-block;`)
- **How it works:** This is a hybrid state that offers the best of both worlds. It places elements side-by-side on the same line (like inline) but allows them to retain block-level layout controls.
- **Key Characteristics:**
  - It strictly respects custom `width`, `height`, `padding`, and `margin`.
  - Ideal for creating grid-like cards, navigation links, or custom buttons.
  - `Box 3` utilizes this property to maintain a defined width of `180px` while sitting comfortably alongside other elements.

### 4. Hidden Display (`display: none;`)
- **How it works:** This property completely removes the element from the document structure. It is not just invisible; it behaves as if the element does not exist in the HTML structure at all.
- **Key Characteristics:**
  - It takes up **zero space** on the layout.
  - Commonly used in modern web development for interactive toggles, popups, and responsive mobile menus.
  - `Box 4` has this property applied, effectively hiding it from the final live viewport.

---

## 🚀 Technologies Used
- **HTML5** - Semantic page structuring.
- **CSS3** - Modern UI design including box-shadows, border-radius, and smooth hover micro-interactions.
