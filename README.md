# VUE BAIDU MAP

<p align="center">
  <img src="https://dafrok.github.io/vue-baidu-map/favicon.png" width="200px">
</p>
<p align="center">Baidu Map components for Vue 2.x</p>
## Special Instruction

The current package is copied from the Vue-Baidu-Map of [Dafrok](https://github.com/Dafrok/vue-baidu-map). Since the original author has not maintained the Vue-Baidu-Map package, I copied it for personal use and changed the BAIDU Map API to 3.0


[![npm](https://img.shields.io/npm/v/vue-baidu-map.svg)]()
[![Travis](https://img.shields.io/travis/Dafrok/vue-baidu-map.svg)]()
[![Package Quality](http://npm.packagequality.com/shield/vue-baidu-map.svg)](http://packagequality.com/#?package=vue-baidu-mapgl)
[![npm](https://img.shields.io/npm/dm/vue-baidu-map.svg)]()
[![license](https://img.shields.io/github/license/dafrok/vue-baidu-map.svg)]()

## Languages

- [中文](https://github.com/BigPlayBoy/vue-baidu-mapgl/blob/main/README.zh.md)
- [English](https://github.com/BigPlayBoy/vue-baidu-mapgl/blob/main/README.md)

## Documentation

[https://github.com/BigPlayBoy/vue-baidu-mapgl](https://github.com/BigPlayBoy/vue-baidu-mapgl)

## Get Start

### Installation

```bash
npm i --save vue-baidu-map
```

### Initialization

```javascript
import Vue from 'vue'
import BaiduMap from 'vue-baidu-map'

Vue.use(BaiduMap, {
  /* Visit http://lbsyun.baidu.com/apiconsole/key for details about app key. */
  ak: 'YOUR_APP_KEY'
})
```

### Usage

```vue
<template>
  <baidu-map class="map">
  </baidu-map>
</template>

<style>
/* The container of BaiduMap must be set width & height. */
.map {
  width: 100%;
  height: 300px;
}
</style>
```

## Contributing

[Contributing Guide](https://github.com/BigPlayBoy/vue-baidu-mapgl/blob/master/CONTRIBUTING.md)


## License

[MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2023-present