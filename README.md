# Integer to Cardinal Ordinal

Any number to English

## Install

```
npm install --save number-to-english
```

## Usage

Import the package

```node
const english = require("number-english");
```

Pass in any rational number:

```node
english(1521.12); // => "One Thousand Five Hundred and Twenty-One and Twelve Hundredths"
```

Or a ratio of integers:

```node
english(4, 3); // "Four Thirds"
```

## Limitations

Vocabulary is currently limited to integers below

    999,999,999,999,999

That is, the library does not currently support one quadrillion or higher.
The same goes for precision.

Higher numbers are easily supported.  If you need it, please don't be shy and
open up a pull request!

## Motivation & Related Work

[Number Reference](http://www.number-reference.com) is an online encyclopedia
of calculations that relies heavily on this and related packages.

## License

Nice and Brief: [BSD-3-Clause](./LICENSE)
