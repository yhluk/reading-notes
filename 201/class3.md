## [Ordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) and [Unordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul) lists in html
  The <ol> HTML element represents an ordered list of items — typically rendered as a numbered list.
>      <ol>
>           <li>Mix flour, baking powder, sugar, and salt.</li>
>           <li>In another bowl, mix eggs, milk, and oil.</li>
>           <li>Stir both mixtures together.</li>
>           <li>Fill muffin tray 3/4 full.</li>
>           <li>Bake for 20 minutes.</li>
>      </ol> -->
    
 ## <ol>: 
  
 * >Content categories. 	**Flow content, and if the <ul> element's children include at 
                        least one <li> element, palpable content.**
 * >Permitted content	  **Zero or more <li>, <script> and <template> elements.**
 * >Tag omission	        **None, both the starting and ending tag are mandatory.**
 * >Permitted parents	  **Any element that accepts flow content.**
 * >Implicit ARIA role	  **list**
 * >Permitted ARIA roles	**directory, group, listbox, menu, menubar, none, presentation, 
                        radiogroup, tablist, toolbar, tree**
 * >DOM Interface	      **HTMLUListElement**
  
##  Attributes
  
    This element also accepts the global attributes.

> reversed
This Boolean attribute specifies that the list's items are in reverse order. Items will be numbered from high to low.

> start
An integer to start counting from for the list items. Always an Arabic numeral (1, 2, 3, etc.), even when the numbering type is letters or Roman numerals. For example, to start numbering elements from the letter "d" or the Roman numeral "iv," use start="4".

> type
Sets the numbering type:

- a for lowercase letters
- A for uppercase letters
- i for lowercase Roman numerals
- I for uppercase Roman numerals
- 1 for numbers (default)
- The specified type is used for the entire list unless a different type attribute is used on an enclosed <li> element.
  
  ## Browser compatibility:
  
  ![Screenshot 2022-11-30 at 8 50 15 AM](https://user-images.githubusercontent.com/118200431/204858749-75f9ce62-6151-446d-b209-ef5923bcd380.png)<
`
  '
  
## <ul>: The Unordered List element
  
The <ul> HTML element represents an unordered list of items, typically rendered as a bulleted list.
  
  Usage notes:
  
* The <ul> element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle, or a square. The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the list-style-type property.
* The <ul> and <ol> elements may be nested as deeply as desired. Moreover, the nested lists may alternate between <ol> and <ul> without restriction.
* The <ol> and <ul> elements both represent a list of items. They differ in that, with the <ol> element, the order is meaningful. To determine which one to use, try changing the order of the list items; if the meaning is changed, the <ol> element should be used, otherwise you can use <ul>.
  
  Browser compatibility:
  
  ![Screenshot 2022-11-30 at 8 54 37 AM](https://user-images.githubusercontent.com/118200431/204859682-1db1532f-230b-4e54-ac35-0f9fce833610.png)

