# Building with responsive design

A clone of [The Odin Project](https://www.theodinproject.com/courses/html5-and-css3#basic-html-page-structure) built with a custom CSS framework. Think bootstrap, but bootleg 

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

## Getting started

- Clone the project and start building on html_template.html.
- Custom CSS should be linked after framework CSS in html_template.html
- Framework includes [Google's Material Design Icons](https://material.io/resources/icons/?style=baseline) files, you can use them as images (*.png, *.svg, *.eps)
- Lint css with Stylelint, recommenden config included in repo. 

## Grid

This framwrok is flex grid-based, with 12 columns.

### For responsive design 

- Start with the smallest column use classes: _.col-1_ thru ._col-12_
- At screen width 576px: _col-sm-1_ thru _col-sm-12_
- At screen width 768px: _col-md-1_ thru _col-md-12_
- At screen width 992px: _col-lg-1_ thru _col-lg-12_
- Rows should use _.row_ class

## Layout 

Classes for 
- _.navbar_  Use for your nav bar
- _.nav-item_ Use for items inside the nav bar
- _.container-fluid_ Use for wraping content
- _.d-none_, _d-sm-none_, _d-md-none_, _d-lg-none_ and  _d-sm-flex_, _d-md-flex_, _d-lg-flex_ to hide and show elements at different breakpoints with only css 

## Style 

- Padding and Margin: Class name is constructed as follows:

Prefix: (.ma for margin)  
.pa (Padding all)   
.pt (Padding top)  
.pr (Padding Right)  
.pb (Padding Bottom)  
.pl (Padding Left)  
.px (Padding x Axis)  
.py (padding y Axis)  

Followed by -1 thru -10 sufix for the number of pixels

Example: _.mx-5_ for marging left and right (x axis) of 5 px per side. 

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
