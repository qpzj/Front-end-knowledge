## uni-app学习笔记

### 模板语法

v-bind: 组件属性要使用data中定义的数据变量，或者组件属性要是使用表达式，要使用v-bind指定  简写：

v-on：绑定事件  简写@



### 数据绑定

初始化数据

data一般定义为函数 return一个值回去定义成对象也可以，但是数据不会发生变化不推荐。

v-model：数据双向绑定

### 条件判断

v-if  决定某个内容或者区块是否挂载

v-else-if  多个条件判断

v-else 和v-if成套使用

v-show 条件判断，是否显示

补充：

空标签

```html
<block>
</block>
<!-- vue中有template代替 --> 
<template>
</template>
```

### 列表渲染

v-for  循环渲染

v-for = "(item,index) in arr"  :key = "index"

