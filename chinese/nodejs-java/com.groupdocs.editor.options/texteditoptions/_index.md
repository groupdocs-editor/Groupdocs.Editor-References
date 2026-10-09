---
title: "TextEditOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许指定加载纯文本 TXT 文档的自定义选项"
type: docs
weight: 39
url: /zh/nodejs-java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

允许为加载纯文本（TXT）文档指定自定义选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | 文本文档的字符编码，将用于其 |
打开
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 文本文档的字符编码，将用于其 |
打开
|
|  | [getRecognizeLists()](#getRecognizeLists--) | 允许指定文档中编号列表项的识别方式，当文档是 |
从纯文本格式导入时。
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | 允许指定文档中编号列表项的识别方式，当文档是 |
从纯文本格式导入时。
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | 获取或设置首部空格处理的首选选项。 |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | 获取或设置首部空格处理的首选选项。 |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | 获取或设置尾部空格处理的首选选项。 |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | 获取或设置尾部空格处理的首选选项。 |
|
|  | [getEnablePagination()](#getEnablePagination--) | 允许在生成的 HTML 文档中启用或禁用分页。 |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 允许在生成的 HTML 文档中启用或禁用分页。 |
|
|  | [getDirection()](#getDirection--) | 允许指定输入纯文本的文本流方向 |
文档。
|
|  | [setDirection(int value)](#setDirection-int-) | 允许指定输入纯文本的文本流方向 |
文档。
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


文本文档的字符编码，将用于其
打开


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


文本文档的字符编码，将用于其
打开


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


允许指定文档中编号列表项的识别方式，当文档是
从纯文本格式导入时。默认值为 true。


*** ** * ** ***

如果此选项设置为 false，列表识别算法将在列表编号以点、右括号或项目符号（如 "\\u2022", "\*", "-" 或 "o"）结尾时检测列表段落。如果此选项设置为 true，空白字符也将用作列表编号分隔符：阿拉伯式编号（1., 1.1.2.）的列表识别算法同时使用空白字符和点（".") 符号。

<br />



**Returns:**
布尔
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


允许指定文档中编号列表项的识别方式，当文档是
从纯文本格式导入时。默认值为 true。


*** ** * ** ***

如果此选项设置为 false，列表识别算法将在列表编号以点、右括号或项目符号（如 "\\u2022", "\*", "-" 或 "o"）结尾时检测列表段落。如果此选项设置为 true，空白字符也将用作列表编号分隔符：阿拉伯式编号（1., 1.1.2.）的列表识别算法同时使用空白字符和点（".") 符号。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


获取或设置首部空格处理的首选选项。默认情况下
将首部空格转换为左缩进。


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


获取或设置首部空格处理的首选选项。默认情况下
将首部空格转换为左缩进。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


获取或设置尾部空格处理的首选选项。默认情况下
截断所有尾部空格。


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


获取或设置尾部空格处理的首选选项。默认情况下
截断所有尾部空格。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


允许在生成的 HTML 文档中启用或禁用分页。默认情况下
默认是禁用的（false）。


**Returns:**
布尔
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


允许在生成的 HTML 文档中启用或禁用分页。默认情况下
默认是禁用的（false）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


允许指定输入纯文本的文本流方向
文档。默认情况下为从左到右。


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


允许指定输入纯文本的文本流方向
文档。默认情况下为从左到右。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

