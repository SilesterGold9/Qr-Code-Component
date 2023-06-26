# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
    - [Links](#links)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media Queries
- Mobile-first workflow

### What I learned

During the process of completing this challenge, i actually pushed myself to use at least one time the grid layout, that its something that i barely use, but now that i know how to use it and the beneficts, i feel like i'll start to use it much more.

```css
.card {
    display: grid;
    justify-content: center;
    align-items: center;
    gap: 10px;
    grid-template-columns: 1fr;
    grid-template-rows: auto auto;
    width: 16rem;
  }
  .card > img {
    width: 14rem;
    justify-self: center;
  }
  .text > p {
    font-size: 15px;
    text-align: center;
  }
```

### Continued development

I definitely will use more the combination of FlexBox with Grid Layout, and i would love to use some of the most recent selectors of css, such as *:is()*, *:where()* and *:has()*.

## Author

- Website - [Silvestre Dourado](https://www.your-site.com)
- Frontend Mentor - [@SilesterGold9](https://www.frontendmentor.io/profile/yourusername)
