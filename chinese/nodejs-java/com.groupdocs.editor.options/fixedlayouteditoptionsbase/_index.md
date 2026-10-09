---
title: "FixedLayoutEditOptionsBase"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "所有固定布局格式（如 PDF 和 XPS）文档选项的基抽象类。"
type: docs
weight: 16
url: /zh/nodejs-java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

所有固定布局格式（如 PDF 和 XPS）文档选项的基抽象类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | 获取或设置指示在将输入的固定布局文档转换为生成的 HTML 时是否必须跳过图像的标志。 |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | 获取或设置指示在将输入的固定布局文档转换为生成的 HTML 时是否必须跳过图像的标志。 |
|
|  | [getPages()](#getPages--) | 允许设置要处理的页码范围。 |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | 允许设置要处理的页码范围。 |
|
|  | [getEnablePagination()](#getEnablePagination--) | 允许在生成的 HTML 文档中启用（true）或禁用（false）分页。 |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 允许在生成的 HTML 文档中启用（true）或禁用（false）分页。 |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


获取或设置指示在将输入的固定布局文档转换为生成的 HTML 时是否必须跳过图像的标志。默认值为 false——图像将被保留。


**Returns:**
布尔
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


获取或设置指示在将输入的固定布局文档转换为生成的 HTML 时是否必须跳过图像的标志。默认值为 false——图像将被保留。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


允许设置要处理的页码范围。默认情况下，将处理固定布局文档的所有页面。


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


允许设置要处理的页码范围。默认情况下，将处理固定布局文档的所有页面。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


允许在生成的 HTML 文档中启用（true）或禁用（false）分页。默认情况下为禁用（false）。

<br />

*** ** * ** ***

固定布局格式的文档（尤其是 PDF 和 XPS）本质上是严格分页的，其内容具有固定布局并划分为页面。但生成的可编辑 HTML 可以以无页或分页视图的形式呈现。

<br />



**Returns:**
布尔
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


允许在生成的 HTML 文档中启用（true）或禁用（false）分页。默认情况下为禁用（false）。

<br />

*** ** * ** ***

固定布局格式的文档（尤其是 PDF 和 XPS）本质上是严格分页的，其内容具有固定布局并划分为页面。但生成的可编辑 HTML 可以以无页或分页视图的形式呈现。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

