# Frontend Mentor - Base Apparel coming soon page solution

This is a solution to the [Base Apparel coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot

![Mobile version](./mobile-version.png)
![Desktop version](./desktop-version.png)



## My process

### Built with

- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I have learned about email regex pattern,validating email using it and showing error...

```css
:root{
 --bg-gardient1:linear-gradient(135deg,hsl(0, 0%, 100%),hsl(0, 100%, 98%));
    --bg-gardient2:linear-gradient(135deg, hsl(0, 80%, 86%), hsl(0, 74%, 74%));
    --bg-gardient3:linear-gradient(135deg, hsl(0, 55%, 90%), hsl(0, 73%, 84%));
}    
```
```js
function isEmail(email){
    return /^[a-zA-Z0-9.!#$%&’*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$/.test(email);
}
```

### Continued development

I know only basics of javascript, i have to learn more about javascript..I have to improve the design so to fit in all devices irrespect of device's size..


### Useful resources

- [Javascript DOM](https://www.w3schools.com/js/js_htmldom.asp) - This helped me for understanding JS DOM. It is very important one!!.
- [addeventlistener](https://www.freecodecamp.org/news/javascript-addeventlistener-example-code/) - This is an amazing article which helped me understand addind eventlistener.
- [email regex guide](https://www.abstractapi.com/tools/email-regex-guide) - This article helps to know how to use email regex pattern to validate email.

## Author

- Frontend Mentor - [@MIBENIN](https://www.frontendmentor.io/profile/MIBENIN)


