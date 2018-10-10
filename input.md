# Input 输入框
## 概述
基本表单组件
## 代码示例
## API
### props
|属性|说明|类型|默认值|
|:--|:--|:---:|:---:|
|type|声明 input 类型，支持 text,number,email,password,tel|string|text|
|value|表单值，使用v-model绑定|string||
|id|输入框的 id|string||
|placeholder|placeholder 提示|string||
|show-clear|是否显示清除icon|boolean|false|

### events
|事件名|说明|返回值|
|:--|:--|:---:|
|on-enter|按下回车键时触发||
|on-click|设置 icon 属性后，点击图标时触发||
|on-change|数据改变时触发  |event|
|on-focus|输入框聚焦时触发||
|on-blur|输入框失去焦点时触发||

# Tabs 标签页
## 概述
选项卡切换组件
## 代码演示
## API
### Tabs 
#### props
|属性|说明|类型|默认值|
|:--|:--|:---:|:---:|
|line-width|线条宽度|number|1|
|active-color|选中时文字颜色|||
|default-color|默认文字颜色|||
|bar-active-color|设置底部bar颜色|||
|custom-bar-width|设置底部bar宽度，默认宽度是整体tab宽度平分|string、function||


### tab item
#### props
|属性|说明|类型|默认值|
|:--|:--|:---:|:---:|
|active-class|当前项选中时的class|string||
#### events
|事件名|说明|返回值|
|:--|:--|:---:|
|on-item-click|当前 tabItem 被点击时触发||
