# Tiny Bootstrap

A stripped down version of sass-bootstrap containing only the grid system and some responsive utilities. 

## Extra Features

### 24-column grid
The default grid is now 24 columns instead of 12.

### .no-gutter

Class that can be added to an element above your columns to set the gutter to 0.

### New Breakpoint: 'tn'
Added a 'tn' breakpoint which is between col-xs-* and col-sm-*. Also works with the responsive utilities.

### Breakpoints Mixin
A mixin to easily add breakpoints in your sass code.

```
.class {
  @include breakpoint(tn|sm|md|lg) {
    // ...
  }
}
```

## Build

```
sass --update tinybootstrap/_tinybootstrap.scss:dist/tinybootstrap.css --sourcemap=none --style expanded && sass --update tinybootstrap/_tinybootstrap.scss:dist/tinybootstrap.min.css --sourcemap=none --style compressed
```
