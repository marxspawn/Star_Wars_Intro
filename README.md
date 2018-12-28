
# [Star Wars Opening Crawl](https://marxspawn.github.io/Star_Wars_Intro/)

## HTML, CSS and javJavaScript

### <center> Quick look at the project
> My take on the Star Wars opening crawler done through css and javascript.

- A Star Wars fontface is linked.
- Mp3 File for audio.
- CSS file is linked for viewing all animated effects.
- A generated XML-based image is emdedded for the Star Wars Logo
- Embedded JavaScript code generates the background star pattern along with selecting which episode/title/story intro to display.

----------
element

### <center> HTML
- The total HTML body line count is done in 15 lines.
    - This only includes the HTML lines in-between the body tags.
    - Does not include anything that could be linked externally.


### <center> JavaScript
- There are 2 JavaScript functions.
    1. The first is a pixel generator that randomly places stars at 3 levels moving at 3 differnt speeds to give the feeling of floating through space _(This is unlike any of the Star Wars crawlers, I did this for an added effect)_ . 
    
    2. The other uses a json-collection containing the first 8 Star Wars opening crawls. A random number is generated and then used to select which episode element to add inside the HTML when the page is loaded.


### <center> SVG
- The opening Star Wars logo is rendered by svg (Scalable Vector Graphics) and is not a standard raster image (.png, .img, .bmp, or .gif).
    - Vector images are defined using algorithms. SVG is an XML-based language used for describing the vector images. I created this svg file from a png file with a transparent background using an application called Sketch on my MacBook.
    - The image file contains shape and path definitions that the computer can use to work out what the image should look like when rendered on the screen.
    - Vector image files are usually small, but highly scalable. They do not pixellate at large sizes.
    - The total embedded XML svg line count is only 18, but is very misleading because the code is lengthy and is word wrap is used it will seem much larger.
    - You can find out more about [Vector Images here](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web).



