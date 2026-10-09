---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет метаданные одного документа электронной таблицы"
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Представляет метаданные одного документа электронной таблицы

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Возвращает формат этого Spreadsheet‑документа |
|
|  | [getPageCount()](#getPageCount--) | Возвращает количество вкладок |
|
|  | [getSize()](#getSize--) | Возвращает размер в байтах этого Spreadsheet‑документа |
|
|  | [isEncrypted()](#isEncrypted--) | Указывает, зашифрован ли данный Spreadsheet‑документ и |
требует пароль для открытия
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Создаёт и возвращает предварительный просмотр выбранного листа в виде SVG‑изображения |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Определяет, равен ли данный экземпляр указанному другому |
Экземпляр SpreadsheetDocumentInfo
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Возвращает формат этого Spreadsheet‑документа


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Возвращает количество вкладок


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Возвращает размер в байтах этого Spreadsheet‑документа


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Указывает, зашифрован ли данный Spreadsheet‑документ и
требует пароль для открытия


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Создаёт и возвращает предварительный просмотр выбранного листа в виде SVG‑изображения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | worksheetIndex | int | Индекс желаемого листа, начиная с 0. Не может быть меньше 0 и не может превышать количество листов в этой таблице. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Определяет, равен ли данный экземпляр указанному другому
Экземпляр SpreadsheetDocumentInfo


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Другой экземпляр SpreadsheetDocumentInfo, который следует проверить на равенство с этим |
|

**Returns:**
boolean - True, если равны, false, если не равны

