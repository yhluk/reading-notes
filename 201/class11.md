# Class 11 - Reading
## Video and Audio Content

1. Describe the use of the `src` and `controls` attributes in the `<video>` element.
 - `src` - The URL of the video to embed. This is optional; you may instead use the <source> element within the video block to specify the video to embed.
 - `control` - If this attribute is present, the browser will offer controls to allow the user to control video playback, including volume, seeking, and pause/resume playback.

2. Why is it important to have fallback content inside the `<video>` element?
 - Content that is to be used when the external resource cannot be used 

## Grid

1. How does Grid layout differ from Flex?
 - Flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time.
 
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
 - Grid Container: The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.
 - Grid Item: The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.
 - Grid Line: The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.

