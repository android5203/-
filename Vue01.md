# 基础
### 1. MVVM框架

1. model &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;数据（提供）
2. view &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;界面 模板（提供）
3. viewModel &nbsp;连接模板和数据（自动处理数据和模板之间的关系）


### 2. 插值表达式
语法：
```html
<div>
  <h1> {{title}} </h1>
</div>
```

# 指令

__指令集__

指令名称 | 作用 | 备注
---|--- | ---
v-model | 双向数据绑定 |  |
v-for | 循环 | v-fot="(item, index) in arr" |
v-show | 隐藏与显示；根据条件来决定是否要显示该模板的内容 | 不会从 dom 移除元素，通过display: none 控制显示与隐藏
v-if | 隐藏与显示 | 从dom元素中移除
v-bind | 绑定数据 | 在dom属性中直接使用 data 中的值是不行的，必须绑定之后才能使用 缩写:`:`
v-on | 事件绑定 | 缩写：`@` 
v-text | 更新元素中的值 | 和插值表达式表现一致 
v-html | 更新元素的HTML | 注意：内容按普通 HTML 插入 - 不会作为 Vue 模板进行编译 
v-else | | 
v-else-if | |


__Vue指令笔记__

[点击打开笔记](https://blog.csdn.net/qq_39125684/article/details/87870383)































<br />
<br />
<br />
<br />
