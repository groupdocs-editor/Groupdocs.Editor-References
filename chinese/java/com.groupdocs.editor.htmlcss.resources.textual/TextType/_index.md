---
title: "TextType"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示一种可支持的文本资源类型"
type: docs
weight: 12
url: /zh/java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

表示一种可支持的文本资源类型

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextType()](#TextType--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | 特殊值，用于标记未定义、未知或不受支持的文本 |
resource
|
|  | [getCss()](#getCss--) | 文本资源的 CSS 类型 |
|
|  | [getXml()](#getXml--) | 文本资源的 XML 类型 |
|
|  | [getFormalName()](#getFormalName--) | 返回此文本资源类型的正式名称 |
|
|  | [getFileExtension()](#getFileExtension--) | 特定文本的文件扩展名（不含前导点字符） |
resource
|
|  | [getMimeCode()](#getMimeCode--) | 特定文本资源类型的 MIME 代码 |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | 确定此实例是否等于指定的 "TextType" |
实例
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此实例是否等于指定的未强制转换对象， |
它可能是另一个 "TextType" 实例
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | 定义两个特定的 "TextType" 实例是否相等 |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | 定义两个特定的 "TextType" 实例是否不相等 |
|
|  | [hashCode()](#hashCode--) | 返回哈希码，它是此特定值的常数 |
类型
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 返回 TextType 值，它等同于文件扩展名，该扩展名从指定的带扩展名文件名或纯扩展名中提取 |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


特殊值，用于标记未定义、未知或不受支持的文本
resource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


文本资源的 CSS 类型


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


文本资源的 XML 类型


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


返回此文本资源类型的正式名称


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


特定文本的文件扩展名（不含前导点字符）
resource


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


特定文本资源类型的 MIME 代码


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


确定此实例是否等于指定的 "TextType"
实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 其他应与此进行相等比较的 TextType 实例 |
|

**Returns:**
boolean - 如果相等返回 true，否则返回 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此实例是否等于指定的未强制转换对象，
它可能是另一个 "TextType" 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | obj | java.lang.Object | 其他被装箱为对象的 TextType 实例 |
|

**Returns:**
boolean - 如果相等返回 true，否则返回 false

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


定义两个特定的 "TextType" 实例是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 第一个 TextType 实例 |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 第二个 TextType 实例 |
|

**Returns:**
boolean - 如果相等返回 true，否则返回 false

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


定义两个特定的 "TextType" 实例是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 第一个 TextType 实例 |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 第二个 TextType 实例 |
|

**Returns:**
boolean - 如果不相等返回 true，否则返回 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回哈希码，它是此特定值的常数
类型


**Returns:**
int - 有符号 4 字节整数。如果此实例具有默认值则返回 0。

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


返回 TextType 值，它等同于文件扩展名，该扩展名从指定的带扩展名文件名或纯扩展名中提取


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件名 | java.lang.String | 文件名带扩展名，可以是相对路径或绝对路径，或仅仅是扩展名本身 |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

