---
title: React 下拉选择器组件
components: 下拉选择器，原生的选择器
---
# 下拉选择器

<p class="description">下拉选择器组件用于从选项列表中去获得用户所提供的信息。</p>

## 下拉选择器演示

Menus are positioned over their emitting elements such that the currently selected menu item appears on top of the emitting element.

{{"demo": "pages/demos/selects/SimpleSelect.js"}}

## Native Select

As the user experience can be improved on mobile using the native select of the platform, we allow such pattern.

{{"demo": "pages/demos/selects/NativeSelects.js"}}

## Multiple Select

The `Select` component can handle multiple selections. It's enabled with the `multiple` property.

Like with the single selection, you can pull out the new value by accessing `event.target.value` in the `onChange` callback. It's always an array.

{{"demo": "pages/demos/selects/MultipleSelect.js"}}

## With a Dialog

While it's discouraged by the Material Design specification, you can use a select inside a dialog.

{{"demo": "pages/demos/selects/DialogSelect.js"}}

## Text Fields

The `TextField` wrapper component is a complete form control including a label, input and help text. You can find an example with the select mode [in this section](/demos/text-fields/#textfield).

## Controlled open Select

{{"demo": "pages/demos/selects/ControlledOpenSelect.js"}}