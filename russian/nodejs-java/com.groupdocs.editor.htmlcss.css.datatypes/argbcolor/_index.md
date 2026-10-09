---
title: "ArgbColor"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет одно значение цвета в формате ARGB с конвертерами и сериализаторами"
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Представляет одно значение цвета в формате ARGB с конвертерами и сериализаторами

<br />

*** ** * ** ***

Этот тип разработан для удобного использования в операциях CSS (но не ограничивается ими). Подробнее: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Создаёт одно значение [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) из указанных каналов Red, Green, Blue и Alpha. |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Создаёт одно значение [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) из указанных каналов Red, Green, Blue, при этом канал Alpha полностью непрозрачный. |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Создаёт полностью непрозрачный (A=255) цвет из одного значения, которое будет применено ко всем каналам. |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Создаёт одно значение [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) из указанного [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color). |
|
|  | [getValue()](#getValue--) | Получает значение Int32 цвета. |
|
|  | [getA()](#getA--) | Получает альфа‑часть цвета. |
|
|  | [getAlpha()](#getAlpha--) | Получает альфа‑часть цвета в процентах (0..1). |
|
|  | [getR()](#getR--) | Получает красную часть цвета. |
|
|  | [getG()](#getG--) | Получает зелёную часть цвета. |
|
|  | [getB()](#getB--) | Получает синюю часть цвета. |
|
|  | [isEmpty()](#isEmpty--) | Неинициализированный цвет — все 4 канала установлены в 0. |
|
|  | [isDefault()](#isDefault--) | Указывает, является ли данный экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) значением по умолчанию (Transparent) — все 4 канала установлены в 0. |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Указывает, является ли данный экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) полностью прозрачным — его альфа‑канал имеет минимальное (0) значение, поэтому остальные каналы R, G и B не оказывают видимого эффекта. |
|
|  | [isTranslucent()](#isTranslucent--) | Указывает, является ли данный экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) полупрозрачным (не полностью прозрачным, но и не полностью непрозрачным). |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Указывает, является ли данный экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) полностью непрозрачным, без прозрачности (его альфа‑канал имеет максимальное значение). |
|
|  | [toSystemColor()](#toSystemColor--) | Преобразует значение данного экземпляра [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) в экземпляр [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) и возвращает его. |
|
|  | [toRGBA()](#toRGBA--) | Сериализует этот экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) в нотацию функции CSS 'rgba' |
|
|  | [toRGB()](#toRGB--) | Сериализует этот экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) в нотацию функции CSS 'rgb' |
|
|  | [serializeDefault()](#serializeDefault--) | Сериализует этот экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) в наиболее подходящую нотацию функции CSS в зависимости от прозрачности |
|
|  | [toString()](#toString--) | То же, что #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Сравнивает два цвета и возвращает логическое значение, указывающее, совпадают ли они. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Сравнивает два цвета и возвращает логическое значение, указывающее, не совпадают ли они. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Проверяет два цвета [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) на равенство |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Проверяет два цвета [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) на равенство |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Проверяет, равен ли другой объект этому экземпляру [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor). |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш-код, определяющий текущий цвет. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Создаёт одно значение [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) из указанных каналов Red, Green, Blue и Alpha.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | красный | int | Значение красного канала |
|
|  | зеленый | int | Значение зеленого канала |
|
|  | синий | int | Значение синего канала |
|
|  | альфа | int | Значение альфа-канала |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Создаёт одно значение [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) из указанных каналов Red, Green, Blue, при этом канал Alpha полностью непрозрачный.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | красный | int | Значение красного канала |
|
|  | зеленый | int | Значение зеленого канала |
|
|  | синий | int | Значение синего канала |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Создаёт полностью непрозрачный (A=255) цвет из одного значения, которое будет применено ко всем каналам.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | byte | Значение байта, одинаковое для каналов Красного, Зеленого и Синего |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Создаёт одно значение [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) из указанного [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| цвет | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Получает значение Int32 цвета.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Получает альфа‑часть цвета.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Получает альфа‑часть цвета в процентах (0..1).


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Получает красную часть цвета.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Получает зелёную часть цвета.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Получает синюю часть цвета.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Неинициализированный цвет — все 4 канала установлены в 0. То же, что Default и Transparent.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Указывает, является ли данный экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) значением по умолчанию (Transparent) — все 4 канала установлены в 0.


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Указывает, является ли данный экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) полностью прозрачным — его альфа‑канал имеет минимальное (0) значение, поэтому остальные каналы R, G и B не оказывают видимого эффекта.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Указывает, является ли данный экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) полупрозрачным (не полностью прозрачным, но и не полностью непрозрачным).


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Указывает, является ли данный экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) полностью непрозрачным, без прозрачности (его альфа‑канал имеет максимальное значение).


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Преобразует значение данного экземпляра [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) в экземпляр [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) и возвращает его.


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Сериализует этот экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) в нотацию функции CSS 'rgba'


**Returns:**
java.lang.String — строка в формате 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Сериализует этот экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) в нотацию функции CSS 'rgb'


**Returns:**
java.lang.String - Строка в формате 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Сериализует этот экземпляр [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) в наиболее подходящую нотацию функции CSS в зависимости от прозрачности


**Returns:**
java.lang.String - Строка в формате 'rgba(r, g, b, a)' или 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


То же, что #serializeDefault.serializeDefault


**Returns:**
java.lang.String - Такое же возвращаемое значение, как в #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Сравнивает два цвета и возвращает логическое значение, указывающее, совпадают ли они.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Первый цвет, который будет использоваться. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Второй цвет, который будет использоваться. |
|

**Returns:**
boolean - True если оба цвета равны, иначе false.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Сравнивает два цвета и возвращает логическое значение, указывающее, не совпадают ли они.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Первый цвет, который будет использоваться. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Второй цвет, который будет использоваться. |
|

**Returns:**
boolean - True если оба цвета не равны, иначе false.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Проверяет два цвета [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) на равенство


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Другой [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) цвет |
|

**Returns:**
boolean - True если оба цвета равны, иначе false.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Проверяет два цвета [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) на равенство


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | Другой [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) цвет, приведённый к ICssDataType |
|

**Returns:**
boolean - True если оба цвета равны, иначе false.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Проверяет, равен ли другой объект этому экземпляру [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | другой | java.lang.Object | Объект для тестирования. |
|

**Returns:**
boolean - True если два объекта равны, иначе false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код, определяющий текущий цвет.


**Returns:**
int - Целочисленное значение хешкода.

