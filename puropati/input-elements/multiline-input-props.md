# Multiline input props

Beside the [Common properties](../common-properties.md), this element contains following:

## Default value
This is the value that will be set when the component is mounted.

## Placeholder
This is the text that will be displayed when the input is empty.

## Type
This is the type of the input. It can be one of the following:
- text
- number
- tel
- url
- password
- week
- file
- date
- datetime-local
- time
- month

## Disabled
This is a boolean that will disable the input. It will be set to false by default.

## Max length
This is the maximum length of the input. By default, the input can have any length.
Length is measured in characters. It can be set to 0 or empty, to disable the limit.
[Learn more](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/maxlength)