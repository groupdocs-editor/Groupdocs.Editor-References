---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "XML'den HTML'ye dönüşüm sırasında XML vurgulamasını özelleştirmeye izin veren seçenekleri içerir"
type: docs
weight: 53
url: /tr/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

XML'den HTML'ye dönüşüm sırasında XML vurgulamasını özelleştirmeye izin veren seçenekleri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | XML etiketlerinin (etiket adlarıyla açılı köşeli parantezler) yazı tipini temsil etmekten sorumludur |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Öznitelik adlarının yazı tipini temsil etmekten sorumludur |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Öznitelik değerlerinin yazı tipini temsil etmekten sorumludur |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | İç etiket metninin yazı tipini temsil etmekten sorumludur |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | HTML yorumlarının (açılış ve kapanış etiket çiftini içeren) yazı tipini temsil etmekten sorumludur |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | CDATA bölümlerinin (açılış ve kapanış etiket çiftini içeren) yazı tipini temsil etmekten sorumludur |
|
|  | [isDefault()](#isDefault--) | Bu XML Vurgulama seçenekleri nesnesinin varsayılan yazı tipi ayarlarına sahip olup olmadığını belirler |
|
|  | [resetToDefault()](#resetToDefault--) | Mevcut yazı tipi ayarlarını varsayılan değerlerine sıfırlar |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


XML etiketlerinin (etiket adlarıyla açılı köşeli parantezler) yazı tipini temsil etmekten sorumludur


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Öznitelik adlarının yazı tipini temsil etmekten sorumludur


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Öznitelik değerlerinin yazı tipini temsil etmekten sorumludur


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


İç etiket metninin yazı tipini temsil etmekten sorumludur


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


HTML yorumlarının (açılış ve kapanış etiket çiftini içeren) yazı tipini temsil etmekten sorumludur


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


CDATA bölümlerinin (açılış ve kapanış etiket çiftini içeren) yazı tipini temsil etmekten sorumludur


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bu XML Vurgulama seçenekleri nesnesinin varsayılan yazı tipi ayarlarına sahip olup olmadığını belirler


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Mevcut yazı tipi ayarlarını varsayılan değerlerine sıfırlar


