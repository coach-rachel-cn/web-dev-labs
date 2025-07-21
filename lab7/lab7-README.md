# Lab 7: CSS Pseudo-classes & Transitions
Welcome to Lab 7! This lab will introduce you to CSS Pseudo-classes and CSS Transitions, powerful tools for adding interactivity and dynamic visual effects to your web pages without using JavaScript. You'll learn how to change element styles based on user interaction (like hovering) and create smooth animations for these changes.

## Part 1: Pseudo-classes Practice
**Goal**: Understand and implement various CSS pseudo-classes to style elements based on their state or relationship.

1. Open the `pseudo.html` and `pseudo.css` files in your code editor.

2. In `pseudo.css`, you'll find comments guiding you to apply styles using different pseudo-classes:

    * `:hover` - Change the background color and text color of the .button when the mouse pointer is over it.

    * `:active` - Change the background color and text color of the .button when it's being clicked.
    
    * `:focus` - Apply a border or outline to the input field when it's selected (clicked into).

    * `:nth-child()` - Style specific list items in the unordered list (e.g., the 2nd, 3rd, and 5th items).

    * `:first-child` / `:last-child` - Style the first and last paragraph in the "Paragraph Styles" section differently.

## Part 2: CSS Transitions Fun!
**Goal**: Learn how to use CSS transition properties to create smooth animations when an element's style changes.

1. Open the `transitions.html` and `transitions.css` files in your code editor.

2. In `transitions.css`, you'll apply transition properties to the `.box` element:

    * Add a transition-property to specify which CSS property (e.g., `background-color`, `width`, `height`) you want to animate.

    * Set a `transition-duration` to control how long the animation takes (e.g., 0.5s for half a second).

    * Use `transition-timing-function` (e.g., `ease`, `linear`, `ease-in-out`) to control the speed curve of the animation.

    * Apply a `transition-delay` to make the animation start after a certain time.

    * Combine transition with a `:hover` pseudo-class to make the box animate smoothly when hovered over.


### Feeling stuck?
* Consult references like W3Schools CSS Transitions and W3Schools CSS Pseudo-classes.
* Check in with a coach or peer.
* Use an AI tool like Gemini to explain concepts or help debug your code...but remember that this does not take the place of your learning!

#### Happy Coding!