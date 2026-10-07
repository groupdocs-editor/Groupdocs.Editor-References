---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет метаданные одного документа презентации"
type: docs
weight: 14
url: /ru/java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Представляет метаданные одного документа презентации

## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Возвращает формат этого документа Presentation |
|
|  | [getPageCount()](#getPageCount--) | Возвращает количество слайдов в этом документе Presentation |
|
|  | [getSize()](#getSize--) | Возвращает размер в байтах этого документа Presentation |
|
|  | [isEncrypted()](#isEncrypted--) | Указывает, зашифрован ли этот конкретный документ Presentation и требует ли пароль для открытия |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Генерирует и возвращает предварительный просмотр выбранного слайда в виде SVG‑изображения |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Возвращает формат этого документа Presentation


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Возвращает количество слайдов в этом документе Presentation


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Возвращает размер в байтах этого документа Presentation


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Указывает, зашифрован ли этот конкретный документ Presentation и требует ли пароль для открытия


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Генерирует и возвращает предварительный просмотр выбранного слайда в виде SVG‑изображения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | slideIndex | int | Индекс желаемого слайда, начиная с 0. Не может быть меньше 0 и не может превышать количество слайдов в этой презентации. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

