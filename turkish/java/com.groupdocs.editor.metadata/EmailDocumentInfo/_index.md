---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Desteklenen herhangi bir e-posta formatındaki bir e-posta belgesinin meta verilerini temsil eder"
type: docs
weight: 11
url: /tr/java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Desteklenen herhangi bir e-posta formatındaki bir e-posta belgesinin meta verilerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | Bu e-posta belgesinin formatını döndürür |
|
|  | [getPageCount()](#getPageCount--) | Her zaman 1 döndürür, çünkü e-posta belgelerinde sayfalı görünüm yoktur |
|
|  | [getSize()](#getSize--) | Bu e-posta belgesinin bayt cinsinden boyutunu döndürür |
|
|  | [isEncrypted()](#isEncrypted--) | E-posta belgeleri şifreyle şifrelenemediği için, bu özellik her zaman 'false' döndürür |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Bu örneğin, belirtilen diğer EmailDocumentInfo örneğine eşit olup olmadığını belirler |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Bu e-posta belgesinin formatını döndürür


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Her zaman 1 döndürür, çünkü e-posta belgelerinde sayfalı görünüm yoktur


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Bu e-posta belgesinin bayt cinsinden boyutunu döndürür


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


E-posta belgeleri şifreyle şifrelenemediği için, bu özellik her zaman 'false' döndürür


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Bu örneğin, belirtilen diğer EmailDocumentInfo örneğine eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Bu örnek ile eşitlik açısından kontrol edilmesi gereken diğer EmailDocumentInfo örneği |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

