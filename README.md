# genericonfont.js: Embed generic icon fonts

Make generic icon fonts easy to work with.

Try the <a href="http://www.woollymittens.nl/default.php?url=useful-genericonfont">demo</a>.

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

## How to build the script

This project uses node.js from http://nodejs.org/

This project uses gulp.js from http://gulpjs.com/

The following commands are available for development:
+ `npm install` - Installs the prerequisites.
+ `gulp import` - Re-imports libraries from supporting projects to `./src/libs/` if available under the same folder tree.
+ `gulp dev` - Builds the project for development purposes.
+ `gulp dist` - Builds the project for deployment purposes.
+ `gulp watch` - Continuously recompiles updated files during development sessions.
+ `gulp serve` - Serves the project on a temporary web server at http://localhost:8500/.
+ `gulp php` - Serves the project on a temporary php server at http://localhost:8500/.

## License

This work is licensed under a [MIT License](https://opensource.org/licenses/MIT). The latest version of this and other scripts by the same author can be found on [Github](https://github.com/WoollyMittens) and at [WoollyMittens.nl](https://www.woollymittens.nl/).

The example Cosmo icon font is &copy; [Icojam](http://www.icojam.com/) and not meant for redistribution.
