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

Notice that the background-color for your marker is still red. This is because you set the red value of the rgb function to the max of 255, or 100% red, and set both the green and blue values to 0.Now use the rgb function to set the other colors.
In the .two CSS rule, use the rgb function to set the background-color to the max value for green, and 0 for the other values. And in the .three CSS rule, use the rgb function to set the background-color to the max value for blue, and 0 for the other values.

A very common way to apply color to an element with CSS is with hexadecimal or hex values. While hex values sound complicated, they're really just another form of RGB values.
Hex color values start with a # character and take six characters from 0-9 and A-F. The first pair of characters represent red, the second pair represent green, and the third pair represent blue. For example, #4B5320.
In the .green class selector, set the background-color property to a hex color code with the values 00 for red, FF for green, and 00 blue.
With hex colors, 00 is 0% of that color, and FF is 100%. So #00FF00 translates to 0% red, 100% green, and 0% blue, and is the same as rgb(0, 255, 0).
The HSL color model, or hue, saturation, and lightness, is another way to represent colors.
The CSS hsl function accepts 3 values: a number from 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness.
If you imagine a color wheel, the hue red is at 0 degrees, green is at 120 degrees, and blue is at 240 degrees.
Saturation is the intensity of a color from 0%, or gray, to 100% for pure color. You must add the percent sign % to the saturation and lightness values.
Lightness is how bright a color appears, from 0%, or complete black, to 100%, complete white, with 50% being neutral.

Opacity describes how opaque, or non-transparent, something is. For example, a solid wall is opaque, and no light can pass through. But a drinking glass is much more transparent, and you can see through the glass to the other side.
With the CSS opacity property, you can control how opaque or transparent an element is. With the value 0, or 0%, the element will be completely transparent, and at 1.0, or 100%, the element will be completely opaque like it is by default.
Another way to set the opacity for an element is with the alpha channel. Similar to the opacity property, the alpha channel controls how transparent or opaque a color is.
You've already set sleeve's opacity with a named color and the opacity property, but you can add an alpha channel to the other CSS color properties.
You're already familiar with using the rgb function to set colors. To add an alpha channel to an rgb color, use the rgba function instead.
The rgba function works just like the rgb function, but takes one more number from 0 to 1.0 for the alpha channel:
rgba(redValue, greenValue, blueValue, alphaValue);
You can also use an alpha channel with hsl and hex colors.

The box-shadow property lets you apply one or more shadows around an element. Here is basic syntax:
box-shadow: offsetX offsetY color;
Here's how the offsetX and offsetY values work:
both offsetX and offsetY accept number values in px and other CSS units
a positive offsetX value moves the shadow right and a negative value moves it left
a positive offsetY value moves the shadow down and a negative value moves it up
if you want a value of zero (0) for any or both offsetX and offsetY, you don't need to add a unit. Every browser understands that zero means no change.
The height and width of the shadow is determined by the height and width of the element it's applied to. You can also use an optional spreadRadius value to spread out the reach of the shadow. More on that later.

Notice that the edges of the shadow are sharp. This is because there is an optional blurRadius value for the box-shadow property:
box-shadow: offsetX offsetY blurRadius color;
If a blurRadius value isn't included, it defaults to 0 and produces sharp edges. The higher the value of blurRadius, the greater the blurring effect is.

The vh unit stands for viewport height, and is relative to 1% of the height of the viewport.
The rem unit stands for root em, and is relative to the font size of the html element.
As label elements are inline by default, they are all displayed side by side on the same line, making their text hard to read. To make them appear on separate lines, add display: block to the label element, and add a margin of 0.5rem 0, to separate them from each other.

Adding a dropdown to the form is easy with the select element. The select element is a container for a group of option elements, and the option element acts as a label for each dropdown option. Both elements require closing tags.
