---
title: React 下拉选择器组件
components: 下拉选择器，原生的选择器
---
# 下拉选择器

<p class="description">下拉选择器组件用于从选项列表中去获得用户所提供的信息。</p>

## 简单下拉选择器

菜单位于其所点击的元素上, 使得当前选定的菜单项显示在点击元素上。

{{"演示": "pages/demos/selects/SimpleSelect.js"}}

## 原生的下拉选择器

由于可以使用平台的原生选择在移动设备上改进用户体验，我们允许这种模式。

{{"演示": "pages/demos/selects/NativeSelects.js"}}

## 多选

`Select`组件可以处理多个选择，可以使用`multiple` 属性启用

与单项选择一样，您可以通过访问` onChange `属性中的回调` event.target.value `来提取新值。它总是一个数组。

{{"demo": "pages/demos/selects/MultipleSelect.js"}}

## With a Dialog

While it's discouraged by the Material Design specification, you can use a select inside a dialog.

{{"demo": "pages/demos/selects/DialogSelect.js"}}

## Text Fields

The `TextField` wrapper component is a complete form control including a label, input and help text. You can find an example with the select mode [in this section](/demos/text-fields/#textfield).

## Controlled open Select

{{"demo": "pages/demos/selects/ControlledOpenSelect.js"}}