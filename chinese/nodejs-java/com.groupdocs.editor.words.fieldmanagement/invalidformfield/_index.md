---
title: "InvalidFormField"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示在 FormFieldManager.FixInvalidFormFieldNames 操作期间对无效表单字段名称的更新。"
type: docs
weight: 18
url: /zh/nodejs-java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

表示在期间对无效表单字段名称的更新
FormFieldManager.FixInvalidFormFieldNames
操作。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | 使用指定的名称初始化 [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 获取表单字段的原始名称，该名称在外部无法修改 |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | 获取或设置修复后表单字段的新名称。 |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | 获取或设置修复后表单字段的新名称。 |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


使用指定的名称初始化 [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 表单字段的原始名称。 |
|

### getName() {#getName--}
```
public final String getName()
```


获取表单字段的原始名称，该名称在外部无法修改
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


获取或设置修复后表单字段的新名称。
此名称消除与其他表单字段的重复唯一标识符，并设置唯一的书签名称。

<br />

*** ** * ** ***

```
 FixedName = String.format("%s_fixed", name); // as default value.
 
```

<br />



**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


获取或设置修复后表单字段的新名称。
此名称消除与其他表单字段的重复唯一标识符，并设置唯一的书签名称。

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

