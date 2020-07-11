# vcolorpicker-ui

## 安装
```
npm install vcolorpicker-ui -S
```

### 使用
```
在 main.js 文件中引入插件并注册ui

import vcolorpicker from 'vcolorpicker-ui'
Vue.use(vcolorpicker)

```

### 在项目中使用 vcolorpicker-ui
```
<template>
  <colorPicker v-model="color" />
</template>
<script>
  export default {
    data () {
      return {
        color: '#ff0000'
      }
    }
  }
</script>

```

### 特点
```
简单易用，UI在原插件基础上优化增加了圆角和过渡动画
提供以 npm 的形式安装提供全局组件
在支持 html5 input[type='color'] 的浏览器实现了「更多颜色」的功能

```

### 选项
```
你可以通过在所在的元素上设置以下属性来配置color-picker

defaultColor：默认颜色，如defaultColor="#ff0000"
disabled：禁用状态，如disabled=true

```

### 事件
change颜色值改变的时候触发

```
<colorPicker v-model="color" v-on:change="headleChangeColor" />

```
