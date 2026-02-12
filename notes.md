

## Title Slide


* I could replace the title page template with a custom template as mentioned here: https://quarto.org/docs/presentations/revealjs/advanced.html#custom-template
    - just need to define a title-slide.html template, and declare it under the template-partials param
    - the basic template to work or modify from is available here: https://github.com/quarto-dev/quarto-cli/blob/main/src/resources/formats/revealjs/pandoc/title-fancy/title-slide.html
    - could also customize the template to include author degrees

* In short, adapt the template title page above to perhaps have more or less the same info/structure, but allocate the left 30% of the page to LMU OSC logo and other information
* The bottom portion of the slide could be a horizontal bar with LMU contact info, an image, etc.


### Alternative Option

* Make use of the standard footer option, and then use the title-slide-attributes field to include a background image to the whole slide with a certain degree of opacity e.g. 50% or more so that the image appears faded in the background and does not overpower foreground elements
    - would need to decide which images to include in the background


## Table of Contents

* similar to above, can customize the TOC template: 
    - discussion on the topic: https://stackoverflow.com/questions/75024777/changing-on-which-slide-the-toc-appears-in-revealjs-slides-using-quarto
    - quarto folder with some template files: https://github.com/quarto-dev/quarto-cli/tree/main/src/resources/formats/revealjs/pandoc