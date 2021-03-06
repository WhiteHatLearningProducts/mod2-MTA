# The Box Model

*   _4.2 Style HTML box properties Apply styles to alter appearance attributes (size, border and rounding border corners, outline, padding, margin); apply styles to alter graphic effects (transparency, opacity, background image, gradients, shadow, clipping); apply styles to establish and change an element’s position (static, relative, absolute, fixed)_

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vR9fXGQK-iEBE2zaLeilLJlAM0_90xheU8S1VTGyvT08hmVuKDK-sPlL34MeXf3bv-Pl8zBw9caaHti/embed?start=false&amp;loop=true&amp;delayms=60000" frameborder="0" width="100%" height="444" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Every HTML element has box properties. These are the properties that control how the element is spaced on the page and control the position of the box contents. In addition, the graphic effects can be applied to the box of an element.

The border element supports many variants in its ability to set properties in a single line. Take some time to experiment with all the possible combinations so you will be able to read them and identify them easily on the exam.

CSS3 allows you to style box properties in the following ways:

*   Every HTML element is a box and has the properties of a box such as height and width.
*   CSS3 allows you to change the size of a box by specifying a new height and width.
*   The border-style property allows you to specify a solid or dashed line for the border.
*   The border-color property allows you to specify the color of the border.
*   The border-spacing property allows you to specify the amount of space between adjacent elements
*   The border-width property allows you to specify a thickness for the border.
*   Each side of the box can by styled differently.
*   CSS3 provides a way to define the padding and margin that a box should have relative to adjacent elements. This can be configured differently for each side of the box.
*   An element can be made transparent or partially transparent by setting the opacity property.
*   An element can contain a background image by setting its background-image property.
*   CSS3 provides the ability to create shadow effects by specifying the box-shadow property.
*   CSS3 provides the ability to clip images using the clip property to show only a portion of an image.
*   CSS3 can be used to establish an element’s position as either fixed, absolute, or relative.
*   The left and top CSS properties can be used to alter an element’s position.

# Responsive Layouts

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRUJJDlTFSLduiExxM64ScDeuOxSNQz12qkqPJy0MIBTyhv-dI74jnG7mbuumI9eHXrUI3DZ2wPz3QV/embed?start=false&amp;loop=false&amp;delayms=3000" frameborder="0" width="100%" height="444" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

# CSS selectors

Before we go much further lets take a good look at CSS selectors.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQnSLd9aR-oTZ2rBFNX_tPXh5gAdcn3s3qRjciRxuzGisT6caCl-7IOt3jLBtF3l9VF8xLT52mwewmv/embed?start=false&amp;loop=false&amp;delayms=3000" frameborder="0" width="100%" height="444" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Our audio app is going to need the following sections:

*   a header area to brand our app
*   a place for the interactive grid
*   a nav area for the control buttons; play and stop
*   a place to list tracks
*   an area for our audio visualisations
*   a footer for credits

Create a responsive layout that has a place for all of these sections. Use your knowledge of HTML semantic elements and the box model. Start with a mobile layout by copying the css styles below, then adjust the style for different break points. As your screen grows in scale and crosses a break point, different css rules will be applied.

```css
/* css for mobile goes here */
@media screen and (min-width: 30em) {
  /* css for small screens goes here */
}
@media screen and (min-width: 30em) and (max-width: 60em) {
  /* css for mid screens goes here */
}
@media screen and (min-width: 60em) {
  /* css for massive screens goes here */
}
```