# Personal Site with HTML, CSS, Bootstrap
The goal of this project is to re-create my [personal site](https://jackwaterloo.com/) using HTML, CSS, and bootstrap.

You can view the deployed version of this project at the following link: [https://jackwaterloo.github.io/personal-site-bootstrap/](https://jackwaterloo.github.io/personal-site-bootstrap/).
## Home Page
### HTML
I used [bootstrap snippets](https://getbootstrap.com/docs/5.3/examples/) to structure out my sections. I then changed the information to reflect myself.
### CSS
I opted for bootstrap classes over traditional CSS. 

Most of the CSS I wrote was for hero section and creating a mask over the background image. I researched how to change some of the CSS variables in boostrap and you can see that at the top of the `css/style.css` file.

I had to constult the documentation many times to make sure I was applying the right classes for Boostrap. It is much more convenient to use Boostrap breakpoints and columns than to use media quaries with traditional HTML and CSS.

## Contact Page
### HTML
The entire *Contact Me* section I created from scratch. The footer and nav bar were copied over from the home page.

Filling out the elements and deciding struction for the section was pretty quick. The same cannot be said about the CSS portion.

### CSS
It was very difficult to get the functionality I wanted with responsiveness. 

The CSS variable changes are still at the top of the `css/contact-me.css` page. Again, I looked that up just to change a bootstrap color, I can't honestly tell you I am familiar with CSS variables at all. 

The media quaries gave me a head ache when trying to get my desired responsivenes. In the smallest media quary, I declared so many elements as `display: block` in the hope to get the elements to stack on top of each other instead of abiding by flexbox. The devloper tools in chrome allowed me to see a lot of the CSS properties that were causing issues I made changes. Was able to ge tht desired responsivess I wanted on the site after a lot of trial and error, and some research.

The CSS code is very messy and prombably not structure optimally. I will go back and touch up styling just a bit as well as organize my CSS properly.
