---
title: "Соотношение"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет тип данных CSS \"ratio\", который используется для описания соотношений сторон в медиазапросах и для растровых изображений, обозначая пропорцию между двумя безразмерными значениями, называемыми числителем и знаменателем."
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Представляет тип данных CSS "ratio", который используется для описания аспект
соотношений в медиазапросах и для растровых изображений, обозначая пропорцию
между двумя безразмерными значениями, называемыми "numerator" и "denominator". Неизменяемый
структура.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [Single](#Single) | Единственное значение по умолчанию ratio 1/1 |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Возвращает числитель этого ratio |
|
|  | [getDenominator()](#getDenominator--) | Возвращает знаменатель этого ratio |
|
|  | [calculate()](#calculate--) | Вычисляет и возвращает это ratio как одно число с плавающей точкой |
|
|  | [getInverseRatio()](#getInverseRatio--) | Создаёт и возвращает обратное (взаимное) ratio для этого ratio |
|
|  | [serializeDefault()](#serializeDefault--) | Сериализует это ratio в строку и возвращает её |
|
|  | [toString()](#toString--) | Возвращает строковое представление этого ratio; то же, что и |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | Определяет, имеет ли это ratio значение по умолчанию или является "1/1" (единственное) |
|
|  | [deepClone()](#deepClone--) | Возвращает полную копию этого отношения |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Определяет, равен ли этот экземпляр указанному экземпляру \"Ratio\" |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Определяет, равен ли данный экземпляр указанному неконвертированному объекту, |
который, предположительно, является другим экземпляром \"Ratio\"
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Сравнивает два отношения и возвращает логическое значение, указывающее, совпадают ли они. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Сравнивает два отношения и возвращает логическое значение, указывающее, что два не |
совпадают.
|
|  | [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра, который не может быть изменён во время его |
жизни
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Создаёт и возвращает один экземпляр Ratio из указанного числителя и |
знаменателя
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Единственное значение по умолчанию ratio 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Возвращает числитель этого ratio


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Возвращает знаменатель этого ratio


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Вычисляет и возвращает это ratio как одно число с плавающей точкой


**Returns:**
double — число с плавающей точкой двойной точности

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Создаёт и возвращает обратное (взаимное) ratio для этого ratio


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Сериализует это ratio в строку и возвращает её


**Returns:**
java.lang.String — строка в формате \"numerator/denominator\"

### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление этого ratio; то же, что и
"SerializeDefault()"


**Returns:**
java.lang.String — строка в формате \"numerator/denominator\"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Определяет, имеет ли это ratio значение по умолчанию или является "1/1" (единственное)


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Возвращает полную копию этого отношения


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Определяет, равен ли этот экземпляр указанному экземпляру \"Ratio\"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Другой экземпляр Ratio для проверки равенства с этим |
|

**Returns:**
boolean - True, если равны, false, если не равны

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Определяет, равен ли данный экземпляр указанному неконвертированному объекту,
который, предположительно, является другим экземпляром \"Ratio\"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | другой | java.lang.Object | Другой экземпляр System.Object, который, предположительно, имеет тип Ratio, для проверки равенства с этим |
|

**Returns:**
boolean - True, если равны, false, если не равны

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Сравнивает два отношения и возвращает логическое значение, указывающее, совпадают ли они.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Первое отношение для использования. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Второе отношение для использования. |
|

**Returns:**
boolean — true, если оба отношения равны, иначе false.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Сравнивает два отношения и возвращает логическое значение, указывающее, что два не
совпадают.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Первое отношение для использования. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Второе отношение для использования. |
|

**Returns:**
boolean — true, если оба отношения не равны, иначе false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра, который не может быть изменён во время его
жизни


**Returns:**
int — знаковое 4-байтовое целое, которое является неизменяемым для этого экземпляра

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Создаёт и возвращает один экземпляр Ratio из указанного числителя и
знаменателя


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | числитель | int | Числитель отношения. Должен быть строго положительным целым числом. |
|
|  | знаменателя | int | Знаменатель отношения. Должен быть строго положительным целым числом. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

