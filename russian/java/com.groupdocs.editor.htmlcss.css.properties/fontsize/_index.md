---
title: "FontSize"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет размер шрифта как специальную единицу или значение длины, которое определяет размер шрифта, исторически равный ширине заглавной буквы M."
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Представляет размер шрифта как специальную единицу или значение длины, которое определяет размер шрифта (исторически — ширина заглавной буквы "M").

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [Medium](#Medium) | Средний размер. |
|
|  | [XxSmall](#XxSmall) | Очень маленький absolute-size |
|
|  | [XSmall](#XSmall) | Умеренно маленький absolute-size |
|
|  | [Small](#Small) | Обычно маленький absolute-size |
|
|  | [Large](#Large) | Обычно большой absolute-size |
|
|  | [XLarge](#XLarge) | Умеренно большой absolute-size |
|
|  | [XxLarge](#XxLarge) | Очень большой absolute-size |
|
|  | [Larger](#Larger) | Больше относительный размер - шрифт будет больше относительно font-size родительского элемента, примерно по соотношению, используемому для разделения вышеуказанных absolute-size ключевых слов. |
|
|  | [Smaller](#Smaller) | Меньше относительный размер - шрифт будет меньше относительно font-size родительского элемента, примерно по соотношению, используемому для разделения вышеуказанных absolute-size ключевых слов. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isInitial()](#isInitial--) | Указывает, имеет ли этот font-size начальное значение (Medium) |
|
|  | [getValue()](#getValue--) | Возвращает значение этого font size в виде строки |
|
|  | [isLengthDefined()](#isLengthDefined--) | Указывает, определён ли этот размер шрифта значением [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length). |
|
|  | [getLength()](#getLength--) | Значение длины, если этот размер шрифта был определён им, иначе генерируется исключение. |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Указывает, определён ли этот размер шрифта абсолютным размером в виде ключевого слова, основанным на размере шрифта по умолчанию пользователя (который равен medium). |
|
|  | [isRelativeSize()](#isRelativeSize--) | Указывает, определён ли этот размер шрифта относительным размером в виде ключевого слова. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Определяет, равен ли данный экземпляр размера шрифта указанному. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли данный экземпляр размера шрифта указанному неконвертированному. |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Проверяет, равны ли два значения "FontSize". |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Проверяет, не равны ли два значения "FontSize". |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Создаёт размер шрифта из указанной длины. |
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


Размер medium. Начальное значение.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


Очень маленький absolute-size


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


Умеренно маленький absolute-size


### Small {#Small}
```
public static final FontSize Small
```


Обычно маленький absolute-size


### Large {#Large}
```
public static final FontSize Large
```


Обычно большой absolute-size


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


Умеренно большой absolute-size


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


Очень большой absolute-size


### Larger {#Larger}
```
public static final FontSize Larger
```


Больше относительный размер - шрифт будет больше относительно font-size родительского элемента, примерно по соотношению, используемому для разделения вышеуказанных absolute-size ключевых слов.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Меньше относительный размер - шрифт будет меньше относительно font-size родительского элемента, примерно по соотношению, используемому для разделения вышеуказанных absolute-size ключевых слов.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Указывает, имеет ли этот font-size начальное значение (Medium)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Возвращает значение этого font size в виде строки


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Указывает, определён ли этот размер шрифта значением [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length).


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Значение длины, если этот размер шрифта был определён им, иначе генерируется исключение.


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Указывает, определён ли этот размер шрифта абсолютным размером в виде ключевого слова, основанным на размере шрифта по умолчанию пользователя (который равен medium).


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


Определяет, равен ли данный экземпляр размера шрифта указанному.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Другой экземпляр размера шрифта. |
|

**Returns:**
boolean - true если равны, false иначе

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли данный экземпляр размера шрифта указанному неконвертированному.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой неконвертированный экземпляр размера шрифта, может быть null. |
|

**Returns:**
boolean - true если равны, false если не равны, null или другого типа

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра


**Returns:**
int - Hash-code как знаковое целое

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Проверяет, равны ли два значения "FontSize".


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Первое значение для проверки |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Второе значение для проверки |
|

**Returns:**
boolean - true если равны, false иначе

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Проверяет, не равны ли два значения "FontSize".


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Первое значение для проверки |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Второе значение для проверки |
|

**Returns:**
boolean - false если равны, true иначе

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Создаёт размер шрифта из указанной длины.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Значение длины, не может быть без единицы измерения или отрицательным. |
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
|  | ключевое слово | java.lang.String | Ключевое слово для разбора |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Результат: разбор прошёл успешно, иначе #Medium.Medium. |
|

**Returns:**
boolean - true если разбор был успешным, false иначе

