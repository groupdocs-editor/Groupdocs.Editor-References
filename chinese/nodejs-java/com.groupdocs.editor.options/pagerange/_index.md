---
title: "PageRange"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "封装一个可能具有开放或闭合边界的页面范围。"
type: docs
weight: 27
url: /zh/nodejs-java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

封装一个页面范围，该范围可以具有开放或闭合的边界。默认情况下为“完全开放”——包括所有现有页面。页码从 1 开始，而不是从 0 开始。

<br />

*** ** * ** ***

不可变结构体，封装一个与特定文档无关的页面范围，可用于表示任何文档的页面范围。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [AllPages](#AllPages) | 表示文档的所有现有页面。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | 包含的起始页码，即此页面范围的起始页。 |
|
|  | [getEndNumber()](#getEndNumber--) | 排除的结束页码，页面范围持续到该页之前并在该页结束。 |
|
|  | [getCount()](#getCount--) | 范围内的页码数量。 |
|
|  | [isDefault()](#isDefault--) | 指示此实例是否表示默认的“完全开放”页面范围，即 |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | 检测此 PageRange 实例是否等于指定的范围 |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | 创建一个页面范围，从第一页开始，并具有指定数量的页面 |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | 创建一个页面范围，从指定的页码开始并持续到文档末尾 |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | 创建一个页面范围，从指定的页码开始，具有指定数量的页面，或无限页面数（直到结束） |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | 创建一个页面范围，从指定的页码（包含）开始，并持续到指定的页码（不包含） |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


表示文档中所有现有页面。默认值。


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


包含的起始页码，此页面范围从该页码开始。如果为 1，则页面范围从文档的第一页开始


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


排除的结束页码，此页面范围持续到该页码并在该页码处停止（不包含）。如果为 0，则页面范围延伸至文档末尾


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


范围内的页面数量。如果为 0，则页面范围延伸至文档末尾，无论包含多少页面


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


指示此实例是否表示默认的“完全开放”页面范围，即它包含文档的所有页面


**Returns:**
布尔
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


检测此 PageRange 实例是否等于指定的范围


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | 要检查相等性的其他 PageRange 实例 |
|

**Returns:**
布尔值 - true 表示相等；false 表示不相等

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


创建一个页面范围，从第一页开始，并具有指定数量的页面


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageCount | int | 页面数量，必须严格大于零 |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


创建一个页面范围，从指定的页码开始并持续到文档末尾


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | startPageNumber | int | 页码，页面范围从该页码开始（包含）。页码从 1 开始计数，因此必须严格大于零 |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


创建一个页面范围，从指定的页码开始，具有指定数量的页面，或无限页面数（直到结束）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | startPageNumber | int | 页码，页面范围从该页码开始（包含）。页码从 1 开始计数，因此必须严格大于零 |
|
|  | pageCount | int | 页面数量，必须严格大于零。如果为零，则表示文档结束前的所有页面 |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


创建一个页面范围，从指定的页码（包含）开始，并持续到指定的页码（不包含）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | startPageNumber | int | 页码，页面范围从该页码开始（包含）。页码从 1 开始计数，因此必须严格大于零 |
|
|  | endPageNumber | int | 页码，页面范围持续到该页码（不包含）。页码从 1 开始计数，因此必须严格大于零，并且必须严格大于 startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
