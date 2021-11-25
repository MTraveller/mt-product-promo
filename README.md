# The First Project Portfolio of CI

### The Metcon 7 For Women

Project URL: [View live project](https://mtraveller.github.io/mt-product-promo/index.html "The Website")

![Mockup](https://github.com/MTraveller/mt-product-promo/blob/cf7fca20041fcb57f4034bf3fd174c1e5b3d7fd1/rm-img/the-metcon-7-website-mockup.jpg)

The Metcon 7 project is a website promoting one specific product targeted toward women between 20-38 years old who do fitness, bodybuilding, or CrossFit training and know the importance of and appreciate quality training shoes. Based on the real world, Nike Metcon 7 training shoes. The website showcases the shoes with videos and images and leads the visitor to the product page to purchase the shoes.

### The Wireframing

For wireframing this project, mockflow.com was used to design the initial layout for desktop and mobile-sized screens. The website includes features like images, videos, tables, forms, and embeds.

| Desktop           | Mobile  |
|:-------------:| :-----:|
| [Home-Page](https://github.com/MTraveller/mt-product-promo/blob/be61291ce2195e37904c28d619390553e126686a/rm-img/home-page.png) | [Home-Page](https://github.com/MTraveller/mt-product-promo/blob/37f3a3a51a5ac0246d4c4d81c37f9be5edc74034/rm-img/home-mobile.png) |
| [Images-Page](https://github.com/MTraveller/mt-product-promo/blob/be61291ce2195e37904c28d619390553e126686a/rm-img/images-page.png) | [Images-Page](https://github.com/MTraveller/mt-product-promo/blob/37f3a3a51a5ac0246d4c4d81c37f9be5edc74034/rm-img/images-mobile.png) |
| [Contact-Page](https://github.com/MTraveller/mt-product-promo/blob/be61291ce2195e37904c28d619390553e126686a/rm-img/contact-page.png) | [Contact-Page](https://github.com/MTraveller/mt-product-promo/blob/37f3a3a51a5ac0246d4c4d81c37f9be5edc74034/rm-img/contact-mobile.png) |

### Website Features

The website has a header with a different background image for each page; the header has a dark overlay color set to 60% to make the h1 heading stand out. Below the header is the navbar with 3-links, each highlight on hover and current page.

![Header](https://github.com/MTraveller/mt-product-promo/blob/cf7fca20041fcb57f4034bf3fd174c1e5b3d7fd1/rm-img/header.jpg)

The website incorporates a simple CSS highlight method to highlight the current page a user is on for better usability.

![Navbar](https://github.com/MTraveller/mt-product-promo/blob/cf7fca20041fcb57f4034bf3fd174c1e5b3d7fd1/rm-img/navbar.jpg)

The website uses tags such as `<header>` `<nav>` `<main>` `<article>` `<section>` `<aside>` `<footer>` `<div>` `<form>` `<input>` `<table>` `<tbody>` `<tr>` `<td>` `<span>` `<h1>` `<h2>` `<h3>` `<h4>` and `<p>`.

The "Keep It Simple" mindset heavily influenced the development of the website without any use of JS and unnecessary tags, i.e., divs.

The body of the website utilizes the CSS grid property for cleaner code and to make use of the whole column, with the "grid-column" property set to 1 / -1, which makes the element take up 100% of the column area.

![GRID](https://github.com/MTraveller/mt-product-promo/blob/cf7fca20041fcb57f4034bf3fd174c1e5b3d7fd1/rm-img/grid-element-100-percent.jpg)

Images live inside the <picture> tag within the <figure> tag and use the next-gen images such as avif and webp with a fallback to png or jpg. The header does not utilize the <picture> tag as I set the background image with CSS instead merely for educational purposes. If I wanted to use next-gen images, I would use the Modernizr JS library to check which features the visitor's browser has. Then dynamically inject classes based on the information retrieved and target those classes with CSS for either next-gen or classic image types.

As for this project, I used only HTML and CSS except for the Instagram embed, which has JS in its embed code.

The video on the front page has a poster for two things; 1. controlling the first view.
2. on mobile, the video won't load as on desktop, and a genetic circle with a play button would appear.

Adding a poster attribute to the <video> tag will fix this issue and show an image for all screens for consistency. The video on images.html does not have this issue because of the autoplay attribute set.

### Accessibility

The website was produced with accessibility in mind and made sure the website fits all screen sizes perfectly according to chrome's dev tools. The result looks great.

### Font

For this project, I used [Titillium Web](https://fonts.google.com/specimen/Titillium+Web?preview.text=Explorer%20The%20Nike%20Metcon%207%20Training%20Shoes&preview.text_type=custom#standard-styles) Google font. Easy on the eye and pleasant to read. I decided to host the font locally for performance.

### Content

I took all content, images, and videos for the product from the brand's actual product page of their website. The author (I) of this project and the brand is not connected/affiliated or corporated with one another in any way, and all content, images, and videos are the brand's intellectual property only.

I have no right to any content, images, and videos used for this project. All ownership of these assets is of www.nike.com only.

## Validators

### HTML

[index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmtraveller.github.io%2Fmt-product-promo%2Findex.html "https://validator.w3.org")
[images.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmtraveller.github.io%2Fmt-product-promo%2Fimages.html "https://validator.w3.org")
[contact.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmtraveller.github.io%2Fmt-product-promo%2Fcontact.html "https://validator.w3.org")

### CSS

[index.html](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmtraveller.github.io%2Fmt-product-promo%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en "https://jigsaw.w3.org")
[images.html](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmtraveller.github.io%2Fmt-product-promo%2Fimages.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en "https://jigsaw.w3.org")
[contact.html](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmtraveller.github.io%2Fmt-product-promo%2Fcontact.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en "https://jigsaw.w3.org")

## Credits

### Content, Images, and Videos

[Nike Metcon 7](https://www.nike.com/t/metcon-7-womens-training-shoes-MjdMQM/CZ8280-515 "Product Page")

### Minifier

https://www.toptal.com/developers/cssminifier/

### Social Meta Generator

https://metatags.io

### Sources Used

https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids
https://css-tricks.com/almanac/properties/f/font-display/
https://web.dev/defer-non-critical-css/
https://drafts.csswg.org/css-grid/
https://stackoverflow.com