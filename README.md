# Blade Slinger Landscaping — Tailwind CSS Redesign

This project is a full redesign of the Blade Slinger Landscaping website, originally built with **Bootstrap 5** and now fully migrated to **Tailwind CSS**. The goal of this rebuild was to modernize the styling system, simplify customization, and improve accessibility — especially for users with color‑vision disabilities.

---

## Why Tailwind CSS?

Tailwind CSS was chosen to replace Bootstrap for several key reasons:

### **1. Utility‑First Workflow**
Tailwind provides low‑level utility classes (e.g., `flex`, `p-6`, `text-black`) that allow precise control over spacing, layout, and styling directly in the HTML.  
This eliminates the need to override Bootstrap’s pre‑styled components and reduces CSS bloat.

### **2. Faster Development**
Tailwind’s inline utilities make it easy to:

- Adjust spacing and layout on the fly  
- Apply responsive breakpoints  
- Customize colors and typography  
- Maintain consistent design across all pages  

This results in a cleaner, more maintainable codebase.

### **3. No More Fighting Against Bootstrap Defaults**
Bootstrap often forces developers to override:

- Button styles  
- Card styles  
- Typography  
- Spacing  
- Grid behavior  

Tailwind avoids this by giving full control from the start.

---

## Accessible, Color‑Blind‑Friendly Design

A major focus of this redesign was **accessibility**, especially for users with visual impairments or color‑vision deficiencies.

### **Primary Color: Blade Slinger Green**
A bright, saturated green (`#00A651`) was selected because:

- It maintains strong contrast with both white and black text  
- It remains distinguishable for most types of color blindness  
- It aligns with the landscaping brand identity  

### **Text Colors**
- **Black text** is used on green backgrounds for maximum readability  
- **White text** is used only on dark backgrounds (e.g., black footer)  
- All body text in main content sections was switched from white → black to improve contrast ratios

### **WCAG Contrast Considerations**
The redesign follows WCAG recommendations:

- Minimum contrast ratio of **4.5:1** for normal text  
- Avoiding green‑on‑green or low‑contrast combinations  
- Ensuring buttons and links remain visible under all color‑blindness simulations  

This makes the site more accessible for users with:

- Deuteranopia  
- Protanopia  
- Tritanopia  
- Low vision  
- Brightness sensitivity  

---

## 🧱 Project Structure




