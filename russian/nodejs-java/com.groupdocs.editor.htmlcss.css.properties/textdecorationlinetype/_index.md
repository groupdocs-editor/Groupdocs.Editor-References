---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет типы линий текстового декора: underline, underscore, overline и line-through (зачёркивание)."
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Представляет типы линии текстового декора: underline (подчеркивание), overline и line-through (зачёркивание)

<br />

*** ** * ** ***

Неизменяемая структура. Похожа на https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [None](#None) | Не создает текстовое оформление. |
|
|  | [Underline](#Underline) | Каждая строка текста подчеркнута. |
|
|  | [Overline](#Overline) | Каждая строка текста имеет линию над ней. |
|
|  | [LineThrough](#LineThrough) | Каждая строка текста имеет линию посередине. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isInitial()](#isInitial--) | Указывает, имеет ли этот экземпляр начальное значение \\u2014 None |
|
|  | [isUnderline()](#isUnderline--) | Указывает, включено ли подчеркивание (символ подчеркивания) |
|
|  | [isOverline()](#isOverline--) | Указывает, включена ли надстрочная линия |
|
|  | [isLineThrough()](#isLineThrough--) | Указывает, включено ли перечёркивание (зачёркивание) |
|
|  | [getValue()](#getValue--) | Возвращает значение всех флагов в этом экземпляре в виде текста |
|
|  | [toString()](#toString--) | Возвращает значение всех флагов в этом экземпляре в виде текста |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Указывает, равен ли этот экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) указанному |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Указывает, равен ли этот экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) указанному без приведения типов |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш-код этого экземпляра |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Проверяет, равны ли два значения "TextDecorationLineType" |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Проверяет, не равны ли два значения "TextDecorationLineType" |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Создаёт и возвращает экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) с флагами, определёнными указанными параметрами |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Пытается разобрать указанную строку и вернуть корректный экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Объединяет (сливает) два указанных типа линий и создаёт новый результирующий тип линии, где флаги объединены (объединение) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Вычитает второй указанный тип линии из первого указанного типа линии и создаёт новый результирующий тип линии, в котором присутствуют только те флаги из первого операнда, которые не найдены во втором операнде (разность) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Возвращает пересечение первого и второго типов линий, где включены только те флаги, которые одновременно включены в обоих операндах. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Преобразует конкретный байт (8‑битный октет) в соответствующий [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), бросает исключение, если преобразование недействительно. |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Не создает текстовое оформление. Начальное значение.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Каждая строка текста подчеркнута.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Каждая строка текста имеет линию над ней.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Каждая строка текста имеет линию посередине.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Указывает, имеет ли этот экземпляр начальное значение \\u2014 None


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Указывает, включено ли подчеркивание (символ подчеркивания)


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Указывает, включена ли надстрочная линия


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Указывает, включено ли перечёркивание (зачёркивание)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Возвращает значение всех флагов в этом экземпляре в виде текста


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Возвращает значение всех флагов в этом экземпляре в виде текста


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Указывает, равен ли этот экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) указанному


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Другой экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|

**Returns:**
логический -  true  если равны,  false  иначе

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Указывает, равен ли этот экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) указанному без приведения типов


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | java.lang.Object | Другой экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), приведённый к объекту. |
|

**Returns:**
логический -  true  если равны,  false  иначе

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код этого экземпляра


**Returns:**
int - Подписанный целочисленный хеш-код

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Проверяет, равны ли два значения "TextDecorationLineType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Первый операнд для проверки |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Второй операнд для проверки |
|

**Returns:**
логический -  true  если равны,  false  иначе

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Проверяет, не равны ли два значения "TextDecorationLineType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Первый операнд для проверки |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Второй операнд для проверки |
|

**Returns:**
boolean -  true  если не равны,  false  иначе

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Создаёт и возвращает экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) с флагами, определёнными указанными параметрами


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | isUnderline | boolean | Определяет, включён ли флаг подчёркивания |
|
|  | isOverline | boolean | Определяет, включён ли флаг надчеркивания |
|
|  | isLineThrough | boolean | Определяет, включён ли флаг зачеркивания |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Пытается разобрать указанную строку и вернуть корректный экземпляр [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | input | java.lang.String | Входная строка |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Результат. Если разбор недействителен, это значение #None.None |
|

**Returns:**
boolean -  true  если разбор прошёл успешно,  false  при ошибке

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Объединяет (сливает) два указанных типа линий и создаёт новый результирующий тип линии, где флаги объединены (объединение)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Первый операнд типа линии |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Второй операнд типа линии |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Вычитает второй указанный тип линии из первого указанного типа линии и создаёт новый результирующий тип линии, в котором присутствуют только те флаги из первого операнда, которые не найдены во втором операнде (разность)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Первый операнд типа линии |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Второй операнд типа линии |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Возвращает пересечение между первым и вторым типами линий, где включены только те флаги, которые одновременно включены в обоих операндах. Имеет наивысший приоритет среди всех операторов (выше, чем объединение и разность).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Первый операнд типа линии |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Второй операнд типа линии |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Преобразует конкретный байт (8‑битный октет) в соответствующий [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), бросает исключение, если преобразование недействительно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | octet | byte | 8-битный октет (битовое поле), где первые 5 битов равны нулю, а последние 3 указывают флаги |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
