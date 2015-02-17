mouse-wheel
===========
Easy top 

# Example

```javascript
require('mouse-wheel')(function(dx, dy) {
  document.body.innerHTML = '<p>Scroll:' + [dx,dy] + '</p>'
})
```

# Install

```
npm i mouse-wheel
```

# API

#### `require('mouse-wheel')(element, callback, noScroll)`
Hook an event handler for the mouse wheel on `element`.

* `element` is an optional DOM element, or if unspecified then is the window object.
* `callback(dx, dy, dz)` is called whenever the mouse scrolls
    + `dx, dy, dz` is the amount of scrolling vertically, horizontally and depth-wise in pixels
* `noScroll` is an optional flag, which if set disables scrolling the page

# License
(c) 2015 Mikola Lysenko. MIT License