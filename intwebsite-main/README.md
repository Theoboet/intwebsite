# Interactive Website - New Index Page Redesign

## Overview
This README documents the process, design decisions, and technical steps taken to redesign the `index.html` page for the Interactive website.

---

## 1. Design Changes
- **Background:** Changed to dark gray (`#1e1e1e`).
- **Profile Cards (Carte Profilo):** Added as a visual motif in the background, arranged in vertical columns.
- **Text Colors:** Main text is now white. Important text is highlighted in yellow (`#FFDD1a`).
- **Logo & Photos:** Updated with new assets, replacing the old files in the `assets/` folder (using the same filenames).
- **Modern Layout:** Maintained the original structure but refreshed the look for a more vibrant, engaging, and modern feel.

---

## 2. Asset Management
- All new images, icons, and the logo were placed in the `assets/` folder.
- Old assets were replaced with new ones using the same filenames to ensure seamless updates.

---

## 3. Motion & Animation Effects
- **Profile Card Columns:**
  - Cards are arranged in vertical columns.
  - Each column moves slowly (one up, one down, alternating direction) using CSS animations or JavaScript.
- **Phone Images:**
  - Phone images gently zoom in when hovered or when near the center of the viewport.
  - Zoom out when not hovered/centered.
- **Section Transitions:**
  - When scrolling from one phone section to another, a subtle dissolve (fade) transition is applied as each new section appears.

---

## 4. Spacing Specifications
- **Profile Cards:**
  - 24px vertical spacing between cards in the same column.
  - 24px horizontal spacing between columns.

---

## 5. How to Update or Extend
1. **To change assets:**
   - Replace files in the `assets/` folder with new images, keeping the same filenames.
2. **To adjust spacing or animation:**
   - Edit the relevant CSS or JavaScript in `style.css` or the associated script files.
3. **To update text or layout:**
   - Edit the content in `index.html`.

---

## 6. Additional Notes
- Screenshots of the new design are available for reference.
- For further changes, specify exact colors, spacing, and animation behavior in prompts or documentation for clarity.

---

**For questions or further customization, please refer to the code comments or contact the project maintainer.** 