# Website-Landing-Page-sederhana-Day-12
# Modern Landing Page with Animated Particle Background

## Description
This is a modern and visually appealing landing page built with HTML, CSS, and JavaScript. The page features a responsive design, smooth animations, and an interactive particle background in the hero section. It uses Tailwind CSS for styling and includes a navigation bar, a hero section with a call-to-action (CTA) button, and a simple footer.

## Features
- **Responsive Design**: Adapts seamlessly to all screen sizes using Tailwind CSS.
- **Animated Particle Background**: A dynamic canvas-based particle animation in the hero section with connecting lines for a futuristic effect.
- **Smooth Scrolling**: Navigation links provide smooth scrolling to sections.
- **Interactive CTA Button**: Features hover scaling, pulse animation on click, and a popup alert.
- **Modern Gradient Styling**: Hero section has a fallback gradient for browsers without canvas support.
- **Custom Animations**: Fade-in and slide-up effects for hero section text.

## Project Structure
- `index.html`: Main HTML file containing the page structure, including navigation, hero section with canvas, and footer.
- `styles.css`: Custom CSS for animations (fadeIn, slideUp) and additional styling for the particle canvas and CTA button.
- `script.js`: JavaScript for smooth scrolling, CTA button interaction, and particle animation logic.

## How to Run
1. **Clone or Download**: Download the project files (`index.html`, `styles.css`, `script.js`) to a single folder.
2. **Ensure Internet Connection**: The page uses Tailwind CSS via CDN, requiring an internet connection.
3. **Open in Browser**: Open `index.html` in a modern web browser (e.g., Chrome, Firefox, Edge).
4. **View the Page**: The landing page will load with the animated particle background in the hero section.

## Dependencies
- **Tailwind CSS**: Loaded via CDN (`https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css`).
- No additional libraries are required, as the particle animation is built using vanilla JavaScript and HTML5 Canvas.

## Customization
- **Particle Animation**: Adjust the `numberOfParticles`, particle size, speed, or connection distance in `script.js`.
- **Styling**: Modify colors, gradients, or animations in `styles.css` or update Tailwind classes in `index.html`.
- **Content**: Update text, links, or add new sections in `index.html`.

## Notes
- Ensure a stable internet connection to load Tailwind CSS.
- The particle animation is optimized for performance but may consume more resources on low-end devices. Reduce `numberOfParticles` in `script.js` if needed.
- Tested on modern browsers as of May 2025.

## Credits
- Built with ❤️ by MHafisAfrizal.
- Inspired by modern web design trends and particle animation techniques.
