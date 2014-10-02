Tiny Bootstrap
=============

A stripped down version of sass-bootstrap containing only the grid system and some responsive utilities. Also added an 'tn' breakpoint (smaller than col-xs-*) to the grid. 

## Build
```
sass --update tinybootstrap/_tinybootstrap.scss:tinybootstrap.css --sourcemap=none --style expanded && sass --update tinybootstrap/_tinybootstrap.scss:tinybootstrap.min.css --sourcemap=none --style compressed
```
