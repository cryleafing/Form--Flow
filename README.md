# Form & Flow - Flexbox Layout Challenge

A portfolio and client portal landing page for a fictional architecture studio. This project was developed to demonstrate mastery of the CSS Flexbox module, focusing on building complex, multi-column layouts without relying on CSS Grid. The live deployment can be found here [https://cryleafing.github.io/Form--Flow/]

## The Challenge

**Objective:** Implement a responsive and visually complex layout using only Flexbox.

**Requirements:** Create a structural puzzle of images and form elements, ensuring that elements align correctly across different screen sizes while maintaining a clean  aesthetic.

## Implementation

This project avoids CSS Grid in favour of nested Flexbox containers. Key technical decisions include:

* **Nested Flexbox Architecture:** The gallery is constructed using parent rows and nested columns. By setting `flex-direction: column` on internal containers, the layout mimics a complex masonry grid while remaining within the constraints of Flexbox logic.
* **Proportional Scaling:** Each image is housed in a container with a fixed height, using `object-fit: cover` to ensure that visual integrity is maintained regardless of the aspect ratio of the local image files.
* **Form UX:** The invite portal uses a flex-based input wrapper. By applying `flex-grow: 1` to the input fields, the typing area fills horizontal space for a consistent interface.
* **Asset Management:** All imagery is hosted locally within the project directory to ensure optimal load times.

## Getting Started

This is a static HTML and CSS project. 

1. Clone or download this repository.
2. Ensure all images are placed and referenced in the HTML.
3. Open `index.html` in a standard web browser.

## Built With

* HTML5
* CSS3
* Google Fonts
