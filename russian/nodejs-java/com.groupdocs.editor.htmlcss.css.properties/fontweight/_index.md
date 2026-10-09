---
title: "FontWeight"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Свойство Font-weight задаёт толщину или жирность шрифта."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Свойство Font-weight задаёт толщину (или жирность) шрифта. Доступные толщины зависят от текущего установленного font-family.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [Lighter](#Lighter) | Относительная толщина шрифта, на одну ступень легче, чем у родительского элемента. |
|
|  | [Bolder](#Bolder) | Относительная толщина шрифта, на одну ступень толще, чем у родительского элемента. |
|
|  | [Normal](#Normal) | Обычная толщина шрифта. |
|
|  | [Bold](#Bold) | Жирная толщина шрифта. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isInitial()](#isInitial--) | Указывает, имеет ли этот размер шрифта начальное значение (Medium) |
|
|  | [getNumber()](#getNumber--) | Возвращает число — целочисленное значение от 1 до 1000 включительно, которое описывает жирность шрифта, или бросает исключение, если текущая жирность не абсолютна, а относительна. |
|
|  | [isAbsolute()](#isAbsolute--) | Указывает, хранит ли данный экземпляр font-weight абсолютное значение веса (жирности) шрифта в виде целого числа. |
|
|  | [isRelative()](#isRelative--) | Указывает, хранит ли данный экземпляр font-weight относительное значение веса (жирности) шрифта — по сравнению с жирностью родительского элемента. |
|
|  | [getValue()](#getValue--) | Возвращает значение этого font-weight в виде строки. |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Определяет, равны ли указанные экземпляры FontWeight. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли данный экземпляр FontWeight указанному неконвертированному. |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Проверяет, равны ли два значения "FontWeight". |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Проверяет, не равны ли два значения "FontWeight". |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Создаёт font-weight из указанного числа. |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Пытается разобрать указанную строку и вернуть корректный экземпляр FontWeight при успехе. |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


Относительная толщина шрифта, на одну ступень легче, чем у родительского элемента.


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


Относительная толщина шрифта, на одну ступень толще, чем у родительского элемента.


### Normal {#Normal}
```
public static final FontWeight Normal
```


Обычная жирность шрифта. То же, что 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Жирная жирность шрифта. То же, что 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Указывает, имеет ли этот размер шрифта начальное значение (Medium)


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Возвращает число — целочисленное значение от 1 до 1000 включительно, которое описывает жирность шрифта, или бросает исключение, если текущая жирность не абсолютна, а относительна.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Указывает, хранит ли данный экземпляр font-weight абсолютное значение веса (жирности) шрифта в виде целого числа.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Указывает, хранит ли данный экземпляр font-weight относительное значение веса (жирности) шрифта — по сравнению с жирностью родительского элемента.


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Возвращает значение этого font-weight в виде строки.


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Определяет, равны ли указанные экземпляры FontWeight.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Другой экземпляр FontWeight для проверки равенства. |
|

**Returns:**
boolean — true, если равны, false, если не равны.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли данный экземпляр FontWeight указанному неконвертированному.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой неконвертированный экземпляр FontWeight, может быть null. |
|

**Returns:**
boolean - true, если равны, false, если не равны, null или другого типа

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.


**Returns:**
int - Hash-code как знаковое целое

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Проверяет, равны ли два значения "FontWeight".


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Первое значение для проверки |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Второе значение для проверки |
|

**Returns:**
boolean - true, если равны, false в противном случае

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Проверяет, не равны ли два значения "FontWeight".


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Первое значение для проверки |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Второе значение для проверки |
|

**Returns:**
boolean - false, если равны, true в противном случае

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Создаёт font-weight из указанного числа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | number | int | Беззнаковое целое число, должно находиться в диапазоне [1..1000]. |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Пытается разобрать указанную строку и вернуть корректный экземпляр FontWeight при успехе.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | input | java.lang.String | Входная строка для разбора. |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Корректное значение FontWeight при успехе или #Normal.Normal при неудаче. |
|

**Returns:**
boolean — успех (true) или неудача (false) разбора.

