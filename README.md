# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)

## Overview

### Screenshot

![screeenshot](/design/live_webpage.png)


### Links
- Live Site URL: [link](https://rffkive.github.io/Blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

markdown### What I learned

Through this blog preview card project, I gained valuable experience with several core CSS and HTML concepts:

1. Semantic HTML Structure: Using <main> and <footer> elements improves accessibility and SEO by helping search engines better understand the page structure.
   
```html
<main>
  <div class="card">
    <!-- Card content -->
  </div>
</main>
<footer>
</footer>
```

2. The flex: 1 Property: This allows an element to grow and fill available space, which helped create a balanced layout.

```css
main {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}
```

3. Using min-height: 100vh: Setting the minimum height to the full viewport helps ensure content is centered regardless of screen size.

```css
body {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
```

4. Inline-block Display: This provides the perfect balance for elements that need to behave as blocks but flow like inline elements, useful for tags and badges.

```css
.tag {
  display: inline-block;
  padding: 6px 12px;
  background-color: #f9d949;
  border-radius: 4px;
}
```

### Continued development

SEO Optimization: Beyond semantic HTML, I want to learn more about schema markup and other techniques to improve search engine visibility

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - Comprehensive documentation that helped me understand flexbox properties in depth.
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This visual guide to Flexbox was invaluable for centering elements.
- [Google Fonts](https://fonts.google.com/) - Used to import the Outfit font family.
- [Frontend Mentor](https://www.frontendmentor.io/) - The challenge platform that provided the design specifications.
