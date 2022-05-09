# Image

This section allows you to specify image-fit type and alignment.

## Image size

Represents `object-fit` CSS property.

[Learn more](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit)

### None&#x20;

This is default option. Allow the image to be displayed at its original size. Will be cut-out if parent element is smaller than the image, but will not be stretched.

### Fill&#x20;

The image is resized to fill the given dimension. If necessary, the image stretched or squished to fit. The image is scaled down to the smallest version of none or contain

### Scaledown&#x20;

Scale the image, so it fits parent element by one side. Image will keep its original aspect ratio, will not be cut and will leave empty space in parent.

### Cover&#x20;

Scale the image, so it fills parent element by one side. Image keep its original aspect ratio, but will be cut so no empty space remains in parent.

### Contain&#x20;

The image keeps its aspect ratio, but is resized to fit within the given dimension

## Image alignment

Represents `object-position` CSS property.

[Learn more](https://developer.mozilla.org/en-US/docs/Web/CSS/object-position)

### X-align&#x20;

This setting allows you to align the image horizontally.

### Y-align&#x20;

This setting allows you to align the image vertically.
