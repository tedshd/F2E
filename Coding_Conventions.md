## Coding Conventions

### HTML

* put id first class second...
    * 1.id
    * 2.class
    * 3.src, href...(require attribute)
    * 4.data attribute
    * 5.other...
    * example: `<div id="id_data" class="class_1 class_2" data-attr="data"></div>`

* `class` or `id` naming
    * use `_` split word
    * example: `play_video`

### CSS

* property and value must has a space
    * example: `color: #fff;`

### JavaScript

* follow jsHint / jsLint
* variable naming - **lower camel case**
    * example: `playVideo`
* DOM object naming - add `dom` to first
    * example: `domButtonCancel`
* jQuery object add `$` first
    * example: `$var`

### IMG

* file name - `ico_<name>_<size>x<size>.png`
    * use for img
* file name - `bg_<name>_<size>x<size>.png`
    * use for CSS background

### PHP

* include php file name add `_` in first
    * example: `_mod_module.blane.php`
