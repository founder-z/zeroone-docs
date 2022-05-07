# Position

You can specify element positioning type and it's position in [CSS units](css-units.md).&#x20;

[Learn more about position](https://developer.mozilla.org/en-US/docs/Web/CSS/position)

## Fixed

Represents CSS `position: fixed` property.

The element is removed from the normal document flow, and no space is created for the element in the page layout. It is positioned relative to the initial [containing block](https://developer.mozilla.org/en-US/docs/Web/CSS/Containing\_block) established by the [viewport](https://developer.mozilla.org/en-US/docs/Glossary/Viewport), except when one of its ancestors has a `transform`, `perspective`, or `filter` property set to something other than `none` (see the [CSS Transforms Spec](https://www.w3.org/TR/css-transforms-1/#propdef-transform)), in which case that ancestor behaves as the containing block. (Note that there are browser inconsistencies with `perspective` and `filter` contributing to containing block formation.) Its final position is determined by the values of `top`, `right`, `bottom`, and `left`.

This value always creates a new [stacking context](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS\_Positioning/Understanding\_z\_index/The\_stacking\_context). In printed documents, the element is placed in the same position on _every page_.

## Free

Represents CSS `position: absolute` property.  &#x20;

The element is removed from the normal document flow, and no space is created for the element in the page layout. It is positioned relative to its closest positioned ancestor, if any; otherwise, it is placed relative to the initial [containing block](https://developer.mozilla.org/en-US/docs/Web/CSS/Containing\_block). Its final position is determined by the values of `top`, `right`, `bottom`, and `left`.

This value creates a new [stacking context](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS\_Positioning/Understanding\_z\_index/The\_stacking\_context) when the value of `z-index` is not `auto`. The margins of absolutely positioned boxes do not [collapse](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS\_Box\_Model/Mastering\_margin\_collapsing) with other margins.

## Auto

Represents CSS `position: relative` property.  &#x20;

The element is positioned according to the normal flow of the document, and then offset _relative to itself_ based on the values of `top`, `right`, `bottom`, and `left`. The offset does not affect the position of any other elements; thus, the space given for the element in the page layout is the same as if position were `static`.

This value creates a new [stacking context](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS\_Positioning/Understanding\_z\_index/The\_stacking\_context) when the value of `z-index` is not `auto`. Its effect on `table-*-group`, `table-row`, `table-column`, `table-cell`, and `table-caption` elements is undefined.
