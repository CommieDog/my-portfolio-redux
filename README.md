# My Portfolio Redux
A second attempt at a personal portfolio page

## Introduction

This is a personal project of mine, undertaken with an eye towards potential employers. I redesigned [an earlier portfolio website](https://github.com/CommieDog/my-portfolio) of mine from the ground up to incorporate Bootstrap and many of its design elements, such as cards and columns.

![Screenshot of final product.](https://github.com/CommieDog/my-portfolio-redux/blob/main/assets/images/readme/my-portfolio-redux-screenshot.jpg)

A sample deployment of the website is available on [GitHub Pages](https://commiedog.github.io/my-portfolio-redux/).


## Table of Contents

* [Description](#description)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Future Work](#future-work)
* [License](#license)


## Description

At the top of the webpage is an introductory header with my name, contact information, and a photo. Below that is a brief biography. The next section is a showcase of what I feel are some of my best projects, laid out individually on Bootstrap cards within a responsive row layout that stacks vertically on smaller screen sizes. Next up is a brief list of experienced gained working on my personal project. At the end is a bulleted list of contact links for GitHub, LinkedIn, and my email.

## Features

* Proper use of semantic HTML
* Responsive web design
* Multiple stylesheets
* Rich use of CSS features
  * Linear gradient background
  * Pseudo-classes such as `:hover`
  * Variables
  * Media queries
* CSS functions
    ```CSS
    .project:first-child {
      width: calc(var(--project-item-width) * var(--project-first-size-mult));
      ...
    }
* Extensive use of CSS `display` properties, including `flex` and `grid`, to display content


## Technologies Used

* HTML
* CSS
  * Bootstrap


## Future Work

The biggest improvement for this website would be to have move projects for me to display, particularly on the back end. The biography section could also use a rewrite; I'm not terribly good talking about myself.


## License

© 2022 John Netzel. All Rights Reserved.

Licenced undet the [MIT](LICENSE) License.