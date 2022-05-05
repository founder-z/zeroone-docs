# Variants

You can give the element different appearance depending on their state.&#x20;

e.g. Make button change background color from <mark style="color:blue;">Blue</mark> to <mark style="color:red;">Red</mark> when hovered over.

![](<../.gitbook/assets/image (7).png>)

## Create variant

To create variant click on triangles button on the right, and select type. Newly created variant will look the same, as element style. To change its behavior you need to [record](ki.md#record-behavior) appearance, which will be used on match.&#x20;

![](<../.gitbook/assets/image (1).png>)

## Record/Edit behavior

To record how an element should appear when matched to variant condition press `Add to recording` button and change appearance.

<img src="../.gitbook/assets/image (8).png" alt="" data-size="original">

After you set desired appearance for variant click on `Stop recording` button to save.

&#x20;![](<../.gitbook/assets/image (9).png>)

## Preview variant appearance

To see how element will appear when matched variant condition press on `View variant` button.

Click `Turn off variant` to stop preview.

![](<../.gitbook/assets/image (3).png>)



## Delete variant

To delete variant hover over it in appearance menu, click `⋮` button, and then click `Remove`.

<img src="../.gitbook/assets/image (6) (1).png" alt="" data-size="original">

## Variant matching conditions

### Focused

Matches when an element has focus on it.&#x20;

Represesnts `:focus` [CSS pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes).&#x20;

[Learn more](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus)

### Not focused

Matches when an element is out of focus.

### Hovered

Matches when a user designates an item with a pointing device, for example holding the mouse pointer over it.&#x20;

Represesnts `:hover` [CSS pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes).&#x20;

[Learn more](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover)

### Not hovered

Matches when a user **doesn't** designates an item with a pointing device.

### Pressed

Matches when a user activates an item with a pointing device, for example holding mouse left button down.&#x20;

Represesnts `:active` [CSS pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes).

[Learn more](https://developer.mozilla.org/en-US/docs/Web/CSS/:active)

### Not pressed

Matches when a user **doesn't** activates an item with a pointing device.

### Focus within

Matches an element if the element or any of its descendants are focused. In other words, it represents an element that is itself matched by the `Focused` or has a descendant that is matched by `Focused`.&#x20;

Represesnts `:focus-within` [CSS pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes).

[Learn more](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-within)

### Not Focus within

Matches an element if the element or any of its descendants are **not** focused.

### Focus visible

Matches an element with the [`:focus`](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus) pseudo-class and the UA ([User Agent](https://developer.mozilla.org/en-US/docs/Glossary/User\_agent)) determines via heuristics that the focus should be made evident on the element.

Represesnts `:focus-visible` [CSS pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes).

[Learn more](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-visible)

### Not Focus visible

Matches an element with **no** [`:focus`](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus) pseudo-class and the UA ([User Agent](https://developer.mozilla.org/en-US/docs/Glossary/User\_agent)) determines via heuristics that the focus should **not** be made evident on the element.

### Add custom variant

You can create a variant for the element with custom condition using Dynamic expressions. This variant will be applied only for this element

### Add custom page variant

You can create a variant for all elements on page with custom condition using Dynamic expressions. This variant will be applied for every elements on the page

### Add custom project variant&#x20;

You can create a variant for all elements in project with custom condition using Dynamic expressions. This variant will be applied for every elements in project

