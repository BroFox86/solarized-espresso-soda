# Change Log

## 3.0.0 (2018-06-15)
* Enhancement: Pug syntax highlighting is fully reworked with intend to reduce excessive amount of blue colours
* Enhancement: Added CSS syntax support
* Enhancement: Updated Less support
* Enhancement: Added several new colours
* Other: Changed some colours to match to the original Espresso Soda syntax theme

## 2.2.1 (2018-05-23)
* Other [SCSS]: Lightened the support function colour

## 2.2.0 (2018-05-22)
* Enhancement [SCSS]: Added appropriate colours to `@` and `%` prefixes
* Enhancement [SCSS]: Added colours to `.className` dots
* Other [SCSS]: Changed the support function colour (`darken()`, `rgba()` etc.)
* Fix [SCSS]: Fixed some wrong colours in several places such as the hex value colour after a variable: `$grey: #333`

## 2.1.1 (2018-04-13)
* Other [SCSS]: Updated mixin color

## 2.1.0 (2018-04-13)
* Enhancement: Added SCSS support
* Enhancement [SCSS]: Added SCSS mixin color

## 2.0.0
* Fix: Changed `terminal.ansiWhite` and `terminal.ansiBrightWhite` colours from #b59c4a to #7f6d34 to fix blending with background
* Fix [JS]: Reverted some scope colours
* Fix [LESS/CSS]: Changed the `punctuation.definition.entity.css` colour to match to the original Espresso Soda syntax theme and added `punctuation.definition.entity.less` colour with last value from `punctuation.definition.entity.css`
* Enhancement [JS]: Added several scope colours to match to the original Espresso Soda syntax theme
* Enhancement [LESS]: Added the `meta.property-value.less` colour to match to the original Espresso Soda syntax theme
* Other: Removed [better-less](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less) extension from dependencies. It is optional now and recommended for Less users
* Other: Removed unused background declarations from the json file of the theme

## 1.0.0
* Fix: Changed the invalid character colour (the `invalid.illegal` scope)
* Fix: Changed the `editor.selectionBackground` colour from `#eee8d5` to `#e9e1c9`
* Fix: Changed `terminal.ansiWhite` and `terminal.ansiBrightWhite` colours
* Fix: Changed the comment colour (`comment`, `comment punctuation`, `comment.block.preprocessor` scopes). It was slightly blended into the background. The new colour is taken from the default Solarized Light theme and is a bit darker
* Enhancement [LESS]: Added the [better-less](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less) extension as dependence to improve Less syntax highlighting
* Enhancement [CSS/LESS]: Added a few scope colours to match to the original Espresso Soda syntax theme
* Enhancement [CSS/LESS]: Changed the CSS tag colour (the `entity.name.tag.css` scope) and the Less ampersand colour (the `punctuation.definition.entity.css` scope) to match to the original Espresso Soda syntax theme.

## 0.1.0
Initial version
