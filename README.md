## Day 2 project of the 30-day code challenge


## Table of contents

- [Overview]
  - [The challenge]
  - [Screenshot]
  - [Links]
- [My process]
  - [Built with]
  - [What I learned]
  - [Continued development]
  - [Useful resources]
- [Author]



## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements
- view full content of the webpage on any screensize at a glance 
- Get a form vaidation when incorrect input is entered

### Screenshot

![](./design/active-states.png)

 
### Links

- resources:
https://stackoverflow.com/questions/5458716/is-it-possible-to-set-transparency-in-css3-box-shadow
https://smartbear.com/learn/performance-monitoring/what-is-mobile-first/


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap 
- Mobile-first workflow


### What I learned

 see below:

```html
I how to use inline html form validation and autocomplete attribute.
 <input type="text"  name="first-name" placeholder="First Name" autocomplete="name" required />
```
```css
I learned how to use rgb values make an element shadow transparent.
 .signup-detail{
	padding: 10px;
background-color: hsl(248, 32%, 49%);
border-radius: 10px;
box-shadow:2px 7px 2px  rgba(0, 0, 0, 0.4);
margin: 25px auto;

```Js
I learned how to use js to customize form validation
const email = document.getElementById("email");

email.addEventListener("input", function (event) {
  if (email.validity.typeMismatch) {
    email.setCustomValidity(" looks like this is not an email");
    email.reportValidity();
  } else {
    email.setCustomValidity("");
  }
});

### Continued development

I would like to learn more about CSS and Javascript form validations and pseudo classes

### Useful resources
form validation :https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation
transparent box-shadow: https://stackoverflow.com/questions/5458716/is-it-possible-to-set-transparency-in-css3-box-shadow
 Bootstrap: https://getbootstrap.com/docs/3.4/css/
## Author
Name-  Adeoye Joshua (https://github.com/Josh-Adey)
Twitter- themanJosh

