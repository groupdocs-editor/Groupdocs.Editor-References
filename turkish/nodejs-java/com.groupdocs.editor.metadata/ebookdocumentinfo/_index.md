---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Bir EBook belgesinin meta verilerini temsil eder"
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Bir EBook belgesinin meta verilerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | Bu belgenin bir formatını döndürür |
|
|  | [getPageCount()](#getPageCount--) | MOBI veya AZW3 durumunda sayfa sayısını, ePub durumunda ise bölüm sayısını döndürür. |
|
|  | [getSize()](#getSize--) | Bu eKitap belgesinin bayt cinsinden boyutunu döndürür |
|
|  | [isEncrypted()](#isEncrypted--) | eKitap belgeleri şifre ile şifrelenemediği için, bu özellik her zaman 'false' döndürür |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Bu örneğin, belirtilen diğer EbookDocumentInfo örneğiyle eşit olup olmadığını belirler |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Bu belgenin bir formatını döndürür


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


MOBI veya AZW3 durumunda sayfa sayısını, ePub durumunda ise bölüm sayısını döndürür.

<br />

*** ** * ** ***

eKitap belgeleri genellikle sabit sayfalara sahip değildir ve bu nedenle sayfa sayısı yoktur. ePub durumunda bölüm sayısı hesaplanabilir. Ancak MOBI ve AZW3 formatlarında da bölüm bulunmadığından, bu sayı dikey A4 standart sayfa boyutundan hesaplanır.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Bu eKitap belgesinin bayt cinsinden boyutunu döndürür


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


eKitap belgeleri şifre ile şifrelenemediği için, bu özellik her zaman 'false' döndürür


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Bu örneğin, belirtilen diğer EbookDocumentInfo örneğiyle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Bu örnekle eşitlik kontrolü yapılacak diğer EbookDocumentInfo örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

