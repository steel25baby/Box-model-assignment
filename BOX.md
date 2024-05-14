<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [CSS BOX MODEL](#css-box-model)
    - [what is CSS box model?](#what-is-css-box-model)
    - [How does CSS box model work?](#how-does-css-box-model-work)
      - [Box model properties](#box-model-properties)
    - [specific circumstances where box model is mostly useful](#specific-circumstances-where-box-model-is-mostly-useful)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# CSS BOX MODEL

![a barner for css box model](./assets/box%20model.jpg)

### what is CSS box model?

The box model is a fundamental concept for understanding how elements are rendered on a web page. The box model defines a box around every HTML element, and this box consists of four main parts:

1. Content: This is the core area where the actual content of the element resides. It can be text, images, videos, or any other element that displays something on the page.

2. Padding: Padding is a transparent area that surrounds the content box. It creates a buffer between the content and the border. You can set the padding using the padding property in CSS, specifying values for all sides (top, right, bottom, left) or individually.

3. Border: The border is a visual line that goes around the padding and content. It can be styled with properties like border-width, border-style (solid, dashed, dotted, etc.), and border-color.

4. Margin: The margin is a transparent area that surrounds the entire box (content, padding, and border). It creates space between the element and other elements on the page. Margins are set using the margin property, similar to padding.

![a picture showing the CSS box model](./assets/Screenshot%20(147).png)

### How does CSS box model work?

- The width and height properties in CSS apply only to the content box of the element. Padding and border add to the total size of the element displayed on the screen.


- You can use the box-sizing property to change this behavior. Setting it to border-box makes the width and height include padding and border, ensuring more predictable element sizing.

#### Box model properties

- padding: Sets the padding around the content box.

- border: Sets the style, width, and color of the border.

- margin: Sets the margin around the entire box. 
- box-sizing: Controls how width and height properties interact with padding and border.

### specific circumstances where box model is mostly useful

- Creating Consistent Spacing:  The box model allows you to define consistent padding and margin values for elements throughout your webpage, ensuring a clean and organized layout.

- Aligning Elements: By manipulating margins, you can precisely align elements horizontally and vertically, creating a balanced and visually appealing layout.

- Responsive Design:  The box model plays a crucial role in responsive web design. By adjusting padding and margins based on screen size, you can ensure your webpage adapts and displays well on different devices (desktops, tablets, mobiles).

- Creating Visual Separation: Borders can be used effectively to create visual separation between elements and sections on your webpage, improving readability and user experience.

- Adding Emphasis: Strategic use of padding and borders can highlight specific elements on your webpage, drawing user attention to important content or calls to action.

Here is a CSS code that creates a box model.

```css
div {
  background-color: lightgrey;
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```

