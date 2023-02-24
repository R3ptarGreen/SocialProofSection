# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![Desktop](./images/Screenshot%202023-02-23%20at%2023-08-25%20Social%20proof%20section.png)
![Mobile](./images/Screenshot%202023-02-23%20at%2023-08-57%20Social%20proof%20section.png)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned
 This challenges was complicated to me, perhaps I spend a lot of my time (I'm talking about 8h) solving it and finally I did it, and I'm proud how I use only grid display to make all the challenge.

```css
@media (max-width: 700px){
    
    .container{
        margin: auto;
        margin-top: 10vh;
        width: 350px;
        height: 1400px;
        display: grid;
        grid-template-rows: 35% 65%;
        grid-template-areas: "header"
                             "profile";
    }
    .header{
        width: 22rem;
        grid-area: header;
        display: grid;
        padding: 0;
        grid-template-rows: 40% 60%;
        grid-template-areas: "title"
                             "rate";                
    }
    .title{
        width: 22rem;
        grid-area: title;
        padding: 0;
        margin: 0;
        display: grid;
        grid-template-areas: "h1"
                             "p";
    }
    .title h1{
        padding: 0;
        margin: 0;
        padding-top: 0;
        grid-area: h1;
        font-size: 2em;
        width: 13rem;
        align-items: center;
        text-align: center;
        justify-self: center;
    }
    .title p{
        width: 22rem;
        text-align: center;
    }
    .rate{
        width: 22rem;
        grid-area: rate;
        padding: 1rem;
        margin-top: 1rem;
        grid-template-rows: 33% 33% 33%;
        grid-template-areas: "reviews"
                             "report"
                             "tech";
    }
    .reviews{
        display: block;
        grid-area: reviews;
        width: 100%;
        height: 4rem;
        text-align: center;
        margin: 0;
        padding: 0;
        padding-top: 1rem;
    }
    .report{
        display: block;
        grid-area: report;
        width: 100%;
        height: 4rem;
        text-align: center;
        margin: 0;
        padding: 0;
        padding-top: 1rem;
    }
    .tech{
        display: block;
        grid-area: tech;
        width: 100%;
        height: 4rem;
        text-align: center;
        margin: 0;
        padding: 0;
        padding-top: 1rem;
    }
    .profile{
        grid-area: profile;
        display: grid;
        grid-template-rows: 29% 29% 29% 10%;
        grid-template-areas: "colton"
                             "irene"
                             "anne"
                             "empty";
        width: 22rem;
    }
    .colton{
        grid-area: colton;
        padding-top: 2rem;
    }
    .irene{
        grid-area: irene;
        padding-top: 2rem;

    }
    .anne{
        grid-area: anne;
        padding-top: 2rem;

    }
    .colton, .irene, .anne{
        width: 20rem;
        margin-top: 0;
        height: 15rem;
    }
    .colton p, .irene p, .anne p{
        text-align: start;
    }
}
```

### Continued development

I would like continued development on my time to finish more quickly some challenges and short/clean/optimize the code

### Useful resources

- [Rem vs Em](https://www.youtube.com/watch?v=okw-whFWGEo&ab_channel=IanLenehan) - If you want more help know the diference between rem and em, I recommended check this video on youtube

## Author

- Frontend Mentor - [@R3ptarGreen](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

I'm studying by myself in FreeCodeCamp and I'm improving my skills with Frontend Mentor
