# Building with responsive design

A clone of [The Odin Project](https://www.theodinproject.com/courses/html5-and-css3#basic-html-page-structure) built with our own CSS framework. Think bootstrap, but bootleg 

[Demo](https://raw.githack.com/fedgut/web_framework/create_framework/styles_display.html)

# Built With

- HTML
- CSS
- Personal Framework

# Using the Framework

## Structure

- The framework separates CSS files by to function to make it easier to maintain:
  <br>-cssreset.css to homologate style irrespective of browser
  <br>-layout.css has general containers
  <br>-grid.css has the grid elements and classes
  <br>-style.css has padding, margins, borders and other stylistic choices<br>
- Assets and css folders are exclusive to the framework files, project assets should be stored in p_assets
- To use icon fonts you must link the font stylesheet as in any other font

## Getting started

- Clone the project and start building on html_template.html.
- Custom CSS should be linked after framework CSS
- Framwrok includes [Google's Material Design Icons](https://material.io/resources/icons/?style=baseline) files, you can use them as images (*.png, *.svg, *.eps)
- Lint css with Stylelint, recommenden config included in repo. 

# Design Philosophy

- Maintainability: Each css file has a single responsability: reset, grid, layout or style
- Mobile first: Aiming for percentage based mobile first responsive design
- Open Source: Built with open source tech, following an open source course, and  
  open for forking and customization
- Clean Code: Linted with stylelint + stickler and validated with [WW3 CSS validator](https://duckduckgo.com/?t=lm&q=ww3+css+validator&ia=web) 

# Authors

- [Eduardo Gutierrez](https://github.com/fedgut) 

- [Abdul-samii Ajala](https://github.com/jalasem)

# Acknowledgments

- [Microverse](https://microverse.org)
- [TOP](https://www.theodinproject.com/courses/html5-and-css3#basic-html-page-structure)
- [VS Code](https://code.visualstudio.com/)

# Contact

[@eduardogpulido](https://twitter.com/eduardogpulido)
