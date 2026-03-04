

## Title Slide


* I could replace the title page template with a custom template as mentioned here: https://quarto.org/docs/presentations/revealjs/advanced.html#custom-template
    - just need to define a title-slide.html template, and declare it under the template-partials param
    - the basic template to work or modify from is available here: https://github.com/quarto-dev/quarto-cli/blob/main/src/resources/formats/revealjs/pandoc/title-fancy/title-slide.html
    - could also customize the template to include author degrees

* In short, adapt the template title page above to perhaps have more or less the same info/structure, but allocate the left 30% of the page to LMU OSC logo and other information
* The bottom portion of the slide could be a horizontal bar with LMU contact info, an image, etc.

* Note that in the case of too many authors, more than 2 or 3 really, not all of the authors fit on the screen widthwise. Perhaps set a max size, and then have the text size dynamically resize?


### Alternative Option

* Make use of the standard footer option, and then use the title-slide-attributes field to include a background image to the whole slide with a certain degree of opacity e.g. 50% or more so that the image appears faded in the background and does not overpower foreground elements
    - would need to decide which images to include in the background


### PowerPoint Notes

* Standard slide size is 16:9 or 13.33:7.5. In any case, the ratio is 1.777
* In LMU template, measurements:
    - Top bar
        - Überschrift box: centered with width of 8.44 and height of 0.88. Vertical position 0.5 from top
        - Top right image: aligned with Überschrift box horizontally and vertically with matching height of 0.88 and width of about 1.75. There are several options for images that will be included in this section
        - To the top left corner: space for an image that will be the same height as the Überschrift box and is centered 1.44 from the left of the slide. I have a template image that will be inserted permanently into this section.
    - Left content section
        - A large green box that begins in the bottom left corner and is 0.82 wide and is 6.0 tall
            - Inside of the green box, a text box for the title and a section for the title underneath it
            - A separate box listing of the authors, their orcid, affiliation, etc.
            - A final box with dates
    - Right content section
        - An area to include a picture up to a height of 6.0 and extending to the bottom and bottom right corner of the slide.


## Table of Contents

* similar to above, can customize the TOC template: 
    - discussion on the topic: https://stackoverflow.com/questions/75024777/changing-on-which-slide-the-toc-appears-in-revealjs-slides-using-quarto
    - quarto folder with some template files: https://github.com/quarto-dev/quarto-cli/tree/main/src/resources/formats/revealjs/pandoc