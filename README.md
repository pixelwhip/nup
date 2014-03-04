nup
===

Sass mixin for making simple grids of elements.

## Basic Usage

``` scss
@import 'nup.scss';

$columns: 3;
$gutters: 5%;

ul {
  @include nup-container
}

li {
  @include nup-item-base;
  @include nup-item;
}
```

This will layout your list items in 3 equal columns with gutters 5% of the width of the ul element.  Gutters can be defined in any CSS width unit.

See inline comments for more advanced usage.
