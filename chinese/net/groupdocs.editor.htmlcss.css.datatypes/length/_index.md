---
title: Length
second_title: GroupDocs.Editor for .NET API 参考
description: 表示任何支持单位的 CSS 长度值包括百分比和无单位类型 值可以是整数或浮点数负数零和正数不可变结构.
type: docs
weight: 260
url: /zh/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

表示任何支持单位的 CSS 长度值，包括百分比和无单位类型。 值可以是整数或浮点数、负数、零和正数。不可变结构.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | 返回 Length 实例的浮点数值。从不抛出异常 - 如有必要，将 Integer 值转换为 Float. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | 返回此 Length 实例的整数数值，如果它在内部存储为整数， 或抛出异常，如果它最初存储为浮点数。 |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | 如果长度以绝对单位给出则获取。这样的长度可能会转换为像素。 |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | 表示这个 Length 实例的数值最初是否指定并存储为浮点数 (FP32) number |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | 表示这个Length实例的数值最初是否指定并存储为整数（INT32） number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | 判断这个长度的数值是否为负数 |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | 判断这个长度的数值是否为正数 |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | 获取长度是否以相对单位给出。这样的长度无法转换为像素。 |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | 该值具有无单位类型，但不是零 - 正数或负数 |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | 确定此实例是否为无单位零。无单位零是这种类型的默认值。与 IsDefault 属性相同。 |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | 判断这个长度的数值是否为零数 |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | 返回此 Length 实例的单位类型。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | 通过指定的双精度数和 unit 创建并返回 Length 类型的实例 |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | 通过指定的浮点数和 unit 创建并返回 Length 类型的实例 |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | 通过指定的整数和 unit 创建并返回 Length 类型的实例 |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | 解析并返回指定的字符串作为长度值，包括其数值和单位名称，或在失败时抛出异常 |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | 返回此长度 instance 的完整副本 |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | 定义这个值是否等于另一个指定的length |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | 判断这个长度是否等于指定的object |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | 通过组合值和单元类型的哈希码来计算并返回此 Length 实例的哈希码 |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | 以其原始本机形式（存储时）返回此长度的字符串表示形式，而不将长度值转换为其他一些单位 type |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | 如果可能，将长度转换为给定单位。如果 current 或给定单位是相对的，那么将抛出异常。 |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | 如果可能，将长度转换为像素数。如果 当前单位是相对的，那么会抛出异常。 |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | 以指定单位类型返回此长度的字符串表示形式。数值将根据单位类型的变化进行转换。 |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | 尝试解析指定的单元名称并返回相应的单元枚举值。 如果找不到合适的单元，则返回 Unit.Unitless。 |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | 尝试将指定字符串解析为长度值，包括其数值和单位名称 |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | 检查两个给定长度的相等性。 |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | 检查两个给定长度的不等式。 |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | 将给定长度乘以给定因子 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | 无单位整数零 - 默认值，与默认无参数构造函数 相同 |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| enum [Unit](length.unit) | 所有支持的长度单位 |

### 评论

此类型涵盖下一个 CSS 数据类型： https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/percentage

### 也可以看看

* interface [ICssDataType](../icssdatatype)
* 命名空间 [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* 部件 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
