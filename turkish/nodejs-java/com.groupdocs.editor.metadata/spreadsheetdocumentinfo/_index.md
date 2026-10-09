---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Bir Hesap Tablosu belgesinin meta verilerini temsil eder"
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Bir Hesap Tablosu belgesinin meta verilerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | Bu Spreadsheet belgesinin formatını döndürür |
|
|  | [getPageCount()](#getPageCount--) | Sekme sayısını döndürür |
|
|  | [getSize()](#getSize--) | Bu Spreadsheet belgesinin bayt cinsinden boyutunu döndürür |
|
|  | [isEncrypted()](#isEncrypted--) | Bu belirli Spreadsheet belgesinin şifrelenip şifreyle açılması gerekip gerekmediğini gösterir ve |
açılması için parola gerektirir
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Seçilen çalışma sayfasının bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Bu örneğin belirtilen diğer örnek ile eşit olup olmadığını belirler |
SpreadsheetDocumentInfo örneği
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Bu Spreadsheet belgesinin formatını döndürür


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Sekme sayısını döndürür


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Bu Spreadsheet belgesinin bayt cinsinden boyutunu döndürür


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bu belirli Spreadsheet belgesinin şifrelenip şifreyle açılması gerekip gerekmediğini gösterir ve
açılması için parola gerektirir


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Seçilen çalışma sayfasının bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | worksheetIndex | int | İstenen çalışma sayfasının 0 tabanlı indeksi. 0'dan küçük olamaz, bu elektronik tablo içindeki çalışma sayfası sayısını aşamaz. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Bu örneğin belirtilen diğer örnek ile eşit olup olmadığını belirler
SpreadsheetDocumentInfo örneği


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Bu nesneyle eşitlik kontrolü yapılması gereken diğer SpreadsheetDocumentInfo örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

