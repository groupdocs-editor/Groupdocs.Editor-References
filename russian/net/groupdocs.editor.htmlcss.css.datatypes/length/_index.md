---
title: "Длина"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет значение длины CSS в любой поддерживаемой единице, включая проценты и тип без единицы. Значения могут быть целыми или плавающими, отрицательными, нулем и положительными. Неизменяемая структура."
type: docs
weight: 230
url: /ru/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Представляет значение длины CSS в любой поддерживаемой единице, включая проценты и тип без единицы. Значения могут быть целыми или с плавающей точкой, отрицательными, нулевыми и положительными. Неизменяемая структура.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Возвращает числовое значение типа float экземпляра Length. Никогда не бросает исключение — при необходимости преобразует значение Integer в Float. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Возвращает числовое значение типа integer этого экземпляра Length, если оно хранится как целое, или бросает исключение, если изначально было сохранено как число с плавающей точкой. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Получает, указана ли длина в абсолютных единицах. Такая длина может быть преобразована в пиксели. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Указывает, имеет ли этот экземпляр Length значение по умолчанию — ноль без единицы. То же, что свойство IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Указывает, было ли числовое значение этого экземпляра Length изначально указано и сохранено как число float (FP32). |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Указывает, было ли числовое значение этого экземпляра Length изначально указано и сохранено как целое число (INT32). |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Определяет, является ли числовое значение этой длины отрицательным числом. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Определяет, является ли числовое значение этой длины положительным числом. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Получает, указана ли длина в относительных единицах. Такая длина не может быть преобразована в пиксели. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Значение имеет тип без единицы, но не является нулём — положительное или отрицательное число. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Определяет, является ли этот экземпляр нулём без единицы или нет. Ноль без единицы — значение по умолчанию этого типа. То же, что свойство IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Определяет, является ли числовое значение этой длины нулём. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Возвращает тип единицы этого экземпляра Length. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Создаёт и возвращает экземпляр типа Length по указанному числу double и единице. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Создаёт и возвращает экземпляр типа Length по указанному числу float и единице. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Создаёт и возвращает экземпляр типа Length по указанному целому числу и единице. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Разбирает и возвращает указанную строку как значение Length, включая её числовое значение и название единицы, или бросает исключение при ошибке. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Возвращает полную копию этого экземпляра Length. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Определяет, равна ли это значение другой указанной длине. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Определяет, равна ли эта длина указанному объекту. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Вычисляет и возвращает хеш‑код этого экземпляра Length, комбинируя хеш‑коды значения и типа единицы. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Возвращает строковое представление этой длины в её оригинальном нативном виде (как хранится), без преобразования значения длины в другой тип единицы. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Преобразует длину в указанную единицу, если это возможно. Если текущая или указанная единица относительная, будет выброшено исключение. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Преобразует длину в количество пикселей, если это возможно. Если текущая единица относительная, будет выброшено исключение. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Возвращает строковое представление этой длины в указанном типе единицы. Числовое значение будет преобразовано в соответствии с изменением типа единицы. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Пытается разобрать указанное название единицы и вернуть соответствующее значение перечисления Unit. Возвращает Unit.Unitless, если не удаётся найти подходящую единицу. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Пытается разобрать указанную строку как значение Length, включая её числовое значение и название единицы |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Проверяет равенство двух заданных длин. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Проверяет неравенство двух заданных длин. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Умножает заданную длину на указанный коэффициент |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Безразмерный целый ноль — значение по умолчанию, то же, что и конструктор без параметров по умолчанию |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [Unit](length.unit) | Все поддерживаемые единицы длины |

### Замечания

Этот тип охватывает следующие типы данных CSS: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### См. также

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
