---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Bir Sunum belgesinin meta verilerini temsil eder"
type: docs
weight: 14
url: /tr/java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Bir Sunum belgesinin meta verilerini temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | Bu Sunum belgesinin biçimini döndürür |
|
|  | [getPageCount()](#getPageCount--) | Bu Sunum belgesindeki slayt sayısını döndürür |
|
|  | [getSize()](#getSize--) | Bu Sunum belgesinin bayt cinsinden boyutunu döndürür |
|
|  | [isEncrypted()](#isEncrypted--) | Bu belirli Sunum belgesinin şifrelenip şifrelenmediğini ve açmak için şifre gerekip gerekmediğini gösterir |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Seçilen slaytın bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Bu Sunum belgesinin biçimini döndürür


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Bu Sunum belgesindeki slayt sayısını döndürür


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Bu Sunum belgesinin bayt cinsinden boyutunu döndürür


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bu belirli Sunum belgesinin şifrelenip şifrelenmediğini ve açmak için şifre gerekip gerekmediğini gösterir


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Seçilen slaytın bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | slideIndex | int | İstenen slaytın 0 tabanlı indeksi. 0'dan küçük olamaz, bu sunumdaki slayt sayısını aşamaz. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

