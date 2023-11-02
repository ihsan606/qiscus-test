# qiscus-test - Stylish Box Interactions

This is a simple HTML/CSS project that demonstrates interactive box elements with stylish background images. The project showcases the use of CSS selectors and properties to create dynamic visual effects based on user interactions.

## Demo
I have deployed this project in 2 platform : Github Pages and Google Cloud Platform via App Engine.
Links provided below:
- [Google Cloud Platform](https://gamebox-403902.uc.r.appspot.com)
- [Github Pages](ihsan606.github.io/qiscus-test)


## Project Structure

The project consists of an HTML file and a corresponding CSS file. The HTML file defines the structure of the boxes, while the CSS file provides the styling and interactivity for the elements.

## Installation

To run the project locally, simply clone the repository to your local machine:

```bash
git@github.com:ihsan606/qiscus-test.git
```
Then, open the index.html file in your web browser to view the interactive boxes.

### CSS Interactivity Details

The CSS within the project includes interactive elements that respond to user actions. Here's a breakdown of the CSS classes and their functionalities:

1. `.box_inside:hover ~ .box_inside`:
   - When you hover over one of the box elements (box_inside), a left-facing arrow image (long-arrow-left.png) will appear in the box next to it on the left.
   - The tilde (~) here signifies the selection of another box with the same class that is directly to the left of the currently hovered box.

2. `.box_inside:has(~ .box_inside:hover)`:
   - This signifies that when a box (box_inside) has another box next to it that is being hovered, a right-facing arrow image (long-arrow-right.png) will appear on that box.
   - The pseudo-class :has() indicates that the box has another box next to it that is being hovered.

These CSS properties and selectors create a dynamic and visually appealing interaction within the project.



