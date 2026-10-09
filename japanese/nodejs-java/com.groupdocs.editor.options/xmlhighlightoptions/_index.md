---
title: "XmlHighlightOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "XML から HTML への変換中に XML のハイライトをカスタマイズできるオプションを含みます。"
type: docs
weight: 53
url: /ja/nodejs-java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

XMLからHTMLへの変換中のXMLハイライトをカスタマイズできるオプションを含みます。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | XML タグ（タグ名を含む山括弧）のフォントを表現する役割を担います。 |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | 属性名のフォントを表現する役割を担います。 |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | 属性値のフォントを表すことを担当します |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | 内部タグテキストのフォントを表すことを担当します |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | HTML コメントのフォントを表すことを担当します（開始タグと終了タグのペアを含む） |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | CDATA セクションのフォントを表すことを担当します（開始タグと終了タグのペアを含む） |
|
|  | [isDefault()](#isDefault--) | この XML ハイライトオプションオブジェクトにデフォルトのフォント設定があるかどうかを判断します |
|
|  | [resetToDefault()](#resetToDefault--) | 現在のフォント設定をデフォルト値にリセットします |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


XML タグ（タグ名を含む山括弧）のフォントを表現する役割を担います。


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


属性名のフォントを表現する役割を担います。


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


属性値のフォントを表すことを担当します


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


内部タグテキストのフォントを表すことを担当します


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


HTML コメントのフォントを表すことを担当します（開始タグと終了タグのペアを含む）


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


CDATA セクションのフォントを表すことを担当します（開始タグと終了タグのペアを含む）


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


この XML ハイライトオプションオブジェクトにデフォルトのフォント設定があるかどうかを判断します


**Returns:**
ブール
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


現在のフォント設定をデフォルト値にリセットします


