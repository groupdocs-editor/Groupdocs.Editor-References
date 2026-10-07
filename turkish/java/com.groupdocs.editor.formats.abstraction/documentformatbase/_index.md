---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Belge formatları için ortak işlevsellik sağlayan temel sınıfı temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Belge formatları için temel sınıfı temsil eder, format örnekleri için ortak işlevsellik sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMime()](#getMime--) | Belge formatının MIME tipini alır. |
|
|  | [getExtension()](#getExtension--) | Belge formatının dosya uzantısını alır. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Belge formatının ait olduğu format ailesini alır. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Belirtilen tipin bir örneğini alır. |
T
belirtilen MIME türüne sahip.
|
|  | [hashCode()](#hashCode--) | Geçerli nesne için bir karma kodu döndürür. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Bu örneğin belirtilen [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) örneğiyle eşit olup olmadığını belirler. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) örneğiyle eşit olup olmadığını belirler. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) örneğini örtük olarak bir dizeye dönüştürür. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Belge formatının MIME tipini alır.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Belge formatının dosya uzantısını alır.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Belge formatının ait olduğu format ailesini alır.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Belirtilen tipin bir örneğini alır.
T
belirtilen MIME türüne sahip.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | Belge formatının MIME türü. |


T
: Belge formatının türü.
|

**Returns:**
T - Belirtilen tipin bir örneği  T  ve belirtilen MIME türü.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesne için bir karma kodu döndürür.


**Returns:**
int - Geçerli nesne için bir karma kodu, temel nesnenin, MIME türünün, dosya uzantısının ve format ailesinin karma kodlarını birleştirir.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Bu örneğin belirtilen [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) örneğiyle eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | Geçerli örnekle karşılaştırılacak [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) örneği. |
|

**Returns:**
boolean -  true  eğer belirtilen [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) geçerli örnekle eşitse; aksi takdirde,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) örneğiyle eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Geçerli örnekle karşılaştırılacak [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) örneği. |
|

**Returns:**
boolean -  true  eğer belirtilen [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) geçerli örnekle eşitse; aksi takdirde,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) örneğini örtük olarak bir dizeye dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | Dönüştürülecek [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) örneği. |
|

**Returns:**
java.lang.String - [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) örneğinin dosya uzantısı.

