## Layout 布局

通过 24 分栏，迅速简便地创建布局。

### 基础布局

使用分栏创建基础的栅格布局。
:::demo 通过 row 和 col 组件，并通过 col 组件的 `span` 属性我们就可以自由地组合布局。

```html
<will-row>
  <will-col :span="24">
    <div class="grid-content bg-purple-dark"></div
  ></will-col>
</will-row>
<style>
  .bg-purple-dark {
    background: #0966e9;
  }
</style>
```

:::

### Row 属性

| 参数   | 说明     | 类型   | 可选值 | 默认值 |
| ------ | -------- | ------ | ------ | ------ |
| gutter | 栅格间隔 | number | —      | 0      |

### col 属性

| 参数   | 说明               | 类型   | 可选值 | 默认值 |
| ------ | ------------------ | ------ | ------ | ------ |
| span   | 元素占据的列数     | number | —      | 2      |
| offset | 元素左侧的间隔格数 | number | —      | 0      |
| push   | 元素向右移动格数   | number | —      | 0      |
| pull   | 元素向左移动格数   | number | —      | 0      |
