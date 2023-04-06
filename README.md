# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: (https://ohiole.github.io/Result-Summary/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
I used the @media queries to make the page responsive

To see how you can add code snippets, see below:

```css
@media (max-width: 620px) {
    .wrapper{
        display: flex;
        flex-direction: column;

        height: 100vh;
        width: 100%;
        border-radius: 0;
    }
    .result{
        width: 100%;
        padding: 20px;
        height: 45%;
        border-top-right-radius: 0;
        border-top-left-radius: 0;
        gap: 1em;
    }

    .scoreText{
        width: 55%;
    }

    .summary{
        width: 100%;
        padding: 20px;
        height: 55%;
    }

    .scoreLine1,
    .scoreLine2,
    .scoreLine3,
    .scoreLine4,
    button{
        width: 100%;
        margin-top: 15px;
    }
}
```


### Continued development

- I want to be able to develop a responsive website for all screen types, and i want to properly use @media queries.
- Next up is tailwind css and bootstrap. 
- I also want to extremely perfect at DOM Manipulaton.


### Useful resources

- (https://www.w3schools.com/css/default.asp) - This helped me for my CSS. I really liked this pattern and will use it going forward.
- Meta Front end Development course



## Author

- Frontend Mentor - [@Ohiole](https://www.frontendmentor.io/profile/Ohiole)




