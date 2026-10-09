---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许指定用于生成和保存纯文本 TXT 文档的自定义选项"
type: docs
weight: 41
url: /zh/nodejs-java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

允许指定用于生成和保存纯文本（TXT）的自定义选项
文档

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | 文本文档的字符编码，将用于其 |
保存
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 文本文档的字符编码，将用于其 |
保存
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | 指定是否在每个 BiDi 运行前添加双向标记，当 |
以纯文本格式导出时。
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | 指定是否在每个 BiDi 运行前添加双向标记，当 |
以纯文本格式导出
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | 指定程序是否应尝试保留表格的布局 |
在以纯文本格式保存时。
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | 指定程序是否应尝试保留表格的布局 |
在以纯文本格式保存时。
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


文本文档的字符编码，将用于其
保存


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


文本文档的字符编码，将用于其
保存


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


指定是否在每个 BiDi 运行前添加双向标记，当
以纯文本格式导出。默认值为 'false' \u2014 不添加 BiDi 标记。


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


指定是否在每个 BiDi 运行前添加双向标记，当
以纯文本格式导出


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


指定程序是否应尝试保留表格的布局
在以纯文本格式保存时。默认值为 false。


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


指定程序是否应尝试保留表格的布局
在以纯文本格式保存时。默认值为 false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

