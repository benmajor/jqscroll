# JQScroll

JQScroll is a simple jQuery plugin that can be used as a drop-in for native vertical scrolling of elements. It uses the built-in browser scrolling behaviour, and just wraps this in various elements that can in turn be styled using CSS. The project is still a work-in-progress, as it was developed for another major project I was working on out of necessity. 

The approach used here isn't ground-breaking - it's been used by other companies to great effect for a long time (read Facebook, etc.), but this is a simple wrapper that can be included in any project. 

For better functionality, it also includes the jQuery `resize()` event courtesy of the awesome Ben Alman.

---

### Usage:

Simply include `jqscroll.min.js` and `jqscroll.css` into your project, and initialise the plugin like you would any other jQuery plugin:

```javascript
$(function() {
    $('#myScroller').jqscroll();
})
```

### Limitations:

There are a few limitations which will be ironed out if there is enough interest in this project:

- Currently only supports vertical scrolling; no support for horizontal
- Does not support drag to scroll.



