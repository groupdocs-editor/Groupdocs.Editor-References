---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "XML, HTML veya düz metin TXT gibi bir metin belgesinin meta verilerini temsil eder"
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

XML, HTML veya düz metin gibi bir metin belgesinin meta verilerini temsil eder
(TXT)

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | Bu metin belgesinin formatını döndürür. |
|
|  | [getPageCount()](#getPageCount--) | Her zaman 1 döndürür |
|
|  | [getSize()](#getSize--) | Bu metnin bayt cinsinden boyutunu (karakter sayısı değil) döndürür |
belge
|
|  | [isEncrypted()](#isEncrypted--) | Metin belgeleri şifrelenemediği için her zaman 'false' döndürür. |
|
|  | [getEncoding()](#getEncoding--) | Metin belgesinin tespit edilen muhtemel kodlamasını döndürür |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Bu metin belgesinin formatını döndürür. %100 doğru olmayabilir
bazı durumlarda.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Her zaman 1 döndürür


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Bu metnin bayt cinsinden boyutunu (karakter sayısı değil) döndürür
belge


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Metin belgeleri şifrelenemediği için her zaman 'false' döndürür.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Metin belgesinin tespit edilen muhtemel kodlamasını döndürür


**Returns:**
java.nio.charset.Charset
