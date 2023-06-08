# Frontend Mentor - QR Code Component Solution

This is a solution to the [QR Code Component Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [QR Code Component](https://your-solution-url.com)
- Live Site URL: [QR Code Component Live](https://your-live-site-url.com)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I Learned

Working on this project helped me understand how to create a responsive QR code component with good UX design. The most important takeaway was learning how to manage image overflow in a responsive environment.

The CSS code below helped me control the overflow of the QR code image:

```css
.qr-code{
    width: 90%;
    max-height: 90%; 
    border-radius: 10px 10px 0 0;
    margin-bottom: 5%;
    overflow: hidden;
}

.qr-code img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 10px;
}
```

### Continued Development

In future projects, I plan to continue focusing on making components more responsive. I also aim to learn and use more advanced CSS and JavaScript concepts to create more interactive and dynamic web pages.

### Useful Resources

[MDN Web Docs](https://your-solution-url.com) - This site was incredibly helpful for understanding HTML, CSS, and JavaScript concepts.
[CSS-Tricks] (https://your-solution-url.com) - CSS-Tricks provides useful tips and tricks for CSS. The flexbox guide on this site was very handy for this project.

#### Author: Botir Khaltaev
#### Frontend Mentor - @BotirKhaltaev

### Acknowledgments
I would like to thank Frontend Mentor for providing such a practical way to improve frontend skills. It's an excellent platform to learn, experiment, and grow as a developer.
