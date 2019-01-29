# cwise-es-transform

Fork of [cwise-transform](https://github.com/scijs/cwise/blob/master/lib/cwise-transform.js)
with hacked version of [static-module@1.5.0](https://github.com/jpweeks/static-module/tree/cwise-es-transform)
to support ES6 source transforms.

Not pretty, but it works for now.

```sh
npm install @jpweeks/cwise-es-transform
```

```json
{
  "browserify": {
    "transform": [
      "@jpweeks/cwise-es-transform"
    ]
  }
}
```
