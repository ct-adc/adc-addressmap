## AddressMap

> a vue.js component

---
#概述
---
主要用于全国地区数据的操作，包括省，市，区三级联动，地区数据的添加和删除；
在操作地区数据时，以前也用过树形的地区选择组件，但因其在再操作大量的地区数据时，渲染缓慢，所以我们就换了另一种数据展示形式和交互形式，从而就有了这个组件。
>注意：该组件是<code>vue.js</code>组件

---

# demo
---
抢鲜体验请点击这里[demo](www.baidu.com)

---
# API
---
## Props
---
| 参数 | 类型 | 说明 |
| ------- | ---------- | ---------- |
| area  | Array    | 传入组件的地区的数据 |
---
## Events
---
| 事件名 | 参数 | 说明 |
| ------- | -------- | -------- |
| selected | area | 组件中选中的地区 |