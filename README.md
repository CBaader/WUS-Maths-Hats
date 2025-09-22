# Circle Geometry Visualiser

A simple JavaScript and HTML Canvas animation that provides a visual proof for a classic geometry problem involving inscribed circles. This visualisation demonstrates the relationship between the radii of tangent circles, leading to a specific integer solution.

## The Problem Visualised

This animation addresses a problem where smaller circles are progressively inscribed within the space defined by larger circles and bounding lines. The core task is to determine the radius of each new circle, which must be perfectly tangent to its neighbours. This visualisation specifically demonstrates the scenario that elegantly results in the solution '4'.

## Usage

No installation is required.

1.  Clone or download this repository.
2.  Open the `circle_animation.html` file in any modern web browser (e.g., Chrome, Firefox, Safari).

## Technical Details

-   **Graphics:** The animation is rendered using the HTML `<canvas>` element.
-   **Logic:** Vanilla JavaScript is used to calculate the geometric properties (positions, radii) of the circles and to manage the animation loop via `requestAnimationFrame`.
-   **Structure:** All necessary code (HTML, CSS, and JavaScript) is contained within a single `.html` file for maximum portability and simplicity.

## License

This project is licensed under the MIT License.
