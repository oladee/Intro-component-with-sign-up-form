# Frontend Mentor - Intro component with sign up form solution

This is a solution to the [Intro component with sign up form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-component-with-signup-form-5cf91bd49edda32581d28fd1). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - Any `input` field is empty. The message for this error should say *"[Field Name] cannot be empty"*
  - The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say *"Looks like this is not an email"*

### Screenshot

![](./Screenshot%20(61).png)
![](./Screenshot%20(62).png)

### Links

- Solution URL: [https://github.com/oladee/Intro-component-with-sign-up-form]()
- Live Site URL: [https://oladee.github.io/Intro-component-with-sign-up-form/]()


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Javascript
- Mobile-first workflow


```html
<h1>Some css code I'm proud of</h1>
```
input:required:invalid, input:focus:invalid {
    background-image: url(./images/icon-error.svg);
    background-position: right top;
    background-repeat: no-repeat;
    border: 2px solid red;
    -moz-box-shadow: none;
  }
```

### Continued development

Some Javascript functions were relatively new in trying to achieve the client side validation, so i think i will try to look into more functions to aid in achieving better performance forms

### Useful resources

- [ resource 1](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation) - This helped me for in uderstanding client side validation. I really liked this pattern and will use it going forward.
- [ resource 2](https://www.the-art-of-web.com/html/html5-form-validation/) - This is also an amazing article.


## Author

- Website - [Momoh Oladimeji](https://www.your-site.com)
- Frontend Mentor - [@oladee](https://www.frontendmentor.io/profile/@oladee)

## Acknowledgments

Credits to frontend mentor for the being able to make challenges like this available to try out

