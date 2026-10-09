---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许为将实例保存为 HTML 格式指定自定义选项"
type: docs
weight: 19
url: /zh/nodejs-java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

允许为将 [EditableDocument](../../com.groupdocs.editor/editabledocument) 实例保存为 HTML 格式指定自定义选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | 控制 HTML 标记名称在 HTML 标记中的呈现方式：全部小写（默认值）、全部大写或首字母大写 |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | 控制 HTML 标记名称在 HTML 标记中的呈现方式：全部小写（默认值）、全部大写或首字母大写 |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | 控制在 HTML 元素的属性值周围使用哪种分隔符：单引号（默认值）或双引号 |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | 控制在 HTML 元素的属性值周围使用哪种分隔符：单引号（默认值）或双引号 |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | 控制 CSS 样式表的存储位置：作为外部资源 ( |
false
)，或将其嵌入 HTML 标记中，位于 HTML-\>HEAD 部分的 STYLE 元素内 (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | 控制 CSS 样式表的存储位置：作为外部资源 ( |
false
)，或将其嵌入 HTML 标记中，位于 HTML-\>HEAD 部分的 STYLE 元素内 (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | 接口，必须由最终用户实现，以保存所有外部 HTML 资源 |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | 接口，必须由最终用户实现，以保存所有外部 HTML 资源 |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


控制 HTML 标记名称在 HTML 标记中的呈现方式：全部小写（默认值）、全部大写或首字母大写


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


控制 HTML 标记名称在 HTML 标记中的呈现方式：全部小写（默认值）、全部大写或首字母大写


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


控制在 HTML 元素的属性值周围使用哪种分隔符：单引号（默认值）或双引号


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


控制在 HTML 元素的属性值周围使用哪种分隔符：单引号（默认值）或双引号


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


控制 CSS 样式表的存储位置：作为外部资源 (
false
)，或将其嵌入 HTML 标记中，位于 HTML-\>HEAD 部分的 STYLE 元素内 (
true
)


**Returns:**
布尔
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


控制 CSS 样式表的存储位置：作为外部资源 (
false
)，或将其嵌入 HTML 标记中，位于 HTML-\>HEAD 部分的 STYLE 元素内 (
true
)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


接口，必须由最终用户实现，以保存所有外部 HTML 资源


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


接口，必须由最终用户实现，以保存所有外部 HTML 资源


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

