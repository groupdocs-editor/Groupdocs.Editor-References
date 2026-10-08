---
title: "Length"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "パーセンテージや単位なしタイプを含む、サポート可能な任意の単位で CSS の長さ値を表します。値は整数または浮動小数点、負のゼロ、正の数になる可能性があります。変更不可能な構造です。"
type: docs
weight: 230
url: /ja/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

パーセンテージや単位なしタイプを含む、サポート可能な任意の単位での CSS 長さ値を表します。値は整数または浮動小数点、負、ゼロ、正のいずれでも可能です。変更不可能な構造体です。

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Length インスタンスの浮動小数点数値を返します。例外は決してスローせず、必要に応じて整数値を浮動小数点に変換します。 |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | この Length インスタンスが内部的に整数として保存されている場合は整数値を返し、元々浮動小数点数として保存されていた場合は例外をスローします。 |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | 長さが絶対単位で指定されているか取得します。そのような長さはピクセルに変換できる場合があります。 |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | この Length インスタンスがデフォルト値（単位なしのゼロ）を持つかどうかを示します。IsUnitlessZero プロパティと同等です。 |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | この Length インスタンスの数値が元々浮動小数点（FP32）として指定・保存されていたかどうかを示します |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | この Length インスタンスの数値が元々整数（INT32）として指定・保存されていたかどうかを示します |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | この長さの数値が負の数かどうかを判断します |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | この長さの数値が正の数かどうかを判断します |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | 長さが相対単位で指定されているか取得します。そのような長さはピクセルに変換できません。 |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | この値は単位なしタイプですが、ゼロではなく正または負の数です |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | このインスタンスが単位なしのゼロかどうかを判定します。単位なしのゼロはこの型のデフォルト値です。IsDefault プロパティと同等です。 |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | この長さの数値がゼロかどうかを判定します。 |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | この Length インスタンスの単位タイプを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | 指定された double 値と単位で Length 型のインスタンスを作成し、返します。 |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | 指定された float 値と単位で Length 型のインスタンスを作成し、返します。 |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | 指定された整数値と単位で Length 型のインスタンスを作成し、返します。 |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | 指定された文字列を解析し、数値と単位名を含む Length 値として返します。失敗した場合は例外をスローします。 |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | この Length インスタンスの完全なコピーを返します。 |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | この値が他の指定された長さと等しいかどうかを定義します。 |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | この長さが指定されたオブジェクトと等しいかどうかを判定します。 |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | 値と単位タイプのハッシュコードを組み合わせて、この Length インスタンスのハッシュコードを計算し、返します。 |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | この長さを元のネイティブ形式（保存されているまま）で文字列として返します。別の単位タイプに変換しません。 |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | 可能であれば長さを指定された単位に変換します。現在または指定された単位が相対的な場合は例外がスローされます。 |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | 可能であれば長さをピクセル数に変換します。現在の単位が相対的な場合は例外がスローされます。 |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | 指定された単位タイプでこの長さを文字列として返します。数値は単位タイプの変更に応じて変換されます。 |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | 指定された単位名を解析し、対応する Unit 列挙体の値を返します。適切な単位が見つからない場合は Unit.Unitless を返します。 |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | 指定された文字列を解析し、数値と単位名を含む Length 値として取得しようとします。 |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | 与えられた 2 つの長さの等価性をチェックします。 |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | 与えられた 2 つの長さの不等価性をチェックします。 |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | 与えられた Length を指定された係数で乗算します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | 単位なし整数ゼロ - デフォルト値で、パラメータなしのデフォルトコンストラクタと同じです。 |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [Unit](length.unit) | サポートされているすべての長さ単位 |

### 備考

この型は次の CSS データ型をカバーします: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### 参照

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
