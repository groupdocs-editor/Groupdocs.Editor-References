---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Bir Kelime İşleme belgesinin meta verilerini temsil eder"
type: docs
weight: 17
url: /tr/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Bir Kelime İşleme belgesinin meta verilerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | Bu WordProcessing belgesinin formatını döndürür |
|
|  | [getPageCount()](#getPageCount--) | Sayfa sayısını döndürür |
|
|  | [getSize()](#getSize--) | Bu WordProcessing belgesinin bayt cinsinden boyutunu döndürür |
|
|  | [isEncrypted()](#isEncrypted--) | Bu belirli WordProcessing belgesinin şifrelenip şifrelenmediğini belirler ve |
açmak için şifre gerektirir
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Seçilen sayfanın bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Bu örneğin belirtilen diğerine eşit olup olmadığını belirler |
WordProcessingDocumentInfo örneği
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Bu WordProcessing belgesinin formatını döndürür


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Sayfa sayısını döndürür


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Bu WordProcessing belgesinin bayt cinsinden boyutunu döndürür


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bu belirli WordProcessing belgesinin şifrelenip şifrelenmediğini belirler ve
açmak için şifre gerektirir


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Seçilen sayfanın bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageIndex | int | İstenen sayfanın 0 tabanlı indeksi. 0'dan küçük olamaz, bu WordProcessing belgesindeki sayfa sayısını aşamaz. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Bu örneğin belirtilen diğerine eşit olup olmadığını belirler
WordProcessingDocumentInfo örneği


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Bu ile eşitliği kontrol edilmesi gereken diğer WordProcessingDocumentInfo örneği |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

