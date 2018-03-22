# sample

[muvue issue #161](https://github.com/Meituan-Dianping/mpvue/issues/161)

部分issue描述 在demo的 `src/components/card.vue` 中

## 问题简单描述

> 自定义组件属性默认值问题。

1. 使用组件时，传递了属性，导致默认值失效。
2. 如果在使用组件时，不传递属性，默认值是起作用的。
3. 在进行网络请求时，要显示一个默认值（有时候是数组的长度），导致报错。
