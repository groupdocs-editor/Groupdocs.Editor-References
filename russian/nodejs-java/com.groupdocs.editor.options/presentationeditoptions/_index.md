---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Позволяет задать пользовательские параметры для редактирования документов всех поддерживаемых форматов презентаций, совместимых с PowerPoint"
type: docs
weight: 32
url: /ru/nodejs-java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых
Форматы презентаций (совместимые с PowerPoint)

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Позволяет указать номера слайдов, которые должны быть открыты для редактирования |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Позволяет указать номера слайдов, которые должны быть открыты для редактирования |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды или нет. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды или нет. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Позволяет указать номера слайдов, которые должны быть открыты для редактирования


*** ** * ** ***

Номер слайда — это нулевой индекс слайда, который позволяет указать и выбрать один конкретный слайд из презентации для редактирования. Если значение меньше 0, будет выбран первый слайд (то же самое, что SlideNumber = 0). Если значение больше количества всех слайдов в презентации, будет выбран последний слайд. Если входная презентация содержит только один слайд, этот параметр будет игнорироваться, и будет редактироваться единственный слайд. При попытке открыть для редактирования скрытый слайд, когда параметр ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) установлен в 'false', будет выброшено исключение.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Позволяет указать номера слайдов, которые должны быть открыты для редактирования


*** ** * ** ***

Номер слайда — это нулевой индекс слайда, который позволяет указать и выбрать один конкретный слайд из презентации для редактирования. Если значение меньше 0, будет выбран первый слайд (то же самое, что SlideNumber = 0). Если значение больше количества всех слайдов в презентации, будет выбран последний слайд. Если входная презентация содержит только один слайд, этот параметр будет игнорироваться, и будет редактироваться единственный слайд. При попытке открыть для редактирования скрытый слайд, когда параметр ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) установлен в 'false', будет выброшено исключение.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Указывает, следует ли включать скрытые слайды или нет. По умолчанию
false — скрытые слайды не отображаются, и будет выброшено исключение при
попытке их редактировать.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Указывает, следует ли включать скрытые слайды или нет. По умолчанию
false — скрытые слайды не отображаются, и будет выброшено исключение при
попытке их редактировать.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

