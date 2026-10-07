---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Bir Markdown belgesinin meta verilerini temsil eder"
type: docs
weight: 13
url: /tr/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Bir Markdown belgesinin meta verilerini temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | Bu Markdown belgesinin biçimini döndürür \u2014 her zaman |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Sayfa sayısını döndürür. |
|
|  | [getSize()](#getSize--) | Bu Markdown belgesinin bayt cinsinden boyutunu döndürür. |
|
|  | [isEncrypted()](#isEncrypted--) | Markdown belgeleri şifreyle şifrelenemediği için, bu |
özellik her zaman 'false' döndürür
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Bu örneğin belirtilen diğerine eşit olup olmadığını belirler |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Bu Markdown belgesinin biçimini döndürür \u2014 her zaman
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Sayfa sayısını döndürür. Markdown belgeleri genellikle sabit sayfalara sahip değildir
ve bu nedenle sayfa sayısı, bu sayı standart sayfa boyutundan hesaplanır
dikey yönde A4 olarak ayarlanmıştır.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Bu Markdown belgesinin bayt cinsinden boyutunu döndürür.


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Markdown belgeleri şifreyle şifrelenemediği için, bu
özellik her zaman 'false' döndürür


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Bu örneğin belirtilen diğerine eşit olup olmadığını belirler
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Bu ile eşitliği kontrol edilmesi gereken diğer [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) örneği |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

