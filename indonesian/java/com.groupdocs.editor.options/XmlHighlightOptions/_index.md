---
title: "XmlHighlightOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Berisi opsi yang memungkinkan penyesuaian penyorotan XML selama konversi XML-ke-HTML"
type: docs
weight: 53
url: /id/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Berisi opsi yang memungkinkan menyesuaikan penyorotan XML selama konversi XML-ke-HTML.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Bertanggung jawab untuk merepresentasikan font tag XML (kurung sudut dengan nama tag) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Bertanggung jawab untuk merepresentasikan font nama atribut |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Bertanggung jawab untuk merepresentasikan font nilai atribut |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Bertanggung jawab untuk merepresentasikan font teks dalam tag |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Bertanggung jawab untuk merepresentasikan font komentar HTML (termasuk pasangan tag pembuka dan penutup) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Bertanggung jawab untuk merepresentasikan font bagian CDATA (termasuk pasangan tag pembuka dan penutup) |
|
|  | [isDefault()](#isDefault--) | Menentukan apakah objek opsi XML Highlight ini memiliki pengaturan font default |
|
|  | [resetToDefault()](#resetToDefault--) | Mengatur ulang pengaturan font saat ini ke nilai defaultnya |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Bertanggung jawab untuk merepresentasikan font tag XML (kurung sudut dengan nama tag)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Bertanggung jawab untuk merepresentasikan font nama atribut


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Bertanggung jawab untuk merepresentasikan font nilai atribut


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Bertanggung jawab untuk merepresentasikan font teks dalam tag


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Bertanggung jawab untuk merepresentasikan font komentar HTML (termasuk pasangan tag pembuka dan penutup)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Bertanggung jawab untuk merepresentasikan font bagian CDATA (termasuk pasangan tag pembuka dan penutup)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Menentukan apakah objek opsi XML Highlight ini memiliki pengaturan font default


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Mengatur ulang pengaturan font saat ini ke nilai defaultnya


