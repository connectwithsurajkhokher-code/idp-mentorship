# Design System Specification: Editorial Excellence

## 1. Overview & Creative North Star
**Creative North Star: "The Curated Performance"**

This design system moves beyond the utility of standard EdTech platforms to create a high-performance, editorial experience. Inspired by the precision of automotive engineering and the prestige of luxury heritage, we are building a "Digital Atelier" for Indian learners. 

We break the "template" look through **Intentional Asymmetry** and **Tonal Depth**. By avoiding rigid grids and standard containers, we create a sense of movement. Large-scale typography, overlapping imagery, and a "paper-on-glass" layering technique ensure the brand feels both authoritative (Trustworthy) and cutting-edge (Modern).

---

## 2. Colors: The Luxury Palette
The palette is rooted in a warm, sophisticated "Cream" base, accented by a high-octane "Guards Red" and deep, charcoal neutrals.

### Color Tokens
*   **Primary (The Signature):** `#9e0000` (Primary) to `#cc0000` (Primary Container). Use for high-impact CTAs and brand moments.
*   **Background (The Canvas):** `#faf9f6` (Surface). A warm white that reduces eye strain and feels more premium than sterile hex-white.
*   **Secondary/Tertiary (The Mechanics):** `#5f5e5e` and `#4c4c4c`. Used for supportive elements and sophisticated text.

### The "No-Line" Rule
**Explicit Instruction:** 1px solid borders are prohibited for sectioning. 
Structure must be defined through:
1.  **Background Color Shifts:** A `surface-container-low` (`#f4f3f1`) section sitting against a `surface` (`#faf9f6`) background.
2.  **Negative Space:** Using the `16` (4rem) or `20` (5rem) spacing tokens to create mental boundaries.

### Glass & Gradient Strategy
To avoid a flat "out-of-the-box" feel, use **Glassmorphism** for floating navigation and overlay cards. 
*   **Token:** `surface-container-lowest` (`#ffffff`) at 80% opacity with a `20px` backdrop-blur.
*   **Signature Gradient:** For Hero CTAs, use a linear gradient from `primary` (`#9e0000`) to `primary-container` (`#cc0000`) at a 135-degree angle to add "soul" and dimension.

---

## 3. Typography: The Editorial Voice
We utilize **Montserrat** to bridge the gap between Porsche-inspired sleekness and modern educational accessibility.

*   **Display (The Statement):** `display-lg` (3.5rem) / Montserrat Bold. Use for hero headers with tight letter-spacing (-0.02em). This is your "billboard" voice.
*   **Headline (The Authority):** `headline-lg` (2rem) / Montserrat Bold. Used for section titles.
*   **Title (The Guide):** `title-lg` (1.375rem) / Montserrat Medium. For card titles and prominent sub-headers.
*   **Body (The Content):** `body-lg` (1rem) / Montserrat Regular. Optimized for readability in course descriptions and long-form content.
*   **Label (The Metadata):** `label-md` (0.75rem) / Inter. A secondary font used for utility text (durations, tags, prices) to provide a technical contrast to the editorial Montserrat.

---

## 4. Elevation & Depth: Tonal Layering
We do not use "shadows" in the traditional sense; we use **Tonal Stacking**.

### The Layering Principle
Treat the UI as physical sheets of fine paper. 
*   **Base Layer:** `surface` (#faf9f6)
*   **Section Layer:** `surface-container-low` (#f4f3f1)
*   **Card Layer:** `surface-container-lowest` (#ffffff)
This hierarchy creates a natural "lift" that feels integrated, not "pasted on."

### Ambient Shadows & Ghost Borders
*   **Ambient Shadows:** For floating elements (Modals/Dropdowns), use a 32px blur, 0px offset, at 4% opacity using the `on-surface` color. It should be felt, not seen.
*   **Ghost Borders:** If a boundary is required for accessibility, use the `outline-variant` (`#e8bdb6`) at 15% opacity. Never use 100% opaque lines.

---

## 5. Components: Precision Elements

### Buttons
*   **Primary:** `primary` background, `on-primary` text. `0.25rem` (sm) corner radius. Use the signature gradient on hover.
*   **Secondary:** `surface` background with a `Ghost Border`.
*   **Tertiary:** No background. Bold `primary` text with a 2px underline that expands on hover.

### Cards & Course Tiles
*   **Constraint:** Zero borders. Zero divider lines.
*   **Structure:** Use `surface-container-highest` (`#e3e2e0`) for image placeholders. Typography should have generous padding (`spacing-8`).
*   **Interaction:** On hover, the card should transition from `surface-container-low` to `surface-container-lowest` with an ambient shadow.

### Input Fields
*   **Style:** Minimalist. Underline-only or subtle `surface-variant` fills.
*   **Active State:** The label floats and transforms to `primary` color; the underline expands from the center.

### Specialized Component: The "Performance Metric" Chip
For an EdTech bootcamp, use high-contrast chips for "Live" or "Trending" status. 
*   **Token:** `primary` background, `label-sm` text, `full` (9999px) roundedness.

---

## 6. Do’s and Don’ts

### Do:
*   **Use Oversized Imagery:** Use high-quality, high-contrast photography of people and technology, inspired by Porsche’s lifestyle shots.
*   **Embrace Asymmetry:** Offset your text columns from your image columns to create a sophisticated, editorial layout.
*   **Respect the "Breath":** Use `spacing-20` (5rem) between major sections. Luxury is defined by the space you *don't* fill.

### Don’t:
*   **Don't use "Full Black":** Use `on-surface` (`#1a1c1a`) for text; it is softer and more premium.
*   **Don't use Rounded Corners > 8px:** Stay within `DEFAULT` (4px) to `lg` (8px). Large "bubble" corners diminish the professional, high-end aesthetic.
*   **Don't use Dividers:** If you feel the need for a line, increase the vertical whitespace instead. Let the typography and color shifts do the work.