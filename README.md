# Frugal

An open-source theme for the [Ghost](https://ghost.org/) blogging platform, ocused on content. Last tested with Ghost v1.25.5.

## Suggested Customizations

* To customize the colors, look for the string "Customize it" in the `assets/css/global.css` file, and you can redefine the value of all the lines concerned.
* To modify the format of the dates in the list of posts, go to line 3 of the file `partials/post_list.hbs`, and line 10 of the file `post.hbs` for the date displayed for a post view.
* If you are not going to post code in your articles, you can delete the assets/css/highlight folder, delete line 16 (CSS) of the default.hbs file and lines 33/34 (JS) of the same file.

## Installation

1. Download the files
2. Add the folder to the content/themes directory of your Ghost installation
3. Select the theme in the settings page of your Ghost admin panel

## Credits

* Syntax highlighter from [highlight.js](http://https://highlightjs.org/)
* SVG icons from [IcoMoon](https://icomoon.io/)

## License

Released under the [MIT License](https://github.com/Julobel/Frugal/blob/master/LICENSE) 