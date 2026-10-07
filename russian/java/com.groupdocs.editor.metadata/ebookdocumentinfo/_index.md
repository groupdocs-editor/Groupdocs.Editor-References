---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет метаданные одного документа EBook"
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Представляет метаданные одного документа EBook

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Возвращает формат этого документа |
|
|  | [getPageCount()](#getPageCount--) | Возвращает количество страниц в случае форматов MOBI или AZW3, либо количество глав в случае ePub. |
|
|  | [getSize()](#getSize--) | Возвращает размер в байтах этого eBook‑документа |
|
|  | [isEncrypted()](#isEncrypted--) | Поскольку eBook‑документы нельзя зашифровать паролем, это свойство всегда возвращает 'false' |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Определяет, равен ли данный экземпляр другому указанному экземпляру EbookDocumentInfo |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Возвращает формат этого документа


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Возвращает количество страниц в случае форматов MOBI или AZW3, либо количество глав в случае ePub.

<br />

*** ** * ** ***

Обычно у eBook‑документов нет фиксированных страниц и, следовательно, количества страниц. В случае ePub можно вычислить количество глав. Однако форматы MOBI и AZW3 также не содержат глав, поэтому это число рассчитывается исходя из стандартного размера страницы, установленного как A4 в портретной ориентации.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Возвращает размер в байтах этого eBook‑документа


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Поскольку eBook‑документы нельзя зашифровать паролем, это свойство всегда возвращает 'false'


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Определяет, равен ли данный экземпляр другому указанному экземпляру EbookDocumentInfo


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Другой экземпляр EbookDocumentInfo, который следует проверить на равенство с текущим |
|

**Returns:**
boolean — True, если равны, false, если не равны

