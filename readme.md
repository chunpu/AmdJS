AmdJS
---

`amd.js` is a extreme simple [AMD](https://github.com/amdjs/amdjs-api/wiki/AMD) project loader

`amd.min.js` is as small as *1.4k*

all things `amd.js` can do are to load AMD project like jQuery

demo (todo)

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

[more info about Amd](https://github.com/amdjs/amdjs-api/wiki/AMD)
