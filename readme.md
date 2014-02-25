AmdJS
---

`amd.js` is a extreme simple AMD project loader

`amd.min.js` is as small as *1.4k*

all thing `amd.js` can do is to load AMD project like jQuery

demo(todo)

### Usage

index.html

```html
<script src='amd.min.js' data-main='app'></script>
```

app.js

```javascript
define(['jquery/src/jquery'], function($) {
  console.log($.fn.jquery) // @VERSION
})
```

### Notes

CommonJS wrapping has not been implemented

only tested in chrome

[more info about amd](https://github.com/amdjs/amdjs-api/wiki/AMD)
