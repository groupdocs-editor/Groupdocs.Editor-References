---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "包含用于在 XML 转 HTML 转换期间自定义 XML 高亮显示的选项"
type: docs
weight: 53
url: /zh/nodejs-java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

包含允许在 XML 转换为 HTML 过程中自定义 XML 高亮显示的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | 负责表示 XML 标签（带标签名的尖括号）的字体 |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | 负责表示属性名的字体 |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | 负责表示属性值的字体 |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | 负责表示内部标签文本的字体 |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | 负责表示 HTML 注释的字体（包括成对的开始和结束标签） |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | 负责表示 CDATA 区段的字体（包括成对的开始和结束标签） |
|
|  | [isDefault()](#isDefault--) | 确定此 XML 高亮选项对象是否具有默认字体设置 |
|
|  | [resetToDefault()](#resetToDefault--) | 将当前字体设置重置为默认值 |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


负责表示 XML 标签（带标签名的尖括号）的字体


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


负责表示属性名的字体


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


负责表示属性值的字体


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


负责表示内部标签文本的字体


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


负责表示 HTML 注释的字体（包括成对的开始和结束标签）


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


负责表示 CDATA 区段的字体（包括成对的开始和结束标签）


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


确定此 XML 高亮选项对象是否具有默认字体设置


**Returns:**
布尔
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


将当前字体设置重置为默认值


