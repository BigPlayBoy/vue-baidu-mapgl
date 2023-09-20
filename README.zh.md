# VUE BAIDU MAP

<p align="center">
  <img src="https://dafrok.github.io/vue-baidu-map/favicon.png" width="200px">
</p>
<p align="center">基于 VUE 2.x 的百度地图组件</p>

[![npm](https://img.shields.io/npm/v/vue-baidu-map.svg)]()
[![Travis](https://img.shields.io/travis/Dafrok/vue-baidu-map.svg)]()
[![Package Quality](http://npm.packagequality.com/shield/vue-baidu-map.svg)](http://packagequality.com/#?package=vue-baidu-map)
[![npm](https://img.shields.io/npm/dm/vue-baidu-map.svg)]()
[![license](https://img.shields.io/github/license/dafrok/vue-baidu-map.svg)]()

## Special Instruction

当前包是从Dafrok的vue-baidu-map拷贝过来的，由于原作者一直未维护vue-baidu-map这个包，本人拷贝过来作为个人使用，并将百度地图API更改为3.0

## 语言

- [中文](https://github.com/BigPlayBoy/vue-baidu-mapgl/blob/master/README.zh.md)
- [English](https://github.com/BigPlayBoy/vue-baidu-mapgl/blob/master/README.md)

## 文档

[https://github.com/BigPlayBoy/vue-baidu-mapgl](https://github.com/BigPlayBoy/vue-baidu-mapgl)

## 开始

### 安装

```bash
npm i --save vue-baidu-map
```

### 初始化

```javascript
import Vue from 'vue'
import BaiduMap from 'vue-baidu-map'

Vue.use(BaiduMap, {
  // ak 是在百度地图开发者平台申请的密钥 详见 http://lbsyun.baidu.com/apiconsole/key */
  ak: 'YOUR_APP_KEY'
})
```

### 使用
```vue
<template>
  <baidu-map class="map">
  </baidu-map>
</template>

<style>
/* 地图容器必须设置宽和高属性 */
.map {
  width: 400px;
  height: 300px;
}
</style>
```

## 贡献

[贡献指南](https://github.com/BigPlayBoy/vue-baidu-mapgl/blob/master/CONTRIBUTING.md)


## 协议

[MIT 许可证](https://opensource.org/licenses/MIT)