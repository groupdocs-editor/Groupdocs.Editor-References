---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许为编辑所有受支持格式（ePub、MOBI 和 AZW3）的电子书文档指定和调整自定义选项。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

允许指定并调整用于编辑所有受支持格式的电子书文档的自定义选项：ePub、MOBI 和 AZW3。

<br />

*** ** * ** ***

支持的电子书格式：

1. [ePub](../https://docs.fileformat.com/ebook/epub/)（电子出版物）
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/)（MobiPocket）
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/)（Kindle 格式 8t）

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | 初始化 [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) 类的新实例，所有选项均设置为默认值 |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | 使用指定的分页模式初始化 [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) 类的新实例 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | 允许在生成的 HTML 文档中启用或禁用分页。 |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 允许在生成的 HTML 文档中启用或禁用分页。 |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | 指定是否将语言信息以 'lang' HTML 属性的形式导出到 HTML 标记中。 |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | 指定是否将语言信息以 'lang' HTML 属性的形式导出到 HTML 标记中。 |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


初始化 [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) 类的新实例，所有选项均设置为默认值


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


使用指定的分页模式初始化 [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) 类的新实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | enablePagination | boolean | 启用 ( true ) 或禁用 ( false ) 生成的 HTML 文档中电子书内容的分页。默认情况下为禁用 ( false )。 |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


允许在生成的 HTML 文档中启用或禁用分页。默认情况下为禁用 (
false
).

<br />

*** ** * ** ***

本质上，大多数电子书格式内部是类似 Office Open XML 的流式格式，内容是连续的，划分为章节而不是页面。然而，它包含一些特定于页面的信息，如页码、脚注、页眉/页脚等。某些电子书阅读器会将电子书内容拆分为页面，而其他阅读器（尤其是移动端） \\u2014 不会。此选项允许控制在编辑时电子书内容在 HTML/CSS 中的呈现方式 \\u2014 浮动视图 ( false ) 或分页视图 ( true )。

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


允许在生成的 HTML 文档中启用或禁用分页。默认情况下为禁用 (
false
).

<br />

*** ** * ** ***

本质上，大多数电子书格式内部是类似 Office Open XML 的流式格式，内容是连续的，划分为章节而不是页面。然而，它包含一些特定于页面的信息，如页码、脚注、页眉/页脚等。某些电子书阅读器会将电子书内容拆分为页面，而其他阅读器（尤其是移动端） \\u2014 不会。此选项允许控制在编辑时电子书内容在 HTML/CSS 中的呈现方式 \\u2014 浮动视图 ( false ) 或分页视图 ( true )。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


指定是否将语言信息以 'lang' HTML 属性的形式导出到 HTML 标记中。
此选项可能对多语言文档的往返转换有用。默认情况下它是禁用的 (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


指定是否将语言信息以 'lang' HTML 属性的形式导出到 HTML 标记中。
此选项可能对多语言文档的往返转换有用。默认情况下它是禁用的 (
false
).


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

