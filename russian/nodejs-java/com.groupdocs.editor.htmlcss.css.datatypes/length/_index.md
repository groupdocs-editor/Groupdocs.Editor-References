---
title: "Length"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет значение длины CSS в любой поддерживаемой единице, включая проценты    и тип без единицы."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Представляет значение длины CSS в любой поддерживаемой единице, включая проценты
и тип без единицы. Значения могут быть целыми или с плавающей точкой, отрицательными, нулевыми и
положительными. Неизменяемая структура.

*** ** * ** ***


Этот тип охватывает следующие типы данных CSS:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Length()](#Length--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Нулевое целое без единицы — значение по умолчанию, то же, что значение по умолчанию без параметров |
конструктор
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Создаёт и возвращает экземпляр типа Length по указанному числу с плавающей точкой |
и единица
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Создаёт и возвращает экземпляр типа Length по указанному числу двойной точности |
и единица
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Создает и возвращает экземпляр типа Length, заданный указанным целым числом |
число и единица измерения
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Определяет, является ли этот экземпляр безразмерным нулём или нет. |
|
|  | [isDefault()](#isDefault--) | Указывает, имеет ли этот экземпляр Length значение по умолчанию \u2014 безразмерное |
ноль.
|
|  | [getUnitType()](#getUnitType--) | Возвращает тип единицы измерения этого экземпляра Length. |
|
|  | [isInteger()](#isInteger--) | Указывает, было ли числовое значение этого экземпляра Length |
изначально задано и сохранено как целое число (INT32)
|
|  | [isFloat()](#isFloat--) | Указывает, было ли числовое значение этого экземпляра Length |
изначально задано и сохранено как число с плавающей точкой (FP32)
|
|  | [getFloatValue()](#getFloatValue--) | Возвращает числовое значение с плавающей точкой экземпляра Length. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Возвращает целочисленное числовое значение этого экземпляра Length, если оно |
внутренне сохранено как целое число, или генерирует исключение, если оно было
изначально сохранено как число с плавающей точкой.
|
|  | [isAbsolute()](#isAbsolute--) | Получает, задана ли длина в абсолютных единицах. |
|
|  | [isRelative()](#isRelative--) | Получает, задана ли длина в относительных единицах. |
|
|  | [isZero()](#isZero--) | Определяет, является ли числовое значение этой длины нулём |
|
|  | [isNegative()](#isNegative--) | Определяет, является ли числовое значение этой длины отрицательным числом |
|
|  | [isPositive()](#isPositive--) | Определяет, является ли числовое значение этой длины положительным числом |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | Значение имеет безразмерный тип, но не является нулём — положительным или отрицательным |
number
|
|  | [toPixel()](#toPixel--) | Преобразует длину в количество пикселей, если возможно. |
|
|  | [to(int unit)](#to-int-) | Преобразует длину в указанную единицу, если возможно. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Возвращает строковое представление этой длины в указанном типе единицы. |
|
|  | [serializeDefault()](#serializeDefault--) | Возвращает строковое представление этой длины в её оригинальном родном |
формате (как он хранится), без преобразования значения длины в другую
единицу измерения
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Определяет, равно ли это значение другой указанной длине |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равна ли эта длина указанному объекту |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Умножает заданную длину на указанный коэффициент |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Проверяет равенство двух заданных длин. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Проверяет неравенство двух заданных длин. |
|
|  | [hashCode()](#hashCode--) | Вычисляет и возвращает хеш-код этого экземпляра Length, комбинируя |
хеш-коды значения и типа единицы измерения
|
|  | [deepClone()](#deepClone--) | Возвращает полную копию этого экземпляра Length |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Пытается разобрать указанное название единицы и вернуть соответствующее значение a |
Перечисление Unit.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Пытается разобрать указанную строку как значение Length, включая её |
числовое значение и название единицы
|
|  | [parse(String input)](#parse-java.lang.String-) | Разбирает и возвращает указанную строку как значение Length, включая её |
числовое значение и название единицы, либо бросает исключение при ошибке
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Нулевое целое без единицы — значение по умолчанию, то же, что значение по умолчанию без параметров
конструктор


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


Создаёт и возвращает экземпляр типа Length по указанному числу с плавающей точкой
и единица


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | float | \>Любое число с плавающей точкой (FP32) |
|
|  | единица | int | Любой допустимый тип единицы |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Создаёт и возвращает экземпляр типа Length по указанному числу двойной точности
и единица


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | double | Любое число double (FP64), которое будет преобразовано в float (FP32) |
|
|  | единица | int | Любой допустимый тип единицы |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Создает и возвращает экземпляр типа Length, заданный указанным целым числом
число и единица измерения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Любое целое число |
|
|  | единица | int | Любой допустимый тип единицы |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Определяет, является ли этот экземпляр нулём без единицы измерения или нет. Ноль без единицы измерения
является значением по умолчанию этого типа. То же, что свойство IsDefault.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Указывает, имеет ли этот экземпляр Length значение по умолчанию \u2014 безразмерное
ноль. То же, что свойство IsUnitlessZero.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Возвращает тип единицы измерения этого экземпляра Length.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Указывает, было ли числовое значение этого экземпляра Length
изначально задано и сохранено как целое число (INT32)


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Указывает, было ли числовое значение этого экземпляра Length
изначально задано и сохранено как число с плавающей точкой (FP32)


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Возвращает числовое значение float экземпляра Length. Никогда не бросает
исключение — преобразует значение Integer в Float при необходимости.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Возвращает целочисленное числовое значение этого экземпляра Length, если оно
внутренне сохранено как целое число, или генерирует исключение, если оно было
изначально сохранено как число с плавающей точкой.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Получает, указана ли длина в абсолютных единицах. Такая длина может быть
преобразована в пиксели.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Получает, указана ли длина в относительных единицах. Такая длина не может быть
преобразована в пиксели.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Определяет, является ли числовое значение этой длины нулём


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Определяет, является ли числовое значение этой длины отрицательным числом


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Определяет, является ли числовое значение этой длины положительным числом


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


Значение имеет безразмерный тип, но не является нулём — положительным или отрицательным
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Преобразует длину в количество пикселей, если возможно. Если текущая
единица относительная, будет выброшено исключение.


**Returns:**
float — количество пикселей, представляемое текущей длиной.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Преобразует длину в указанную единицу, если возможно. Если текущая или
указанная единица относительная, будет выброшено исключение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | единица | int | Единица, в которую нужно преобразовать. |
|

**Returns:**
float — значение в указанной единице текущей длины.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Возвращает строковое представление этой длины в указанном типе единицы.
Числовое значение будет преобразовано в соответствии с изменением типа единицы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | единица | int | Указанная единица, в которую этот экземпляр должен быть преобразован перед сериализацией в строку. Должна быть действительной. Не может быть без единицы. |
|

**Returns:**
java.lang.String — строковое представление

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Возвращает строковое представление этой длины в её оригинальном родном
формате (как он хранится), без преобразования значения длины в другую
единицу измерения


**Returns:**
java.lang.String — экземпляр строки

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Определяет, равно ли это значение другой указанной длине


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Другой экземпляр типа Length |
|

**Returns:**
boolean — true, если равны, иначе false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равна ли эта длина указанному объекту


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой экземпляр типа Length, упакованный в System.Object или любой другой абстрактный тип или интерфейс |
|

**Returns:**
boolean — true, если равны, иначе false

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Умножает заданную длину на указанный коэффициент


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length — множитель |
|
|  | коэффициент | int | Произвольное целое число — коэффициент |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Проверяет равенство двух заданных длин.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Левый операнд длины. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Правый операнд длины. |
|

**Returns:**
boolean — true, если обе длины равны, иначе false.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Проверяет неравенство двух заданных длин.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Левый операнд длины. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Правый операнд длины. |
|

**Returns:**
boolean — true, если обе длины не равны, иначе false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Вычисляет и возвращает хеш-код этого экземпляра Length, комбинируя
хеш-коды значения и типа единицы измерения


**Returns:**
int — целое число

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Возвращает полную копию этого экземпляра Length


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Пытается разобрать указанное название единицы и вернуть соответствующее значение a
Перечисление Unit. Возвращает LengthUnit.Unitless, если не удалось найти подходящий LengthUnit.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | unitName | java.lang.String | String, представляющая название единицы |
|

**Returns:**
int — значение перечисления Unit в любом случае, LengthUnit.Unitless, если не удалось найти подходящую единицу

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Пытается разобрать указанную строку как значение Length, включая её
числовое значение и название единицы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | input | java.lang.String | Input string, которую следует разобрать |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Output parameter, содержащий результат разбора. Если разбор не удался, содержит значение Length по умолчанию \\u2014 безразмерный ноль. |
|

**Returns:**
boolean — true, если разбор успешен, false, если неуспешен

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Разбирает и возвращает указанную строку как значение Length, включая её
числовое значение и название единицы, либо бросает исключение при ошибке


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | input | java.lang.String | Input string, которую следует разобрать |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

