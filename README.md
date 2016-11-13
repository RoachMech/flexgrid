# Flexgriddle
[![Build Status](https://travis-ci.org/RoachMech/flexgrid.svg?branch=master)](https://travis-ci.org/RoachMech/flexgrid)
[![npm version](https://badge.fury.io/js/flexgriddle.svg)](https://badge.fury.io/js/flexgriddle)


A sass mixin library for creating simple grids using flexbox

## Install
```cli
npm install --save flexgriddle
```

## Usage
This library consists of two mixins which enable you to make a simple grid using `flexbox`.

### Specify the grid container
```scss
.gallery {
  @include flexgrid-container();
}
```
Argument:
- __$gutter__ _Optional_. Size of the gutter.

### Specify the grid items
```scss
.gallery__item {
  @include flexgrid-item(5);
}
```
Arguments:
- __$number-of-items__. The number of items that one row will contain.
- __$gutter__ _Optional_. Size of the gutter. Should be the same as its container gutter size.

## License
MIT