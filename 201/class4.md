
# Class 04 - readig journal
## HTML Links, JS Functions, and Intro to CSS Layout

# **Creating hyperlinks**
## What is a hyperlink?
Hyperlinks are one of the most exciting innovations the Web has to offer. They've been a feature of the Web since the beginning, and are what makes the Web a web. Hyperlinks allow us to link documents to other documents or resources, link to specific parts of documents, or make apps available at a web address. Almost any web content can be converted to a link so that when clicked or otherwise activated the web browser goes to another web address (URL).

![Html](https://developer.mozilla.org/en-US/docs/Glossary/HTML/anatomy-of-an-html-element.png);

## Anatomy of a link
A basic link is created by wrapping the text or other content, see Block level links, inside an *<a>* element and using the *href* attribute, also
known as a Hypertext Reference, or target, that contains the web address.

> <p>
>   I'm creating a link to
>   <a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a>.
> </p>

This gives us the following result:

I'm creating a link to the [Mozilla homepage](https://www.mozilla.org/).

## Block level links
As mentioned before, almost any content can be made into a link, even block-level elements. 
If you have an image you want to make into a link, use the <a> element and reference the image file with the <img> element.
![Screenshot 2022-11-30 at 10 01 59 PM](https://user-images.githubusercontent.com/118200431/204977817-fd9effae-531d-4074-bdf0-81ec73f23b36.png)

  
  # CSS
  ## [Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow);
  As detailed in the last lesson introducing layout, elements on a webpage lay out in normal flow if you haven't applied any CSS to change the way they behave. And, as we began to discover, you can change how elements behave either by adjusting their position in normal flow or by removing them from it altogether. Starting with a solid, well-structured document that's readable in normal flow is the best way to begin any webpage. It ensures that your content is readable even if the user's using a very limited browser or a device such as a screen reader that reads out the content of the page. In addition, since normal flow is designed to make a readable document, by starting in this way you're working with the document rather than struggling against it as you make changes to the layout.

Before digging deeper into different layout methods, it's worth revisiting some of the things you have studied in previous modules with regard to normal document flow.


  ## Positioning
  
  Positioning allows us to produce interesting results by overriding normal document flow. What if you want to slightly alter the position of some boxes from their default flow position to give a slightly quirky, distressed feel? Positioning is your tool. Or what if you want to create a UI element that floats over the top of other parts of the page and/or always sits in the same place inside the browser window no matter how much the page is scrolled? Positioning makes such layout work possible.

There are a number of different types of positioning that you can put into effect on HTML elements. To make a specific type of positioning active on an element, we use the position property.

