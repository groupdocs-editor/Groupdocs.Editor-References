---
title: "Dimensions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет линейные размеры ширины и высоты одного растрового прямоугольного изображения в произвольных единицах."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Представляет линейные размеры (ширина и высота) одного растрового прямоугольного
изображение в произвольных единицах. Неизменяемая структура.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Создаёт новый экземпляр из указанных ширины и высоты |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getWidth()](#getWidth--) | Возвращает ширину изображения |
|
|  | [getHeight()](#getHeight--) | Возвращает высоту изображения |
|
|  | [isSquare()](#isSquare--) | Определяет, представляет ли указанная 'Dimensions' квадрат, т.е. |
|
|  | [getArea()](#getArea--) | Возвращает площадь (Ширина x Высота) |
|
|  | [isEmpty()](#isEmpty--) | Определяет, является ли данный экземпляр "Dimensions" пустым и значением по умолчанию, т.е. |
|
|  | [getAspectRatio()](#getAspectRatio--) | Соотношение сторон этих размеров как ширина/высота |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Создаёт и возвращает новый экземпляр "Dimensions", который пропорционально |
изменён в размере от текущего, исходя из указанной ширины
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Создаёт и возвращает новый экземпляр "Dimensions", который пропорционально |
изменён в размере от текущего, исходя из указанной высоты
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Определяет, равен ли данный экземпляр указанному "Dimensions" |
экземпляр
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли данный экземпляр указанному неконвертированному объекту, |
который, предположительно, является другим экземпляром "Dimensions"
|
|  | [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра, который не может быть изменён во время его |
жизни
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Проверяет, равны ли два значения "Dimensions", т.е. |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Проверяет, не равны ли два значения "Dimensions", т.е. |
|
|  | [toString()](#toString--) | Возвращает строковое представление этого "Dimensions" |
|
|  | [deepClone()](#deepClone--) | Возвращает полную копию этого экземпляра |
|
|  | [getEmpty()](#getEmpty--) | Возвращает пустой экземпляр Dimensions |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Создаёт новый экземпляр из указанных ширины и высоты


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | ширина | int | Ширина изображения |
|
|  | высота | int | Высота изображения |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Возвращает ширину изображения


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Возвращает высоту изображения


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Определяет, представляет ли указанная 'Dimensions' квадрат, т.е. если
ширина равна высоте


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Возвращает площадь (Ширина x Высота)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Определяет, является ли данный экземпляр "Dimensions" пустым и значением по умолчанию, т.е.
он не сохраняет правильные ширину и высоту


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Соотношение сторон этих размеров как ширина/высота


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Создаёт и возвращает новый экземпляр "Dimensions", который пропорционально
изменён в размере от текущего, исходя из указанной ширины


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | targetWidth | int | Новая целевая ширина, которая будет присутствовать в результирующем Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Создаёт и возвращает новый экземпляр "Dimensions", который пропорционально
изменён в размере от текущего, исходя из указанной высоты


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | targetHeight | int | Новая целевая высота, которая будет присутствовать в результирующем Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Определяет, равен ли данный экземпляр указанному "Dimensions"
экземпляр


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Другой экземпляр "Dimensions" для проверки на равенство |
|

**Returns:**
boolean - True, если равны, false, если не равны

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли данный экземпляр указанному неконвертированному объекту,
который, предположительно, является другим экземпляром "Dimensions"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой объект, предположительно типа "Dimensions", который должен быть проверен на равенство с этим |
|

**Returns:**
boolean - True, если равны, false, если не равны

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра, который не может быть изменён во время его
жизни


**Returns:**
int - неизменяемый (для этого экземпляра) хеш-код как знаковое 4-байтовое целое

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Проверяет, равны ли два значения "Dimensions", т.е. они имеют одинаковые
ширину и высоту, либо оба пусты


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Первый экземпляр для проверки |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Второй экземпляр для проверки |
|

**Returns:**
boolean - True, если равны, false, если не равны

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Проверяет, не равны ли два значения "Dimensions", т.е. их
соответствующая ширина и/или высота различаются


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Первый экземпляр для проверки |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Второй экземпляр для проверки |
|

**Returns:**
boolean - True если не равны, false если равны

### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление этого "Dimensions"

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - экземпляр String, содержащий ширину и высоту в формате W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Возвращает полную копию этого экземпляра


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Возвращает пустой экземпляр Dimensions


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
