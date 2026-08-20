# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: HTML Structure

What is the difference between the `<head>` and `<body>` sections of an HTML document? What kind of content goes in each?

**Your Answer:**
The difference between `<head>` and `<body>` is that head stores the information for the page internally and the body projects the code written, into the external page (meaning it turns the code into ) into the actual page 

## Question 2: Semantic HTML

Why should we use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything?



**Your Answer:**

semantic values like `<header>`, `<main>`, and `<footer>` are better to use over `<div>` tags because they optimize the code accessibility and help to structure the webpages in more consistent syntax. It also helps promote search engine optimization (SEO) which helps your webpage easier to find and easier to technically comprehend, and maintain good practices for your code stability especially when working with others or if other AI or AI-assisted systems to find your webpage.  


## Question 3: CSS Selectors

Given the following HTML:

```html
<ul>
  <li class="vegetable">Carrots</li>
  <li class="vegetable">Broccoli</li>
  <li class="fruit" id="favorite">Mango</li>
</ul>
```

Write THREE different CSS rules:
1. One that makes ALL list items have a `yellow` background
2. One that makes only the vegetables have `green` text color
3. One that makes only the Mango `bold`

**Your Answer:**

```css
1.
ul{
  background-color: `yellow`;
}
2.
.vegetable{
  color: `green`;
}
3.
#favorite{
  font-weight: bold:
}
```


## Question 4: The Box Model

In your own words, explain the four parts of the CSS box model (content, padding, border, margin). What is the purpose of each part?

**Your Answer:**

Content is the actual text or image inside an element. Padding is the space between the content and the border, giving it breathing room. Border is the visible line around the padding, and margin is the space outside the border that separates the element from its neighbors.


## Question 5: Box-Sizing

What problem does `box-sizing: border-box` solve? Why do we include it in a CSS reset at the top of our CSS files?

**Your Answer:**

By default, padding and border add extra width/height on top of what you set, making sizing unpredictable. box-sizing: border-box includes padding and border inside the width/height you define, so the box stays the size you intended. It's included in resets to make layouts easier to control across a whole project.



## Question 6: Display Property

What is the difference between `display: block`, `display: inline`, and `display: inline-block`? Give an example of when you might use `inline-block`.

**Your Answer:**

block elements take up the full width and start on a new line. inline elements only take up as much space as their content and sit within text, ignoring width/height . inline-block combines both. It sits in line with other elements but still accepts width, height, and margin, which is useful for things like a row of nav buttons.