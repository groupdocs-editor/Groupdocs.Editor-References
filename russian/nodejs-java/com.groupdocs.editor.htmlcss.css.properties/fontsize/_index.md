---
title: "FontSize"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет размер шрифта как специальную единицу или значение длины, которое указывает размер шрифта, исторически равный ширине заглавной буквы M."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Представляет размер шрифта как специальную единицу или значение длины, которое указывает размер шрифта (исторически — ширина заглавной буквы "M").

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [Medium](#Medium) | Средний размер. |
|
|  | [XxSmall](#XxSmall) | Очень маленький абсолютный размер |
|
|  | [XSmall](#XSmall) | Скромный маленький абсолютный размер |
|
|  | [Small](#Small) | Обычно маленький абсолютный размер |
|
|  | [Large](#Large) | Обычно большой абсолютный размер |
|
|  | [XLarge](#XLarge) | Скромный большой абсолютный размер |
|
|  | [XxLarge](#XxLarge) | Очень большой абсолютный размер |
|
|  | [Larger](#Larger) | Больше относительный размер - шрифт будет больше относительно font-size родительского элемента, примерно по тому же коэффициенту, который используется для разделения вышеуказанных абсолютных размеров. |
|
|  | [Smaller](#Smaller) | Меньше относительный размер - шрифт будет меньше относительно font-size родительского элемента, примерно по тому же коэффициенту, который используется для разделения вышеуказанных абсолютных размеров. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isInitial()](#isInitial--) | Указывает, имеет ли этот размер шрифта начальное значение (Medium) |
|
|  | [getValue()](#getValue--) | Возвращает значение этого размера шрифта в виде строки |
|
|  | [isLengthDefined()](#isLengthDefined--) | Указывает, определён ли этот размер шрифта значением [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |
|
|  | [getLength()](#getLength--) | Значение длины, если этот размер шрифта был определён с его помощью, иначе генерируется исключение |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Указывает, определён ли этот размер шрифта абсолютным размером в виде ключевого слова, основанным на размере шрифта пользователя по умолчанию (который равен medium) |
|
|  | [isRelativeSize()](#isRelativeSize--) | Указывает, определён ли этот размер шрифта относительным размером в виде ключевого слова. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Определяет, равен ли данный экземпляр размера шрифта указанному |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли данный экземпляр размера шрифта указанному неприведенному |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Проверяет, равны ли два значения "FontSize" |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Проверяет, не равны ли два значения "FontSize" |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Создаёт размер шрифта из указанной длины |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Пытается распознать указанное ключевое слово как корректное значение свойства 'font-size' и вернуть его при успехе или NULL при неудаче. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Размер Medium. Начальное значение.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


Очень маленький абсолютный размер


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


Скромный маленький абсолютный размер


### Small {#Small}
```
public static final FontSize Small
```


Обычно маленький абсолютный размер


### Large {#Large}
```
public static final FontSize Large
```


Обычно большой абсолютный размер


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


Скромный большой абсолютный размер


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


Очень большой абсолютный размер


### Larger {#Larger}
```
public static final FontSize Larger
```


Больше относительный размер - шрифт будет больше относительно font-size родительского элемента, примерно по тому же коэффициенту, который используется для разделения вышеуказанных абсолютных размеров.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Меньше относительный размер - шрифт будет меньше относительно font-size родительского элемента, примерно по тому же коэффициенту, который используется для разделения вышеуказанных абсолютных размеров.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Указывает, имеет ли этот размер шрифта начальное значение (Medium)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Возвращает значение этого размера шрифта в виде строки


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Указывает, определён ли этот размер шрифта значением [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Значение длины, если этот размер шрифта был определён с его помощью, иначе генерируется исключение


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Указывает, определён ли этот размер шрифта абсолютным размером в виде ключевого слова, основанным на размере шрифта пользователя по умолчанию (который равен medium)


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Указывает, определён ли этот размер шрифта относительным размером в виде ключевого слова. Шрифт будет больше или меньше относительно размера шрифта родительского элемента, примерно по коэффициенту, используемому для разделения абсолютных ключевых слов.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Определяет, равен ли данный экземпляр размера шрифта указанному


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Другой экземпляр размера шрифта |
|

**Returns:**
boolean - true, если равны, false в противном случае

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли данный экземпляр размера шрифта указанному неприведенному


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой неконвертированный экземпляр размера шрифта, может быть null |
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

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Проверяет, равны ли два значения "FontSize"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Первое значение для проверки |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Второе значение для проверки |
|

**Returns:**
boolean - true, если равны, false в противном случае

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Проверяет, не равны ли два значения "FontSize"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Первое значение для проверки |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Второе значение для проверки |
|

**Returns:**
boolean - false, если равны, true в противном случае

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Создаёт размер шрифта из указанной длины


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Значение длины, не может быть без единицы измерения или отрицательным |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Пытается распознать указанное ключевое слово как корректное значение свойства 'font-size' и вернуть его при успехе или NULL при неудаче.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | keyword | java.lang.String | Ключевое слово для разбора |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Результат: разбор был успешным, иначе #Medium.Medium |
|

**Returns:**
boolean - true, если разбор был успешным, false в противном случае

