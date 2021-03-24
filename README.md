# Bulb-UI

![npm](https://img.shields.io/npm/v/bulb-vue-ui)
## 介绍

Bulb-UI 是一个基于 Vue 的 UI 组件库，目前包括有 Button、Tabs、Input、Grid、
Layout、Toast、Collapse、Popover 组件。

## 开始使用

1. 添加 CSS 样式

使用本框架前，请在 CSS 中开启 border-box

```css
*,*::before,*::after{box-sizing: border-box;}
```

IE 8 及以上浏览器都支持此样式。

2. 安装 bulb-vue-ui

```bash
npm i --save bulb-vue-ui
```

3. 引入 bulb-vue-ui

```js
import {Button, ButtonGroup, Icon} from 'bulb-vue-ui'
import 'bulb-vue-ui/dist/index.css'

export default {
  name: 'app',
  components: {
    'i-button': Button,
    'i-icon': Icon
  }
}
```
## 文档

[前往官网](https://yixin300.github.io/bulb-vue-ui/)
