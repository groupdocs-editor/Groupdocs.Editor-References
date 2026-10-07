---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "PDF veya XPS gibi sabit düzen formatına sahip bir belgenin meta verilerini temsil eder"
type: docs
weight: 12
url: /tr/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

PDF veya XPS gibi sabit düzen formatına sahip bir belgenin meta verilerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | Bu sabit düzen format belgesinin formatını döndürür |
|
|  | [getPageCount()](#getPageCount--) | Sayfa sayısını döndürür |
|
|  | [getSize()](#getSize--) | Bu sabit düzen format belgesinin bayt cinsinden boyutunu döndürür |
|
|  | [isEncrypted()](#isEncrypted--) | Bu belirli sabit düzen format belgesinin şifrelenip şifrelenmediğini ve açmak için şifre gerektirip gerektirmediğini belirler |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Bu örneğin belirtilen diğer FixedLayoutDocumentInfo örneğiyle eşit olup olmadığını belirler |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Bu sabit düzen format belgesinin formatını döndürür


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


Bu sabit düzen format belgesinin bayt cinsinden boyutunu döndürür


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bu belirli sabit düzen format belgesinin şifrelenip şifrelenmediğini ve açmak için şifre gerektirip gerektirmediğini belirler


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Bu örneğin belirtilen diğer FixedLayoutDocumentInfo örneğiyle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Bu ile eşitliği kontrol edilmesi gereken diğer FixedLayoutDocumentInfo örneği |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

