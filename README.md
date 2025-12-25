# Tailwind Color Palette Generator 

A lightweight web tool that generates a full **Tailwind-style color scale (50–900)** from a single base color.  
Built using **HTML, JavaScript, and Tailwind CSS CDN**, with perceptually uniform color interpolation.

---

## Features

-  Pick any base color using a color picker
-  Automatically generates Tailwind steps: `50 → 900`
-  Live preview of background + text contrast
-  Click any color to copy its HEX value
-  Copy-ready Tailwind utility class preview
-  Uses **OKLCH color space** for smooth, perceptual color scaling

---

##  Tech Stack

- **HTML5**
- **Tailwind CSS (CDN)**
- **Vanilla JavaScript**
- **OKLCH color interpolation**

---

##  How It Works

1. User selects a base color
2. Color is converted from **HEX → OKLCH**
3. Lightness is interpolated across Tailwind steps (50–900)
4. Each step is converted back to HEX
5. Palette updates instantly with copy support

---



