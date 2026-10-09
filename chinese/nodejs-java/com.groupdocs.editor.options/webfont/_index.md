---
title: "WebFont"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示用于 Web 的字体设置。"
type: docs
weight: 43
url: /zh/nodejs-java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

表示用于 Web 的字体设置。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getColor()](#getColor--) | ARGB32 格式的字体颜色 |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | ARGB32 格式的字体颜色 |
|
|  | [getWeight()](#getWeight--) | 设置字体的粗细（或加粗程度） |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | 设置字体的粗细（或加粗程度） |
|
|  | [getStyle()](#getStyle--) | 设置字体是否应使用其字体系列中的常规、斜体或倾斜体样式。 |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 设置字体是否应使用其字体系列中的常规、斜体或倾斜体样式。 |
|
|  | [getLine()](#getLine--) | 设置应用于文本的线条或线条组合 |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 设置应用于文本的线条或线条组合 |
|
|  | [getSize()](#getSize--) | 设置字体的大小（以绝对或相对单位） |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | 设置字体的大小（以绝对或相对单位） |
|
|  | [getName()](#getName--) | 设置字体名称。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 设置字体名称。 |
|
|  | [deepClone()](#deepClone--) | 创建并返回此 [WebFont](../../com.groupdocs.editor.options/webfont) 实例的完整深拷贝 |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | 确定此 WebFont 实例是否等于指定的对象 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此 WebFont 实例是否等于指定的未强制转换对象 |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


ARGB32 格式的字体颜色


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


ARGB32 格式的字体颜色


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


设置字体的粗细（或加粗程度）


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


设置字体的粗细（或加粗程度）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


设置字体是否应使用其字体系列中的常规、斜体或倾斜体样式。


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


设置字体是否应使用其字体系列中的常规、斜体或倾斜体样式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


设置应用于文本的线条或线条组合


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


设置应用于文本的线条或线条组合


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


设置字体的大小（以绝对或相对单位）


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


设置字体的大小（以绝对或相对单位）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


设置字体名称。如果未指定，将使用默认字体


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


设置字体名称。如果未指定，将使用默认字体


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


创建并返回此 [WebFont](../../com.groupdocs.editor.options/webfont) 实例的完整深拷贝


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


确定此 WebFont 实例是否等于指定的对象


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | 另一个用于检查相等性的 WebFont，可能为 NULL |
|

**Returns:**
布尔值 - 相等为 true，不相等为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此 WebFont 实例是否等于指定的未强制转换对象


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | obj | java.lang.Object | 对象，预期为一个 [WebFont](../../com.groupdocs.editor.options/webfont) 实例 |
|

**Returns:**
布尔值 - 相等为 true，不相等为 false

