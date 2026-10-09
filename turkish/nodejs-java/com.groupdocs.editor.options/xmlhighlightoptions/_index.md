---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "XML vurgulamasını XML'den HTML'ye dönüşüm sırasında özelleştirmeye izin veren seçenekleri içerir."
type: docs
weight: 53
url: /tr/nodejs-java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

XML'den HTML'ye dönüşüm sırasında XML vurgulamasını özelleştirmeyi sağlayan seçenekleri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | XML etiketlerinin (etiket adlarıyla açılı köşeli parantezler) yazı tipini temsil etmekten sorumludur. |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Özellik adlarının yazı tipini temsil etmekten sorumludur. |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Özellik değerlerinin yazı tipini temsil etmekten sorumludur. |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | İç etiket metninin yazı tipini temsil etmekten sorumludur. |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | HTML yorumlarının (açılış ve kapanış etiket çiftini içeren) yazı tipini temsil etmekten sorumludur. |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | CDATA bölümlerinin (açılış ve kapanış etiket çiftini içeren) yazı tipini temsil etmekten sorumludur. |
|
|  | [isDefault()](#isDefault--) | Bu XML Vurgulama seçenekleri nesnesinin varsayılan yazı tipi ayarlarına sahip olup olmadığını belirler. |
|
|  | [resetToDefault()](#resetToDefault--) | Mevcut yazı tipi ayarlarını varsayılan değerlerine sıfırlar. |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


XML etiketlerinin (etiket adlarıyla açılı köşeli parantezler) yazı tipini temsil etmekten sorumludur.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Özellik adlarının yazı tipini temsil etmekten sorumludur.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Özellik değerlerinin yazı tipini temsil etmekten sorumludur.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


İç etiket metninin yazı tipini temsil etmekten sorumludur.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


HTML yorumlarının (açılış ve kapanış etiket çiftini içeren) yazı tipini temsil etmekten sorumludur.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


CDATA bölümlerinin (açılış ve kapanış etiket çiftini içeren) yazı tipini temsil etmekten sorumludur.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bu XML Vurgulama seçenekleri nesnesinin varsayılan yazı tipi ayarlarına sahip olup olmadığını belirler.


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Mevcut yazı tipi ayarlarını varsayılan değerlerine sıfırlar.


