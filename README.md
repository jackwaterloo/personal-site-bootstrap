# Personal Site with HTML, CSS, Bootstrap
The goal of this project is to re-create my <a href="https://jackwaterloo.com/" target="_blank">personal site</a> using HTML, CSS, and bootstrap.

You can view the deployed version of this project at the following link: <a href="https://jackwaterloo.github.io/personal-site-bootstrap/" target="_blank">https://jackwaterloo.github.io/personal-site-bootstrap/</a>

## Home Page
### HTML
I used [bootstrap snippets](https://getbootstrap.com/docs/5.3/examples/) to structure out my sections. I then changed the information to reflect myself.
### CSS
I opted for bootstrap classes over traditional CSS for the home page. 

Most of the CSS I wrote was for hero section and creating a mask over the background image. I researched how to change some of the CSS variables in bootstrap and you can see that at the top of the `css/style.css` file.

I had to consult the documentation many times to make sure I was applying the right classes for Bootstrap. It is much more convenient to use Bootstrap breakpoints and columns than to use media queries for responsive design.

## Contact Page
### HTML
I utilized little bootstrap for this page. The entire *Contact Me* section I created from scratch. The footer and nav bar were copied over from the home page.

Filling out the elements and deciding structure for the section was pretty quick. The same cannot be said about the CSS portion.

### CSS

The CSS variable changes for bootstrap are still at the top of the `css/contact-me.css` page.

The media queries were a head ache when trying to achieve my desired responsiveness for the page. 

I ran into an issue with element height and position.
- An element with `position: relative` cannot also have `height: fit-content` property as well.
    - This may be because the element in question had a child element with `position absolute`. This means the child element position depends on it's parent. 

The above issue came across in my `css/contact-me.css` file with my `section` and `.flex-container` selectors in the media query. `height: fit-content` only worked after declaring the **position** for both selectors as **static**.

The developer tools in chrome allowed me to see the CSS properties that were causing issues as I made changes. I was able to get the desired responsiveness I wanted on the site after a lot of trial and error, and some research.

I do not think I am optimally using the CCS cascade to apply styles. For example, the styles applied in my media queries are very redundant but I could not find a better way to do it.

## Portfolio Page
### HTML and CSS
The HTML and CSS on this page is very basic as it is meant to be only a place holder. Take a look at the [page itself](https://jackwaterloo.github.io/personal-site-bootstrap/public/portfolio.html) for more information about the page.
