# Video props

## Video props

Beside the [Common properties](../common-properties.md), this element contains following:

### Provider

Sets the provider of the video or select as file from a bucket.

e.g. YouTube

## YouTube as a provider

## File as a provider

### Source

Specifies the source of the video by its Url or select a file from a bucket.

### Video type

Set the type of the video. By default, it is `video/mp4`.

### Controls

You can disable the controls of the video.

The controls are pause, play, stop, volume, seek, fullscreen and more.

### Plays Inline

A Boolean attribute indicating that the video is to be played "inline", that is within the element's playback area.

{% hint style="info" %}
The absence of this attribute does not imply that the video will always be played in fullscreen.
{% endhint %}

### Muted

A Boolean attribute indicating that the video should be muted by default. If controls are available, the user can still unmute the video by clicking the mute button.

### Autoplay

A Boolean attribute indicating that the video should start playing as soon as the page is loaded.

### Poster

A URL to a poster image file that is to be displayed before the video starts playing.

### Loop

A Boolean attribute indicating that the video should start over as soon as it ends.
