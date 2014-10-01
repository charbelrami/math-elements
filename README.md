# math-elements

## Getting started

### Installation

#### Bower

```sh
$ bower install --save math-elements
```

### Usage

```html
<!doctype html>
<html>
  <head>
    <script src="bower_components/platform/platform.js"></script>
    <link rel="import" href="bower_components/math-elements/math.html">
  </head>
  <body>
    <math-elements></math-elements>
  </body>
</html>
```

## Reference

name | polymer-element | attributes | default values
---- | --------------- | ---------- | --------------
main container | math-elements | |
element | math-el | |
italic | math-i | |
superscript | math-super | |
subscript | math-sub | |
superscript-subscript | math-super-sub | |
fraction | math-frac | |
brackets | math-brack | l, r | l: '(', r: ')'
limit | math-lim | v, p | v: 'x', p: 'a'
derivative | math-deriv | v | v: 'x'
partial derivative | math-par-deriv | v | v: 'x'
integral | math-inte | v | v: 'x'
definite integral | math-def-inte | ll, ul, v | ll: 'a', ul: 'b', v: 'x'
sum | math-sum | ll, ul, i | ll: 'm', ul: 'n', i: 'i'
product | math-prod | ll, ul, i | ll: 'm', ul: 'n', i: 'i'
matrix | math-matrix | |
matrix row | math-row | |

* l = left
* r = right
* v = variable
* p = point
* ll = lower limit
* ul = upper limit
* i = index

## License

MIT © 2014 [Charbel Rami](https://twitter.com/CharbelRami)
