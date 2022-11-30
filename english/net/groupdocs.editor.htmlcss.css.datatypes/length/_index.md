---
title: Length
second_title: GroupDocs.Editor for .NET API Reference
description: Represents a CSS length value in any supportable unit including percentage and unitless type. Values may be integer or float negative zero and positive. Immutable structure.
type: docs
weight: 1040
url: /net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Represents a CSS length value in any supportable unit, including percentage and unitless type. Values may be integer or float, negative, zero and positive. Immutable structure.

```csharp
public struct Length : ICloneable, IEquatable<ICssDataType>, IEquatable<Length>
```

## Properties

| Name | Description |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Returns a float numeric value of the Length instance. Never throws an exception - converts Integer value to Float if necessary. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Returns an integer numeric value of this Length instance, if it is internally stored as an integer, or throws an exception, if it was originally stored as a float number. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Gets if the length is given in absolute units. Such a length may be converted to pixels. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Indicates whether this Length instance has a default value — unitless zero. Same as IsUnitlessZero property. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Indicates whether the numeric value of this Length instance was originally specified and stored as a float (FP32) number |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Indicates whether the numeric value of this Length instance was originally specified and stored as an integer (INT32) number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Determines whether the numeric value of this length is a negative number |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Determines whether the numeric value of this length is a positive number |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Gets if the length is given in relative units. Such a length cannot be converted to pixels. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | The value has unitless type, but is not a zero - positive or negative number |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Determines whether this instance is a unitless zero or not. Unitless zero is default value of this type. Same as IsDefault property. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Determines whether the numeric value of this length is a zero number |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Returns a unit type of this Length instance. |

## Methods

| Name | Description |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Creates and returns an instance of Length type by specified double number and unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Creates and returns an instance of Length type by specified float number and unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Creates and returns an instance of Length type by specified integer number and unit |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Parses and returns specified string as a Length value, including its numeric value and unit name, or throws an exception on failure |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Returns a full copy of this Length instance |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Defines whether this value is equal to the other specified length |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Determines whether this length is equal to specified object |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Calculates and returns a hash-code of this Length instance by combining hash-codes of the value and unit type |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Returns a string representation of this length in its original native form (as it is stored), without converting length value to some other unit type |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Converts the length to the given unit, if possible. If the current or given unit is relative, then an exception will be thrown. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Converts the length to a number of pixels, if possible. If the current unit is relative, then an exception will be thrown. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Returns a string representation of this length in specified unit type. Numeric value will be converted in corresponding to unit type change. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Tries to parse specified unit name and return corresponding value of a Unit enum. Returns Unit.Unitless if cannot find appropriate unit. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Tries to parse a specified string as a Length value, including its numeric value and unit name |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Checks the equality of the two given lengths. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Checks the inequality of the two given lengths. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Unitless integer zero - default value, the same as default parameterless constructor |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Other Members

| Name | Description |
| --- | --- |
| enum [Unit](length.unit) | All supported length units |

### Remarks

This type covers the next CSS data types: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### See Also

* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
