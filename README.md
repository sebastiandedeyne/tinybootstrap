# Tiny Bootstrap

A stripped down version of sass-bootstrap containing only the grid system and some responsive utilities. 

## Extra Features

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
sass --update tinybootstrap/_tinybootstrap.scss:tinybootstrap.css --sourcemap=none --style expanded && sass --update tinybootstrap/_tinybootstrap.scss:tinybootstrap.min.css --sourcemap=none --style compressed
```
