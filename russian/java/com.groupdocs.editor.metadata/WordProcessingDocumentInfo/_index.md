---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет метаданные одного документа WordProcessing"
type: docs
weight: 17
url: /ru/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Представляет метаданные одного документа WordProcessing

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Возвращает формат этого документа WordProcessing |
|
|  | [getPageCount()](#getPageCount--) | Возвращает количество страниц |
|
|  | [getSize()](#getSize--) | Возвращает размер в байтах этого документа WordProcessing |
|
|  | [isEncrypted()](#isEncrypted--) | Определяет, зашифрован ли конкретный документ WordProcessing и |
требует пароль для открытия
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Генерирует и возвращает предварительный просмотр выбранной страницы в виде SVG‑изображения |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Определяет, равен ли этот экземпляр указанному другому |
Экземпляр WordProcessingDocumentInfo
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Возвращает формат этого документа WordProcessing


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
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


Возвращает размер в байтах этого документа WordProcessing


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Определяет, зашифрован ли конкретный документ WordProcessing и
требует пароль для открытия


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Генерирует и возвращает предварительный просмотр выбранной страницы в виде SVG‑изображения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageIndex | int | Индекс желаемой страницы, начиная с 0. Не может быть меньше 0, не может превышать количество страниц в этом документе WordProcessing. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Определяет, равен ли этот экземпляр указанному другому
Экземпляр WordProcessingDocumentInfo


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Другой экземпляр WordProcessingDocumentInfo, который должен быть проверен на равенство с этим |
|

**Returns:**
boolean — True, если равны, false, если не равны

