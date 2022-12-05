# Class 5 Reading Notes
## [HTML Media](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)

### How do we put an image on a webpage?
In order to put a simple image on a web page, we use the <img> element. 
This is a void element (meaning, it cannot have any child content and 
cannot have an end tag) that requires two attributes to be useful: src
and alt. The src attribute contains a URL pointing to the image you want 
to embed in the page. As with the href attribute for <a> elements, the src 
attribute can be a relative URL or an absolute URL. Without a src attribute, 
an img element has no image to load.

### Void element:
  
A void element is an element in HTML that cannot have any child nodes (i.e., nested elements or text nodes). Void elements only have a start tag; end tags must not be specified for void elements.

In HTML, a void element must not have an end tag. For example, <input type="text"></input> is invalid HTML. In contrast, SVG or MathML elements that cannot have any child nodes may use an end tag instead of XML self-closing-tag syntax in their start tag.

The HTML, SVG, and MathML specifications define very precisely what each element can contain. So, some combinations of tags have no semantic meaning.

Although there is no way to mark up a void element as having any children, child nodes can be added programmatically to the element in the DOM using JavaScript. But that is not a good practice, as the outcome will not be reliable.

<img width="687" alt="Screenshot 2022-12-04 at 10 01 38 PM" src="https://user-images.githubusercontent.com/118200431/205560861-803ece46-f74f-425e-a478-546f44b48947.png">

### Alternative text:
The next attribute we'll look at is alt. Its value is supposed to be a textual description of the image, 
for use in situations where the image cannot be seen/displayed or takes a long time to render because of 
a slow internet con<img width="495" alt="Screenshot 2022-12-04 at 10 07 04 PM" src="https://user-images.githubusercontent.com/118200431/205561441-478bd9a5-47f4-4cb9-b1ce-3f5c979312fa.png">
nection. For example, our above code could be modified like so:

![Uploading Screenshot 2022-12-04 at 10.07.04 PM.png…]()

## Applying color to HTML elements using CSS
This article is a primer introducing each of the ways CSS color can be used in HTML.

The use of color is a fundamental form of human expression. Children experiment with color before they even have the manual dexterity to draw. Maybe that's why color is one of the first things people often want to experiment with when learning to develop websites. With CSS, there are lots of ways to add color to your HTML elements to create just the look you want.

We're going to touch on most of what you'll need to know when using color, including a list of what you can color and what CSS properties are involved, how you describe colors, and how to actually use colors both in stylesheets and in scripts. We'll also take a look at how to let the user pick a color.

Then we'll wrap things up with a brief discussion of how to use color wisely: how to select appropriate colors, keeping in mind the needs of people with differing visual capabilities.

## Things that can have color:
At the element level, everything in HTML can have color applied to it. Instead, let's look at things in terms of the kinds of things that are drawn in the elements, such as text and borders and so forth. For each, we'll see a list of the CSS properties that apply color to them.

At a fundamental level, the color property defines the foreground color of an HTML element's content and the background-color property defines the element's background color. These can be used on just about any element.


 - ### Text
Whenever an element is rendered, these properties are used to determine the color of the text, its background, and any decorations on the text.

 - ### color
The color to use when drawing the text and any text decorations (such as the addition of under- or overlines, strike-through lines, and so forth.

 - ### background-color
The text's background color.

 - ### text-shadow
Configures a shadow effect to apply to text. Among the options for the shadow is the shadow's base color (which is then blurred and blended with the background based on the other parameters). See Text drop shadows in Fundamental text and font styling to learn more.

 - ### text-decoration-color
By default, text decorations (such as underlines, strikethroughs, etc.) use the color property as their colors. However, you can override that behavior and use a different color for them with the text-decoration-color property.

 - ### text-emphasis-color
The color to use when drawing emphasis symbols adjacent to each character in the text. This is used primarily when drawing text for East Asian languages.

 - ### caret-color
The color to use when drawing the caret (sometimes referred to as the text input cursor) within the element. This is only useful in elements that are editable, such as <input> and <textarea> or elements whose HTML contenteditable attribute is set.

 - ### Boxes
Every element is a box with some sort of content, and has a background and a border in addition to whatever contents the box may have.

 - ### Borders
See the section Borders for a list of the CSS properties you can use to set the colors of a box's borders.

 - ### background-color
The background color to use in areas of the element that have no foreground content.

 - ### column-rule-color
The color to use when drawing the line separating columns of text.

 - ### outline-color
The color to use when drawing an outline around the outside of the element. This outline is different from the border in that it doesn't get space set aside for it in the document (so it may overlap other content). It's generally used as a focus indicator, to show which element will receive input events.

 - ### Borders
Any element can have a border drawn around it. A basic element border is a line drawn around the edges of the element's content. See Box properties in The box model to learn about the relationship between elements and their borders, and the article Styling borders using CSS to learn more about applying styles to borders.

You can use the border shorthand property, which lets you configure everything about the border in one shot (including non-color features of borders, such as its width, style (solid, dashed, etc.), and so forth.

 - ### border-color
Specifies a single color to use for every side of the element's border.

 - ### border-left-color, border-right-color, border-top-color, and border-bottom-color
Lets you set the color of the corresponding side of the element's border.

 - ### border-block-start-color and border-block-end-color
With these, you can set the color used to draw the borders which are closest to the start and end of the block the border surrounds. In a left-to-right writing mode (such as the way English is written), the block start border is the top edge and the block end is the bottom. This differs from the inline start and end, which are the left and right edges (corresponding to where each line of text in the box begins and ends).

 - ### border-inline-start-color and border-inline-end-color
These let you color the edges of the border closest to the beginning and the end of the start of lines of text within the box. Which side this is will vary depending on the writing-mode, direction, and text-orientation properties, which are typically (but not always) used to adjust text directionality based on the language being displayed. For example, if the box's text is being rendered right-to-left, then the border-inline-start-color is applied to the right side of the border.


