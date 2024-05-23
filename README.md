# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot!

![](https://github.com/suhanigoel24/FAQ-Accordian/assets/165935293/7fbc285e-52f2-41c9-aa19-6bac14a497bb)

### Links

- Solution URL: [solution URL](https://your-solution-url.com)
- Live Site URL: [live site URL](https://suhanigoel24.github.io/FAQ-Accordian/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

```html
<details open>
            <summary>
                <h2>
                    What is Frontend Mentor, and how will it help me?
                </h2>
            </summary>
            <p>
                Frontend Mentor offers realistic coding challenges to help developers improve their frontend coding
                skills with projects in HTML, CSS, and JavaScript. It's suitable for all levels and ideal for portfolio
                building.
            </p>
        </details>
```
```css
summary::after{
    content: ".......";
    color: rgba(255, 255, 255, 0);
    height: 30px;
    width: 30px;
    background-image: url(icon-plus.svg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    margin-left: 5px ;
    

}


details[open] > summary::after{
    background-image: url("icon-minus.svg");

}
```


## Author
- Frontend Mentor - [@suhanigoel24](https://www.frontendmentor.io/profile/suhanigoel24)
- Linked in - [Suhani Goel](https://www.linkedin.com/in/suhani-goel-a78537277/)

