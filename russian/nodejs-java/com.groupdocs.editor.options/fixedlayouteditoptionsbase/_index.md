---
title: "FixedLayoutEditOptionsBase"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Базовый абстрактный класс для параметров всех документов фиксированного макета, таких как PDF и XPS."
type: docs
weight: 16
url: /ru/nodejs-java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Базовый абстрактный класс для параметров всех документов фиксированного макета, таких как PDF и XPS.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Получает или задает флаг, указывающий, должны ли изображения пропускаться при преобразовании входного фиксированного документа в результирующий HTML. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Получает или задает флаг, указывающий, должны ли изображения пропускаться при преобразовании входного фиксированного документа в результирующий HTML. |
|
|  | [getPages()](#getPages--) | Позволяет задать диапазон страниц для обработки. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Позволяет задать диапазон страниц для обработки. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Позволяет включить (true) или отключить (false) пагинацию в результирующем HTML‑документе. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Позволяет включить (true) или отключить (false) пагинацию в результирующем HTML‑документе. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Получает или задает флаг, указывающий, должны ли изображения пропускаться при преобразовании входного фиксированного документа в результирующий HTML. По умолчанию false — изображения сохраняются.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Получает или задает флаг, указывающий, должны ли изображения пропускаться при преобразовании входного фиксированного документа в результирующий HTML. По умолчанию false — изображения сохраняются.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Позволяет задать диапазон страниц для обработки. По умолчанию обрабатываются все страницы фиксированного документа.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Позволяет задать диапазон страниц для обработки. По умолчанию обрабатываются все страницы фиксированного документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Позволяет включить (true) или отключить (false) пагинацию в результирующем HTML‑документе. По умолчанию отключена (false).

<br />

*** ** * ** ***

Документы фиксированного формата (в частности PDF и XPS) по своей сути строго постраничны, их содержимое имеет фиксированную разметку и разделено на страницы. Однако результирующий редактируемый HTML может быть представлен как безстраничный, так и постраничный вид.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Позволяет включить (true) или отключить (false) пагинацию в результирующем HTML‑документе. По умолчанию отключена (false).

<br />

*** ** * ** ***

Документы фиксированного формата (в частности PDF и XPS) по своей сути строго постраничны, их содержимое имеет фиксированную разметку и разделено на страницы. Однако результирующий редактируемый HTML может быть представлен как безстраничный, так и постраничный вид.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

