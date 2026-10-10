# HTML & CSS Exercises

Exercises from my frontend development course, organized in the order I
completed them. Each folder is a standalone exercise you can open directly
in the browser.
| # | Exercise | Demo | Topics |
| --- | ----------------------------------------------------- | --------------------------------------------------------------------- | ------ |
| 01 | [HTML Media](./01-html-media) | [Live](https://eng-mohammadi.github.io/html-css-exercises/01-html-media/) | `<audio>`, `<video>`, `<img>`, multiple `<source>` formats, text formatting tags, anchor links, table layout |
| 02 | [Semantic Page & Forms](./02-semantic-page-and-forms) | [Live](https://eng-mohammadi.github.io/html-css-exercises/02-semantic-page-and-forms/) | Semantic tags (`header`, `main`, `aside`, `section`, `figure`), meta tags, `<meter>`, forms (`fieldset`, input types, `select`, `textarea`, file upload), Persian RTL layout |
| 03 | [CSS Selectors](./03-css-selectors) | [Live](https://eng-mohammadi.github.io/html-css-exercises/03-css-selectors/) | Custom Persian font with `@font-face`, class and attribute selectors, `:first-of-type`, `:last-of-type`, `:nth-of-type`, `:nth-child` (index and odd), `:hover` / `:visited`, list styling, background image, RTL layout |
| 04 | [Auth Pages](./04-auth-pages) | [Live](https://eng-mohammadi.github.io/html-css-exercises/04-auth-pages/) | Login, registration and password-recovery forms, `fieldset` / `legend`, input validation (`required`, `maxlength`, `:valid` / `:invalid`), Flexbox form layout, `@font-face` with two font variants (regular and medium), BEM-style class names, RTL layout |
| 05 | [Responsive Page](./05-responsive-page) | [Live](https://eng-mohammadi.github.io/html-css-exercises/05-responsive-page/) | Media queries (mobile, tablet and desktop breakpoints), Flexbox and CSS Grid layout, Font Awesome icons, hover transitions, `@keyframes` animation |
| 06 | [Bakery Website](./06-bakery-website) | [Live](https://eng-mohammadi.github.io/html-css-exercises/06-bakery-website/) | Static multi-page bakery site (HTML and CSS only, no JavaScript): semantic structure, responsive layout with multiple media-query breakpoints, CSS Grid and Flexbox, product cards, a dedicated product page, login/register tabs, contact form, Font Awesome icons, SCSS partials, RTL Persian layout |

## About these exercises

These were written step by step while following the course, so each one only
uses what I had learned up to that point. For example, exercises 01 and 02
were done before I learned `div`, Flexbox and Grid, so their layouts are built
with a `<table>` and inline styles. I've kept the code as I originally wrote
it to show my learning path.

- The forms in exercises 02, 04 and 06 are front-end only; they have no server-side handling.
- The CSS comments in exercise 03 keep the original exercise instructions (Persian and English).
- Exercises 05 and 06 load Font Awesome icons from a CDN, so the icons need an internet connection.
- Exercise 06 is a static site (HTML and CSS only, no JavaScript): most links are placeholders and only one product has its own page, as the exercise required.
- Exercise 06 was written in SCSS (`sass/` folder); the compiled CSS is included.

For my more recent work with modern layout and tooling, see
[React-Projects](https://github.com/eng-mohammadi/React-Projects) and
[Next.js](https://github.com/eng-mohammadi/Next.js).
