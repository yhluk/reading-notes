# Class 5 Reading Notes
## [HTML Media](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)

###How do we put an image on a webpage?
In order to put a simple image on a web page, we use the <img> element. 
This is a void element (meaning, it cannot have any child content and 
cannot have an end tag) that requires two attributes to be useful: src
and alt. The src attribute contains a URL pointing to the image you want 
to embed in the page. As with the href attribute for <a> elements, the src 
attribute can be a relative URL or an absolute URL. Without a src attribute, 
an img element has no image to load.

### Void element
A void element is an element in HTML that cannot have any child nodes (i.e., nested elements or text nodes). Void elements only have a start tag; end tags must not be specified for void elements.

In HTML, a void element must not have an end tag. For example, <input type="text"></input> is invalid HTML. In contrast, SVG or MathML elements that cannot have any child nodes may use an end tag instead of XML self-closing-tag syntax in their start tag.

The HTML, SVG, and MathML specifications define very precisely what each element can contain. So, some combinations of tags have no semantic meaning.

Although there is no way to mark up a void element as having any children, child nodes can be added programmatically to the element in the DOM using JavaScript. But that is not a good practice, as the outcome will not be reliable.

The void elements in HTML are as follows:

