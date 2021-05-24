# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/curved-sections-SGLCb9Zik)
- Live Site URL: [Github Pages Link](https://landon345.github.io/frontendmentor-huddle-landing-page-curved-sections/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to curve my sections using svgs.

```html
<header>
  <div class="header">
    <img src="./images/logo.svg" alt="logo" class="logo" />
    <button class="try-free">Try it free</button>
  </div>
  <div class="community">
    <div class="community-text">
      <h1>Build The Community Your Fans Will Love</h1>
      <p class="community-para">
        Huddle re-imagines the way we build communities. You have a voice, but
        so does your audience. Create connections with your users as you engage
        in genuine discussion.
      </p>
    </div>
    <button class="my-button">Get Started For Free</button>
  </div>
  <img
    src="./images/screen-mockups.svg"
    alt="screen-mockups"
    class="screen-mockups"
  />
</header>
```

```css
.header {
  padding: 20px 20px;
  margin-bottom: 100px;
  display: flex;
  justify-content: space-between;
}
.community {
  margin-top: 60px;
}
.logo {
  object-fit: contain;
  width: 20%;
}
```

### Continued development

I'll focus on making sections different colors.

### Useful resources

- [Get Waves](https://getwaves.io/) - This helped me create my svgs for my curved sections.
- [Stretch svgs](https://stackoverflow.com/questions/11658173/how-does-one-make-a-svg-background-that-stretches-rather-than-tiles) - This helped me be able to keep the height of my svgs consistent.

## Author

- Website - [Landon Schlangen](https://www.landonschlangen.com)
- Frontend Mentor - [@Landon345](https://www.frontendmentor.io/profile/Landon345)
- LinkedIn - [Profile](https://www.linkedin.com/in/landon-schlangen-a3989a16b/)

## Acknowledgments

This project took me about 6 hours in total.
