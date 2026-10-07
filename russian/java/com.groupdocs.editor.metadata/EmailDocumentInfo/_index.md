---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет метаданные одного электронного письма любого поддерживаемого формата электронной почты"
type: docs
weight: 11
url: /ru/java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Представляет метаданные одного электронного письма любого поддерживаемого формата электронной почты

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Возвращает формат этого email‑документа |
|
|  | [getPageCount()](#getPageCount--) | Всегда возвращает 1, потому что у email‑документов нет постраничного представления |
|
|  | [getSize()](#getSize--) | Возвращает размер в байтах этого email‑документа |
|
|  | [isEncrypted()](#isEncrypted--) | Поскольку email‑документы не могут быть зашифрованы паролем, это свойство всегда возвращает 'false' |
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


Возвращает формат этого email‑документа


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Всегда возвращает 1, потому что у email‑документов нет постраничного представления


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Возвращает размер в байтах этого email‑документа


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Поскольку email‑документы не могут быть зашифрованы паролем, это свойство всегда возвращает 'false'


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
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Другой экземпляр EmailDocumentInfo, который должен проверяться на равенство с этим |
|

**Returns:**
boolean — True, если равны, false, если не равны

