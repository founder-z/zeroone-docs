# CSS units

## CSS Units

CSS has several different units for expressing a length.

Many CSS properties take "length" values, such as `width`, `margin`, `padding`, `font-size`, etc.

**Length** is a number followed by a length unit, such as `10px`, `2em`, etc.

For some CSS properties, negative lengths are allowed.

There are two types of length units: **absolute** and **relative**.

## Absolute Lengths

The absolute length units are fixed and a length expressed in any of these will appear as exactly that size.

Absolute length units are not recommended for use on screen, because screen sizes vary so much. However, they can be used if the output medium is known, such as for print layout.

| Unit  | Description                  |
| ----- | ---------------------------- |
| px \* | pixels (1px = 1/96th of 1in) |

\* Pixels (px) are relative to the viewing device. For low-dpi devices, 1px is one device pixel (dot) of the display. For printers and high resolution screens 1px implies multiple device pixels.

## Relative Lengths

Relative length units specify a length relative to another length property. Relative length units scale better between different rendering medium.



| Unit | Description                                                                                             |
| ---- | ------------------------------------------------------------------------------------------------------- |
| em   | <p>Relative to the font-size of the element </p><p>(2em means 2 times the size of the current font)</p> |
| rem  | Relative to font-size of the root element                                                               |
| vw   | Relative to 1% of the width of the viewport\*                                                           |
| vh   | Relative to 1% of the height of the viewport\*                                                          |
| %    | Relative to the parent element                                                                          |

**Tip:** The em and rem units are practical in creating perfectly scalable layout!\
\* Viewport = the browser window size. If the viewport is 50cm wide, 1vw = 0.5cm.

## Hug-content

Set an auto layout frame to **Hug content** to resize itself according to its child objects. The frame will keep the smallest possible dimensions to surround the objects within it, while respecting the padding value. Represents `width: auto` css property. [Learn more](https://developer.mozilla.org/en-US/docs/Web/CSS/width)

## Stretch

Set an auto layout frame to **Stretch** to resize itself according to its parent objects. The frame will keep maximum possible dimensions to surround the objects around it, while respecting the padding value. Represents `width: 100%` css property. [Learn more](https://developer.mozilla.org/en-US/docs/Web/CSS/width)
