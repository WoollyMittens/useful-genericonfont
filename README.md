# genericonfont.js: Embed generic icon fonts

*DEPRICATION WARNING: the functionality in this script has been superceeded / trivialised by updated web standards.*

Make generic icon fonts easy to work with.

## How to include the script

The stylesheet is best included in the header of the document.

```html
<link rel="stylesheet" href="css/genericonfont.css"/>
```

## How to start the script

```scss
@include iconfont($char, $size);
/* attention icon */
@include iconfont('\e9be', 24px);
```

**$char : {Character}** - The hex character code of the icon in the font.

**$size : {Dimensions}** - Dimensions to display the icon at in px, pt, etc.

## License

This work is licensed under a [MIT License](https://opensource.org/licenses/MIT). The latest version of this and other scripts by the same author can be found on [Github](https://github.com/WoollyMittens).

The example Cosmo icon font is &copy; [Icojam](http://www.icojam.com/) and not meant for redistribution.
