# Scroll Animation Project

## Overview
This project demonstrates a simple scroll animation effect. As the user scrolls down the page, the boxes smoothly animate into view from either the left or right side. It uses basic HTML, CSS, and JavaScript for the animation.

## Features
- **Smooth Scroll Animation**: Boxes appear with a slide-in effect as the user scrolls down the page.
- **Responsive Design**: The layout adjusts to different screen sizes using relative units.
- **Simple and Lightweight**: No external JavaScript libraries are needed, and the CSS is minimal.

## Technologies Used
- **HTML5**: The structure of the page.
- **CSS3**: Styling the elements and adding the animation effects.
- **JavaScript**: Handling the scroll event and triggering the animations.

## How It Works
1. The boxes are initially positioned off-screen using CSS `transform`.
2. When the user scrolls, the `checkBoxes` function calculates the position of each box relative to the viewport.
3. If the box is close enough to the viewport, a CSS class `show` is added, causing the box to animate into view.

![Screenshot](https://github.com/user-attachments/assets/08cbec2a-3359-426c-b847-97059fa0b424)
