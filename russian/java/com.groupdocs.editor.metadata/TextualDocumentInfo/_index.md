---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет метаданные одного текстового документа, например XML, HTML или обычного текста TXT"
type: docs
weight: 16
url: /ru/java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Представляет метаданные одного текстового документа, например XML, HTML или обычного текста
(TXT)

## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Возвращает формат этого текстового документа. |
|
|  | [getPageCount()](#getPageCount--) | Всегда возвращает 1 |
|
|  | [getSize()](#getSize--) | Возвращает размер в байтах (а не количество символов) этого текстового |
документа
|
|  | [isEncrypted()](#isEncrypted--) | Всегда возвращает 'false', так как текстовые документы не могут быть зашифрованы. |
|
|  | [getEncoding()](#getEncoding--) | Возвращает обнаруженную предполагаемую кодировку текстового документа |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Возвращает формат этого текстового документа. Может быть не на 100% корректен в
некоторых случаях.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Всегда возвращает 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Возвращает размер в байтах (а не количество символов) этого текстового
документа


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Всегда возвращает 'false', так как текстовые документы не могут быть зашифрованы.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Возвращает обнаруженную предполагаемую кодировку текстового документа


**Returns:**
java.nio.charset.Charset
