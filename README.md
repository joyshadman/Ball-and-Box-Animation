# Boll-and-Box-Animation

A simple animation of a boll (ball) moving inside a box, created using HTML and CSS.

## Table of Contents

*   [Overview](#overview)
*   [Features](#features)
*   [Demo](#demo)
*   [Installation](#installation)
*   [Usage](#usage)
*   [Contributing](#contributing)
*   [License](#license)

## Overview

This project demonstrates a basic CSS animation technique to move a circular "boll" back and forth within a rectangular "box". It's a great starting point for learning about CSS animations and how to control the movement of elements on a webpage.

## Features

*   Simple and clean HTML structure.
*   CSS-based animation for smooth movement.
*   Easily customizable animation duration, color, and size.
*   Responsive design that adapts to different screen sizes.

## Usage

1.  **Customize the Animation:**

    *   **Duration:**  Modify the `animation-duration` property in the CSS rules (`@keyframes bollAnimation`).  A smaller value increases speed, a larger decreases.
    *   **Color:** Change the `background-color` property of the `.boll` class to alter the ball's color. Also change the `border` of `.box` to change the box color.
    *   **Size:** Adjust the `width` and `height` properties of the `.box` class to change the box dimensions and `width` and `height` properties of the `.boll` class to change the ball dimensions.
    *   **Path:** Adjust the `transform: translateX()` values inside the `@keyframes bollAnimation` to change the ball's path.

2.  **Integration into Existing Projects:**

    *   Copy the `index.html` or its contents and CSS code into your project, adjusting the file paths accordingly.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request.

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Commit your changes.
4.  Push to the branch.
5.  Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
