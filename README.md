# responsive-website-cheat-sheet

The figure element represents self-contained content and will allow you to associate an image with a caption.
A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element. For example, <figcaption>A cute at</figcaption> adds the caption A cute cat.

To prevent a user from submitting your form when required information is missing, you need to add the required attribute to an input element. There's no need to set a value to the required attribute. Instead, just add the word required to the input element, making sure there is space between it and other attributes.Even though you added your button below the text input, they appear next to each other on the page. That's because both input and button elements are inline elements, which don't appear on new lines.
The button you added will submit the form by default. However, relying on default behavior may cause confusion. Add the type attribute with the value submit to the button to make it clear that it is a submit button.

Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a name attribute with the same value.
Add the name attribute with the value indoor-outdoor to both radio buttons.If you select the Indoor radio button and submit the form, the form data for the button is based on its name and value attributes. Since your radio buttons do not have a value attribute, the form data will include indoor-outdoor=on, which is not useful when you have multiple buttons.

The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line.The legend element acts as a caption for the content in the fieldset element. It gives users context about what they should enter into that part of the form.

For the styling of the page to look similar on mobile as it does on a desktop or laptop, you need to add a meta element with a special content attribute.
Add the following within the head element:
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

you want to center the div horizontally. You can do this by setting its margin-left and margin-right properties to auto. Think of the margin as invisible space around an element. Using these two margin properties, center the div element within the body element.

That is kind of what you want, but now it would be nice if the flavor and price were on the same line. p elements are block-level elements, so they take up the entire width of their parent element.
To get them on the same line, you need to apply some styling to the p elements so they behave more like inline elements. To do that, start by adding a class attribute with the value item to the first article element under the Coffee heading.
That's closer, but the price didn't stay over on the right. This is because inline-block elements only take up the width of their content. To spread them out, add a width property to the flavor and price class selectors that have a value of 50% each.

The current width of the menu will always take up 80% of the body element's width. On a very wide screen, the coffee and dessert appear far apart from their prices.Add a max-width property to the menu class with a value of 500px to prevent it from growing too wide.

You change properties of a link when the mouse hovers over them by using a pseudo-selector that looks like a:hover { propertyName: propertyValue; }.
Change the color of the footer Visit our website link to be brown when a user hovers over it.
You change properties of a link when the link is actually being clicked by using a pseudo-selector that looks like a:active { propertyName: propertyValue; }.Change the color of the footer Visit our website link to be white when clicked on.
