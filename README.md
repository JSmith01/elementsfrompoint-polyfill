document.elementsFromPoint polyfill
===================================

This is a simple polyfill for `document.elementsFromPoint` that relies on `document.elementFromPoint` call (that should be supported by browser).
It solves the problem at least for Safari 11.0 that supports only latter.

For documentation on `document.elementsFromPoint` please take a look on [MDN article](https://developer.mozilla.org/en-US/docs/Web/API/DocumentOrShadowRoot/elementsFromPoint).

This polyfill is based on following GitHub gist: https://gist.github.com/iddan/54d5d9e58311b0495a91bf06de661380

Polyfill can be imported as `require 'elementsfrompoint-polyfill';` or with ES6 syntax `import('elementsfrompoint-polyfill');`
