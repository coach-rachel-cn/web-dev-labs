# Lab 5: Styling by Id and Class & Semantic HTML Practice
This lab introduces CSS styling with IDs and Classes, and the importance of semantic HTML. You'll style elements precisely and then refactor a web page for better structure and accessibility.

## Lab Overview
* Part 1: Styling by Id
* Part 2: Styling by Class
* Part 3: Semantic HTML Practice


## Part 1: Styling by Id
In this part, you'll practice using CSS IDs to target and style specific, unique elements in your HTML. Remember that an ID should be used only once per page, making it perfect for styling a single, distinct component.

```
/* Use a # and the unique id to style a specific element */

#blueBox {
    background-color: blue;
    font-family: sans-serif;
}
```
## Part 2: Styling by Class
Now, let's explore CSS Classes. Unlike IDs, classes can be applied to multiple elements, allowing you to style groups of elements that share common characteristics. This makes your CSS more efficient and reusable!
```
/* Use a . and the class name to style all elements that have the specified class */

.greenBoxes {
    background-color: green;
    font-size: 24px;
}
```

## Part 3: Semantic HTML Practice
Good HTML isn't just about making content appear on a page; it's about giving that content meaning and structure. In this part, you'll take a non-semantic HTML page and refactor it to use more descriptive, semantic HTML5 tags. This improves accessibility for screen readers and helps other developers understand your code.

Currently, the HTML for this part uses generic div tags for most of its sections. Your job is to replace these generic divs with more semantic HTML5 tags where appropriate.

### Strategies for Implementing Semantic Elements
* Consider elements like `<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<nav>`, etc.
* Think about the structure of the page. For example, what could the main container of the page be? What about each major content block like "Overview" or "Ada's Family"? What about the source link at the bottom?
* A helpful resource for semantic elements is [W3Schools HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

Once you've refactored the HTML, you can further style semantic.css to make the page visually appealing, following good design practices

### Feeling stuck?

* Consult references like W3Schools or MDN Web Docs
* Check in with a coach or peer.
* Use an AI tool like Gemini to explain concepts or help debug your code...but remember that this does not take the place of your learning :)

#### Happy Coding!