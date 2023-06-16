# responsive-website-cheat-sheet

The <figure> element represents self-contained content and will allow you to associate an image with a caption.
A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element. For example, <figcaption>A cute at</figcaption> adds the caption A cute cat.

To prevent a user from submitting your form when required information is missing, you need to add the required attribute to an input element. There's no need to set a value to the required attribute. Instead, just add the word required to the input element, making sure there is space between it and other attributes.Even though you added your button below the text input, they appear next to each other on the page. That's because both input and button elements are inline elements, which don't appear on new lines.
The button you added will submit the form by default. However, relying on default behavior may cause confusion. Add the type attribute with the value submit to the button to make it clear that it is a submit button.

Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a name attribute with the same value.
Add the name attribute with the value indoor-outdoor to both radio buttons.If you select the Indoor radio button and submit the form, the form data for the button is based on its name and value attributes. Since your radio buttons do not have a value attribute, the form data will include indoor-outdoor=on, which is not useful when you have multiple buttons.

The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line.The legend element acts as a caption for the content in the fieldset element. It gives users context about what they should enter into that part of the form.
