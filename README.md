# unit-synonyms-temperature-difference

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-temperature-difference.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-temperature-difference)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-temperature-difference/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-temperature-difference?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-temperature-difference/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-temperature-difference)

Temperature difference units synonyms

## Install

    npm i unit-synonyms-temperature-difference

## Units

- [Celsius](https://en.wikipedia.org/wiki/Celsius)
- [Fahrenheit](https://en.wikipedia.org/wiki/Fahrenheit)
- [Kelvin](https://en.wikipedia.org/wiki/Kelvin)
- [Rankine](https://en.wikipedia.org/wiki/Rankine_scale)
- [Delisle](https://en.wikipedia.org/wiki/Delisle_scale)
- [Newton](https://en.wikipedia.org/wiki/Newton_scale)
- [Reaumur](https://en.wikipedia.org/wiki/Réaumur_scale)
- [Romer](https://en.wikipedia.org/wiki/Rømer_scale)

## Usage

```js
var synonyms = require('unit-synonyms-temperature-difference').synonyms;

synonyms['°C']; // => celsius
synonyms['degrees fahrenheit']; // => fahrenheit
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
