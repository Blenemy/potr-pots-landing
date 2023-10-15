# Base layout template with Gulp, SCSS and Stylelint

# POTR POTS Landing Page

POTR POTS is a streamlined single-page landing crafted with a keen attention to detail. It serves as a gateway to showcase the elegant simplicity of POTR POTS offerings.

# Key Technologies & Features

- **JavaScript (ES6)**
- **HTML**: Semantically structured and cleanly laid out.
- **SCSS with BEM Methodology**: Styles are written using the SCSS preprocessor, with the BEM naming convention to ensure readability and maintainability.
- **Slider**: A custom-built slider for displaying content in a carousel.
- **Pop-ups**: Interactive pop-ups that enhance user engagement.
- **Form Validation**: Real-time form validation ensures data integrity before submission.
- **Menu Toggling**: Dynamic menu behavior based on URL hash changes.
- **Dynamic Adaptive** Display: Leveraging an open-source library, the landing page adjusts seamlessly across various displays.
- **Intersection Observer**: This feature enables on-scroll animations, enhancing the visual experience as users navigate the site.

# Viewing Recommendations

The landing page is fully responsive and well-adapted for all types of devices, ensuring a seamless browsing experience.

## IntersectionObserver Module

- Uses the IntersectionObserver API to implement scroll-triggered animations.
- Elements with the class `animate-on-scroll` will animate when they enter the viewport.
- The `rootMargin` option in the observer ensures the animations trigger a bit before the element is fully in view.

## Additional Info

- **Styles:** Styled using SCSS (referenced as `main.scss`).
- **Scripts:** The site uses custom scripts (`main.js` and `dynamicAdapt.js`).
