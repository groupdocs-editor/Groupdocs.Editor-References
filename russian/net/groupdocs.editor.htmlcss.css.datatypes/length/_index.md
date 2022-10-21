---
title: Length
second_title: Справочник по API GroupDocs.Editor для .NET
description: Представляет значение длины CSS в любых поддерживаемых единицах включая проценты и безразмерный тип. Значения могут быть целыми или плавающими отрицательными нулевыми и положительными. Неизменяемая структура.
type: docs
weight: 190
url: /ru/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Представляет значение длины CSS в любых поддерживаемых единицах, включая проценты и безразмерный тип. Значения могут быть целыми или плавающими, отрицательными, нулевыми и положительными. Неизменяемая структура.

```csharp
public struct Length : ICloneable, IEquatable<  >, IEquatable<Length>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Возвращает числовое значение с плавающей запятой экземпляра Length. Никогда не выдает исключение — при необходимости преобразует целочисленное значение в число с плавающей запятой. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Возвращает целочисленное числовое значение этого экземпляра Length, если оно внутренне сохранено как целое число, или выдает исключение, если изначально оно было сохранено как число с плавающей запятой. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Получает, если длина указана в абсолютных единицах. Такая длина может быть преобразована в пиксели. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Указывает, имеет ли этот экземпляр Length значение по умолчанию — безразмерный ноль. То же, что и свойство IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Указывает, было ли числовое значение этого экземпляра Length изначально задано и сохранено как число с плавающей запятой (FP32) |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Указывает, было ли числовое значение этого экземпляра Length изначально задано и сохранено как целое число (INT32) number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Определяет, является ли числовое значение этой длины отрицательным числом |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Определяет, является ли числовое значение этой длины положительным числом |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Получает, если длина задана в относительных единицах. Такая длина не может быть преобразована в пиксели. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Значение имеет безразмерный тип, но не является нулем - положительным или отрицательным числом |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Определяет, является ли данный экземпляр безразмерным нулем или нет. Безразмерный ноль является значением по умолчанию для этого типа. То же, что и свойство IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Определяет, является ли числовое значение этой длины нулевым числом |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Возвращает тип единицы измерения этого экземпляра Length. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Создает и возвращает экземпляр типа Length по указанному двойному числу и unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Создает и возвращает экземпляр типа Length по заданному числу с плавающей запятой и unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Создает и возвращает экземпляр типа Length по заданному целому числу и unit |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Анализирует и возвращает указанную строку как значение длины, включая ее числовое значение и имя единицы измерения, или выдает исключение при сбое |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Возвращает полную копию этого экземпляра Length |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Определяет, равно ли это значение другой заданной длине |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Определяет, равна ли эта длина указанному object |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Вычисляет и возвращает хэш-код этого экземпляра Length путем объединения хэш-кодов значения и типа единицы измерения |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Возвращает строковое представление этой длины в исходной исходной форме (в том виде, в каком она хранится), без преобразования значения длины в какую-либо другую единицу измерения type |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Преобразует длину в заданные единицы, если это возможно. Если current или данный блок являются относительными, будет выдано исключение. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Преобразует длину в число пикселей, если это возможно. Если текущая единица является относительной, будет выдано исключение. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Возвращает строковое представление этой длины в единицах измерения указанного типа. Числовое значение будет преобразовано в соответствии с изменением типа единицы измерения. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Пытается проанализировать указанное имя юнита и вернуть соответствующее значение Unit enum. Возвращает Unit.Unitless, если не может найти подходящий юнит. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Пытается проанализировать указанную строку как значение длины, включая ее числовое значение и имя единицы измерения |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Проверяет равенство двух заданных длин. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Проверяет неравенство двух заданных длин. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Безразмерный целочисленный ноль — значение по умолчанию, то же, что и конструктор без параметров по умолчанию |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [Unit](length.unit) | Все поддерживаемые единицы длины |

### Примечания

Этот тип охватывает следующие типы данных CSS: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/процент

### Смотрите также

* пространство имен [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
