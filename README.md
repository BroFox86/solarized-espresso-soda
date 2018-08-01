<div align="center"><img width="600" src="https://github.com/BroFox86/solarized-espresso-soda/raw/master/logo.png"></div>

This is a color theme for MS Visual Studio Code editor. Basically the theme is converted from 
the original [Soda](https://github.com/buymeasoda/soda-theme) syntax theme but contains some reworks & improvements and based on the default Solarized Light theme. 
Also available <img src="https://github.com/BroFox86/theme-espresso-soda-light/raw/master/icon-small.png" width=16 height=16/> [Espresso Soda](https://marketplace.visualstudio.com/items?itemName=brofox86.theme-espresso-soda-light) that based on the default Light theme.

## Screenshots

*Java Script:*<br>
![Screenshot](https://github.com/BroFox86/solarized-espresso-soda/raw/master/screenshots/js.png)

*Pug (manually reworked):*<br>
![Screenshot](https://github.com/BroFox86/solarized-espresso-soda/raw/master/screenshots/pug.png)

*SCSS (CSS and Less are also supported):*<br>
![Screenshot](https://github.com/BroFox86/solarized-espresso-soda/raw/master/screenshots/scss.png)

*HTML:*<br>
![Screenshot](https://github.com/BroFox86/solarized-espresso-soda/raw/master/screenshots/html.png)

## Less syntax

I recommend install [better-less](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less) extension together with this theme for properly highlight Less syntax in VSC. 

## Installation

This theme is available for free in the <img src="https://marketplace.visualstudio.com/favicon.ico" width=16 height=16/> [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=brofox86.theme-espresso-soda-solarized). 

### Activation

a) After install the theme, launch *Command Palette*

* <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> [macOS](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf): `⇧+⌘+P`
* <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> [Linux](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf): `Ctrl+P`
* <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> [Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf): `Ctrl+P`

b) Type `theme` and choose `Preferences: Color Theme`, then select this theme from the list.

## Customization

You can customize the colors to your liking, overriding the ones provided by this theme or extending them. 
More info [here](https://code.visualstudio.com/docs/getstarted/theme-color-reference). 

For example, the code below in the config.json file *(Preferences > Settings)* will change the CSS tag color to dark green:

```
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": ["entity.name.tag.css", "entity.name.tag.less"],
      "settings": {
        "foreground": "#61862F"
      }
    }
  ]
}
```

The scopes are identified by using *Command Palette > Developer: Inspect TM Scopes*. 

## Contribution

Report issues, bugs to the [issue tracker](https://github.com/BroFox86/solarized-espresso-soda/issues).