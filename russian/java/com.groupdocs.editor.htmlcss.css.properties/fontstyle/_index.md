---
title: "FontStyle"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Определяет, как шрифт должен быть оформлен с нормальным, курсивным или наклонным начертанием из его семейства шрифтов."
type: docs
weight: 11
url: /ru/java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Определяет, как шрифт должен быть оформлен: обычный, курсивный или наклонный стиль из его семейства шрифтов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [Normal](#Normal) | Выбирает шрифт, классифицированный как нормальный в рамках семейства шрифтов. |
|
|  | [Italic](#Italic) | Выбирает шрифт, классифицированный как курсив. |
|
|  | [Oblique](#Oblique) | Выбирает шрифт, классифицированный как наклонный. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isInitial()](#isInitial--) | Указывает, имеет ли этот стиль шрифта начальное значение (Normal) |
|
|  | [getValue()](#getValue--) | Возвращает значение этого стиля шрифта в виде строки |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Определяет, равен ли этот экземпляр стиля шрифта указанному |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли этот экземпляр стиля шрифта указанному неприведенному |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Проверяет, равны ли два значения "FontStyle" |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Проверяет, не равны ли два значения "FontStyle" |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Пытается распознать указанное ключевое слово как корректное значение ключевого слова 'font-style' и вернуть его при успехе или NULL при неудаче. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Выбирает шрифт, классифицированный как нормальный в рамках семейства шрифтов. Начальное значение.


### Italic {#Italic}
```
public static final FontStyle Italic
```


Выбирает шрифт, классифицированный как курсив. Если версия шрифта в курсиве недоступна, используется версия, классифицированная как наклонный. Если ни одна из них недоступна, стиль имитируется искусственно.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Выбирает шрифт, классифицированный как наклонный. Если версия шрифта в наклонном виде недоступна, используется версия, классифицированная как курсив. Если ни одна из них недоступна, стиль имитируется искусственно.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Указывает, имеет ли этот стиль шрифта начальное значение (Normal)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Возвращает значение этого стиля шрифта в виде строки


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Определяет, равен ли этот экземпляр стиля шрифта указанному


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Другой экземпляр стиля шрифта |
|

**Returns:**
boolean - true если равны, false иначе

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли этот экземпляр стиля шрифта указанному неприведенному


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой неконвертированный экземпляр font-style, может быть null |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Проверяет, равны ли два значения "FontStyle"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Первое значение для проверки |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Второе значение для проверки |
|

**Returns:**
boolean - true если равны, false иначе

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Проверяет, не равны ли два значения "FontStyle"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Первое значение для проверки |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Второе значение для проверки |
|

**Returns:**
boolean - false если равны, true иначе

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Пытается распознать указанное ключевое слово как корректное значение ключевого слова 'font-style' и вернуть его при успехе или NULL при неудаче.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | ключевое слово | java.lang.String | Ключевое слово для разбора |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Результат, если разбор был успешным, иначе #Normal.Normal |
|

**Returns:**
boolean - true если разбор был успешным, false иначе

