# Field types

Each field has it's own type, in which data is stored.

### Number

The `Number` type is a [double-precision 64-bit binary format IEEE 754](https://en.wikipedia.org/wiki/Floating-point\_arithmetic) value, like `double` in Java or C#. This means it can represent fractional values, but there are some limits to what it can store.&#x20;

A `Number` only keeps about 17 decimal places of precision; arithmetic is subject to [rounding](https://en.wikipedia.org/wiki/Floating-point\_arithmetic#Representable\_numbers,\_conversion\_and\_rounding). The largest value a `Number` can hold is about 1.8E308. Values higher than that are replaced with the special `Number` constant [`Infinity`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global\_Objects/Infinity).

e.g. 0, 11, -22, 3.141592653589793

### Text

`Text` (or `String`) are useful for holding data that can be represented in text form. Length of text is unlimitted.

### Yes / No

`Yes / No` (or `boolean`) is a primitive data type in JavaScript. It can have only two values: `true or false` (or `Yes / No`). It is useful in controlling program flow using conditional statements like `if`.

### Date

A timestamp format with timezone. [Learn more](https://en.wikipedia.org/wiki/ISO\_8601)

YYYY-MM-DDTHH:mm:ss.sss+HH:mm

e.g. `2000-12-31T23:59:59.999+00:00`

### File

A JSON that contains file name and bucket name.&#x20;

e.g.&#x20;

### Date range



### Duration

The duration data type allows you to store and manipulate a period of time in years, months, days, hours, minutes, seconds, etc. [Learn more](https://en.wikipedia.org/wiki/ISO\_8601#Durations)

Abbreviations used:

| Abbreviations   | Stored as   |
| --------------- | ----------- |
| year, y         | year, years |
| month, mon      | mon, mons   |
| day, d          | day, days   |
| hour, hours, h  | HH:00:00    |
| minutes, min, m | 00:mm:00    |
| seconds, sec, s | 00:00:ss    |

### List of Numbers

### List of Text

### List of Yes / Nos

### List of Files

### List of Dates

### List of Date ranges

### List of Durations

### Rich text

Rich text is more exciting than plain text. It supports text formatting, such as **bold**, _italics_, and underlining, as well as different fonts, font sizes, and colored text. Rich text documents can also include page formatting options, such as custom page margins, line spacing, tab widths, images and many more.

### References
