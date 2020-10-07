This is a brief project in which I'll deconstruct and reconstruct an existing website. Webtools will be the main tool used in this.

I've managed to use some degree of HTML and CSS, although frankly with a lot left to be desired. I managed to implement most of the features to a somewhat satisfactory degree, although some degree of laziness was shown in not taking care to make things look exactly the same. Despite that, I'm decently happy with how it turned out since it's the second time I've ever used HTML and CSS. The one thing that irks me is the issues with the footer, but those stem from apparent conflict between flexboxes and position:fixed, since I needed position fixed to put it at the bottom of the page and the flex boxes to display my two lists of links on either side of the screen. All in all it's fine for a first try, in my own opinion.

CORRECTION

I had earlier tried using display:flex on the body element to do it, but things just went haywire, so instead I did it for each individual element. Upon realizing that I had forgotten to set the flex-direction to column, I did so. Which also fixed my footer.
