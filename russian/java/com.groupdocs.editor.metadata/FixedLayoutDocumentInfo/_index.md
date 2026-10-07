---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет метаданные одного документа с фиксированным макетом, например PDF или XPS"
type: docs
weight: 12
url: /ru/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Представляет метаданные одного документа с фиксированным макетом, например PDF или XPS

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Возвращает формат этого документа фиксированного макета |
|
|  | [getPageCount()](#getPageCount--) | Возвращает количество страниц |
|
|  | [getSize()](#getSize--) | Возвращает размер в байтах этого документа фиксированного макета |
|
|  | [isEncrypted()](#isEncrypted--) | Определяет, зашифрован ли конкретный документ фиксированного макета и требует пароль для открытия |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Определяет, равен ли этот экземпляр другому указанному экземпляру FixedLayoutDocumentInfo |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Возвращает формат этого документа фиксированного макета


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Возвращает количество страниц


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Возвращает размер в байтах этого документа фиксированного макета


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Определяет, зашифрован ли конкретный документ фиксированного макета и требует пароль для открытия


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Определяет, равен ли этот экземпляр другому указанному экземпляру FixedLayoutDocumentInfo


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Другой экземпляр FixedLayoutDocumentInfo, который должен быть проверен на равенство с этим |
|

**Returns:**
boolean — True, если равны, false, если не равны

