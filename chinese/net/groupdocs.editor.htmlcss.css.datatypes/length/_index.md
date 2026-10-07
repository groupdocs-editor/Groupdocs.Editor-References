---
title: "Length"
second_title: "GroupDocs.Editor for .NET API 参考"
description: "表示 CSS 长度值，可使用任何支持的单位，包括百分比和无单位类型。值可以是整数或浮点数、负数、零和正数。不可变结构。"
type: docs
weight: 230
url: /zh/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

表示 CSS 长度值，可使用任何支持的单位，包括百分比和无单位类型。值可以是整数或浮点数，负数、零或正数。不可变结构。

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | 返回 Length 实例的浮点数值。永不抛出异常——必要时将整数值转换为浮点数。 |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | 返回此 Length 实例的整数数值（如果内部存储为整数），否则如果最初存储为浮点数则抛出异常。 |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | 获取长度是否以绝对单位给出。此类长度可以转换为像素。 |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | 指示此 Length 实例是否具有默认值——无单位的零。等同于 IsUnitlessZero 属性。 |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | 指示此 Length 实例的数值是否最初被指定并存储为浮点数（FP32） |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | 指示此 Length 实例的数值是否最初被指定并存储为整数（INT32） |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | 确定此长度的数值是否为负数 |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | 确定此长度的数值是否为正数 |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | 获取长度是否以相对单位给出。此类长度无法转换为像素。 |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | 该值为无单位类型，但不是零——为正数或负数 |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | 确定此实例是否为无单位零。无单位零是此类型的默认值。与 IsDefault 属性相同。 |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | 确定此长度的数值是否为零 |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | 返回此 Length 实例的单位类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | 通过指定的 double 数值和单位创建并返回 Length 类型的实例 |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | 通过指定的 float 数值和单位创建并返回 Length 类型的实例 |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | 通过指定的整数数值和单位创建并返回 Length 类型的实例 |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | 解析并返回指定字符串为 Length 值，包括其数值和单位名称，若失败则抛出异常 |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | 返回此 Length 实例的完整副本 |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | 定义此值是否等于另一个指定的长度 |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | 确定此长度是否等于指定的对象 |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | 通过组合数值和单位类型的哈希码，计算并返回此 Length 实例的哈希码 |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | 以其原始本机形式（存储时的形式）返回此长度的字符串表示，不会将长度值转换为其他单位类型 |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | 将长度转换为给定单位（如果可能）。如果当前单位或给定单位是相对的，则会抛出异常。 |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | 将长度转换为像素数（如果可能）。如果当前单位是相对的，则会抛出异常。 |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | 以指定的单位类型返回此长度的字符串表示。数值将根据单位类型的变化进行转换。 |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | 尝试解析指定的单位名称并返回对应的 Unit 枚举值。如果找不到合适的单位，则返回 Unit.Unitless。 |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | 尝试将指定字符串解析为 Length 值，包括其数值和单位名称 |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | 检查两个给定长度的相等性。 |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | 检查两个给定长度的不等性。 |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | 将给定的 Length 与给定因子相乘 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | 无单位整数零 - 默认值，与默认无参数构造函数相同 |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [Unit](length.unit) | 所有支持的长度单位 |

### 备注

此类型涵盖以下 CSS 数据类型：https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### 另请参见

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
