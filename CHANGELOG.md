# Change Log

## 3.0.1 (2018-07-21)

* [PUG]: Changed the mixin color

## 3.0.0 (2018-06-15)
* Enhancement: Pug syntax highlighting is fully reworked with intend to reduce excessive amount of similar to each other blue colors
* Enhancement: Added CSS syntax support
* Enhancement: Updated Less support
* Enhancement: Added several new colors
* Other: Changed some colors to match to the original Espresso Soda syntax theme

## 2.2.1 (2018-05-23)
* Other [SCSS]: Lightened the support function color

## 2.2.0 (2018-05-22)
* Enhancement [SCSS]: Added colors to `@` and `%` prefixes
* Enhancement [SCSS]: Added colors to `.className` dots
* Other [SCSS]: Changed the support function color (`darken()`, `rgba()` etc.)
* Fix [SCSS]: Fixed some wrong colors in several places such as the hex value color after a variable

## 2.1.0 - 2.1.1 (2018-04-13)
* Enhancement: Added SCSS support

## 2.0.0
* Fix: Changed `terminal.ansiWhite` and `terminal.ansiBrightWhite` colors from #b59c4a to #7f6d34 to fix blending with background
* Fix [JS]: Reverted some scope colors
* Enhancement [JS/CSS/LESS]: Added & changed some colors to match to the original syntax theme
* Other: Removed [better-less](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less) extension from dependencies. It is optional now and recommended for Less users
* Other: Removed unused background declarations from the json file of the theme

## 1.0.0
* Fix: Changed the invalid character color (the `invalid.illegal` scope)
* Fix: Changed the `editor.selectionBackground` color from `#eee8d5` to `#e9e1c9`
* Fix: Changed `terminal.ansiWhite` and `terminal.ansiBrightWhite` colors
* Fix: Changed the comment color (`comment`, `comment punctuation`, `comment.block.preprocessor` scopes). It was slightly blended into the background. The new color is taken from the default Solarized Light theme and is a bit darker
* Enhancement [LESS]: Added the [better-less](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less) extension as dependence to improve Less syntax highlighting
* Enhancement [CSS/LESS]: Added & changed a few colors to match to the original syntax theme

## 0.1.0
Initial version
