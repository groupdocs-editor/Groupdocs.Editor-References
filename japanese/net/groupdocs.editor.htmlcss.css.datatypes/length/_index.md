---
title: Length
second_title: GroupDocs.Editor for .NET API リファレンス
description: CSS の長さの値をパーセンテージや単位のないタイプなどサポート可能な単位で表します 値は整数または浮動小数負ゼロ正のいずれかです不変の構造体.
type: docs
weight: 260
url: /ja/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

CSS の長さの値を、パーセンテージや単位のないタイプなど、サポート可能な単位で表します。 値は、整数または浮動小数、負、ゼロ、正のいずれかです。不変の構造体.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Length インスタンスの float 数値を返します。例外をスローしません - 必要に応じて整数値を浮動小数点数に変換します. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | この Length インスタンスの整数値を返します (内部的に整数として格納されている場合は 、または最初に浮動小数点数として格納されていた場合は例外をスローします. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | 長さが絶対単位で指定されているかどうかを取得します。このような長さは、ピクセルに変換できます。 |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | この Length インスタンスの数値が最初に指定され、浮動小数点数 (FP32) として格納されたかどうかを示します number |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | この Length インスタンスの数値が元々指定され、整数 (INT32) として格納されていたかどうかを示します number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | この長さの数値が負の数値かどうかを判断します |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | この長さの数値が正数かどうかを判断します |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | 長さが相対単位で指定されているかどうかを取得します。このような長さはピクセルに変換できません. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | 値は単位のないタイプですが、ゼロではありません - 正または負の数値 |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | このインスタンスが単位のないゼロかどうかを決定します。単位なしのゼロは、このタイプのデフォルト値です。 IsDefault プロパティと同じ. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | この長さの数値がゼロかどうかを判断します |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | この長さインスタンスの単位タイプを返します. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | 指定された double 数と unit によって長さ型のインスタンスを作成して返します |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | 指定された浮動小数点数と unit で長さ型のインスタンスを作成して返します |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | 指定された整数と unit で長さ型のインスタンスを作成して返します |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | 指定された文字列を解析して長さの値 (数値と単位名を含む) として返すか、失敗時に例外をスローします |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | この長さインスタンスの完全なコピーを返します |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | この値が他の指定された長さと等しいかどうかを定義します |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | この長さが指定されたオブジェクトと等しいかどうかを判断します object |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | 値と単位 type のハッシュ コードを組み合わせて、この Length インスタンスのハッシュ コードを計算して返します。 |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | 長さの値を他の単位 type に変換せずに、元のネイティブ形式 (保存されているとおり) でこの長さの文字列表現を返します。 |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | 可能であれば、長さを指定された単位に変換します。 current または指定された単位が相対的な場合、例外がスローされます. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | 可能であれば、長さをピクセル数に変換します。 現在の単位が相対的な場合、例外がスローされます。 |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | 指定された単位タイプでこの長さの文字列表現を返します。数値は単位の種類の変更に対応して変換されます. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | 指定されたユニット名の解析を試み、対応する Unit 列挙値を返します。 適切なユニットが見つからない場合は、Unit.Unitless を返します。 |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | 数値と単位名を含む、指定された文字列を長さの値として解析しようとします |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | 指定された 2 つの長さが等しいことを確認します。 |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | 指定された 2 つの長さの不等式をチェックします。 |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | 指定された長さを指定された係数に乗算します |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | 単位のない整数ゼロ - デフォルト値、デフォルトのパラメーターなしのコンストラクターと同じ |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [Unit](length.unit) | サポートされているすべての長さ単位 |

### 備考

この型は次の CSS データ型をカバーします: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/percentage

### 関連項目

* interface [ICssDataType](../icssdatatype)
* 名前空間 [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
