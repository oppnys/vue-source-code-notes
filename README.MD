### Vue源码阅读 + 中文注解

> 原文档地址 [README_VUE.md](./README_VUE.md)

#### new Vue({}) 的时候都干了啥

```javascript
const app = new Vue({
  el: '#app',
  data() {
    return {
      msg: 'hello vue',
    }
  }
})
```