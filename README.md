<p align="center"><img src="assets/Playing_with_CSS_Variables_and_JS (1).png"></p>

## About This Project

This project demonstrates how to build an interactive image editor that updates in real-time. It uses Vanilla JavaScript to listen for user input and update CSS variables, allowing for seamless changes to image filters, padding, and colors. This project is part of the "30 Days of JavaScript" challenge by Wes Bos.

### Key Learning Objective

- NodeList Selection: Using querySelectorAll to gather a collection of input elements and iterating through them using forEach.

- Event Handling: Implementing multiple listeners (change and mousemove) on DOM elements to ensure the UI updates instantly as the user interacts with sliders.

- Dataset Access: Accessing custom data-\* attributes (like data-sizing) from the DOM to correctly append units such as pixels (px).

- Root Style Modification: Using document.documentElement.style.setProperty() to manipulate CSS variables at the root level, which allows for global style updates with a single line of JavaScript.
