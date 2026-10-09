---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет метаданные одного почтового документа любого поддерживаемого формата электронной почты"
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Представляет метаданные одного почтового документа любого поддерживаемого формата электронной почты

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Возвращает формат этого документа электронной почты |
|
|  | [getPageCount()](#getPageCount--) | Всегда возвращает 1, потому что у документов электронной почты нет постраничного представления |
|
|  | [getSize()](#getSize--) | Возвращает размер в байтах этого документа электронной почты |
|
|  | [isEncrypted()](#isEncrypted--) | Поскольку документы электронной почты не могут быть зашифрованы паролем, это свойство всегда возвращает 'false' |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Определяет, равен ли этот экземпляр другому указанному экземпляру EmailDocumentInfo |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Возвращает формат этого документа электронной почты


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Всегда возвращает 1, потому что у документов электронной почты нет постраничного представления


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Возвращает размер в байтах этого документа электронной почты


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Поскольку документы электронной почты не могут быть зашифрованы паролем, это свойство всегда возвращает 'false'


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Определяет, равен ли этот экземпляр другому указанному экземпляру EmailDocumentInfo


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Другой экземпляр EmailDocumentInfo, который следует проверить на равенство с этим |
|

**Returns:**
boolean - True, если равны, false, если не равны

