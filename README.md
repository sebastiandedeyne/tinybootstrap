Tiny Bootstrap
=============

A stripped down version of sass-bootstrap containing only the grid system and some responsive utilities. Also added an 'xxs' breakpoint for the grid. 

## Build
```
sass --update sass/_tinybootstrap.scss:tinybootstrap.css --sourcemap=none --style expanded && sass --update sass/_tinybootstrap.scss:tinybootstrap.min.css --sourcemap=none --style compressed
```
