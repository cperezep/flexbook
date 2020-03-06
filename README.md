# FLEXBOX
* Flexbox is a new module in CSS3 that makes it easy to align elements to one another, in different directions and orders.
* The main idea behind flexbox is to give the container the ability to expand and to shrink elements to best use all the available space.
* Flexbox replaces float layouts, using less, and more readable and logical code.
* Flexbox completely changes the way that we build one-dimensional layouts.

## Container Properties
* flex-direction: Specifies in which direction the main axis goes.
* flex-wrap: Defines if the flex items should wrap into a new line if there is not enough space in the flex container.
* justify-content: Defines how the flex items will be aligned along the main axis.
* align-items: Defines how the flex items will be aligned along the cross axis.
* align-content: Only applies when there is more than one row of flex items.

## Item Properties
* align-self: Similar to align-items but just for one item.
* order: Defines the order in which one specific flex item should appear inside the container (Helpful for reorder items on small screens).
Three properties that together helps flexbox decide on the width of a flex item.
* flex-grow: Define how much an item can grow.
* flex-shrink: Define how much it can shrink.
* flex-basis: Defines its base width.
* flex: flex-grow - flex-shrink - flex-basis

## Cheat Sheet
![Flexbox](flexbox.png)

## Demo
[Demo](https://codepen.io/crperz/pen/poJWRav?editors=1100)

## Notes
* SVG(Scalable Vector Graphics) icons: There are several problems with icon fonts (really it's just a hack). Screenreaders for blind people. It's considered best practice to move away from icon fonts to SVG icons. Resource for SVG icons [icomoon](https://icomoon.io).