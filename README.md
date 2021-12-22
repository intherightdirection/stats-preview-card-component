# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

The stats preview card component challenge. Not completely responsive.

2nd project.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Source code](https://github.com/intherightdirection/stats-preview-card-component)
- Live Site URL: [Live site](https://intherightdirection.github.io/stats-preview-card-component/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I made the decision to not concentrate on near pixel perfect considering I do not have access to PRO features like figma or sketch layouts.

At this point it's assumed the PRO features have things like specific font sizes, letter spacing and things like that. Without them it's a whole lot of trial and error which takes away from the bigger picture of getting comfortable with CSS. Recognizing things like small design details will probably get somewhat better just from working with CSS a lot. Maybe then I will revisit these projects for new challenge.

My goal is to get comfortable in CSS and I feel I am learning quite a bit and developing a feel. 

Found out why I keep miscalculating percentages from the lengths I am going for. That had to do with the body not being the full length of view port but being short because of border surrounding it.

Learned some more stuff I don't understand about positioning and sizing.

Learned using padding to try and push stuff from edge of container just causes overflow. I need to set widths to allow for padding or margin so they don't cause unintended expansion outside parent container.

Used opacity property available the image we used. I was at first trying a translucent overlay using a div with opacity on background color, but it was easier with CSS opacity property itself.

### Continued development

Three areas I think I need to go back and put more time into are the box model, positioning and box-sizing.

## Author

Jared Dunlop

- Github - [intherightdirection](https://github.com/intherightdirection)
- Frontend Mentor - [@intherightdirection](https://www.frontendmentor.io/profile/intherightdirection)
