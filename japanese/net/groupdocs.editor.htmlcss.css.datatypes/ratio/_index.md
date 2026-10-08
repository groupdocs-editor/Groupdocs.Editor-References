---
title: "比率"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "比率 CSS データ型を表します。このデータ型はメディアクエリでのアスペクト比やラスタ画像で、分子と分母と呼ばれる単位なしの2つの値の比率を示すために使用されます。変更不可能な構造体です。"
type: docs
weight: 250
url: /ja/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

メディアクエリでのアスペクト比やラスタ画像で「分子」および「分母」と呼ばれる単位なしの2つの値間の比率を示すために使用される「ratio」CSS データ型を表します。変更不可能な構造体です。

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | この比率の分母を返します |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/isdefault) { get; } | この比率がデフォルト値か、\"1/1\"（シングル）であるかを判定します |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | この比率の分子を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | 指定された分子と分母から Ratio インスタンスを作成し、返します |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | この比率を単一の浮動小数点数として計算し、返します |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | この比率の完全なコピーを返します |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | このインスタンスが指定されたキャストされていないオブジェクト（おそらく別の \"Ratio\" インスタンス）と等しいかどうかを判定します |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | このインスタンスが指定された \"Ratio\" インスタンスと等しいかどうかを判定します |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | このインスタンスのハッシュコードを返します。ライフタイム中に変更できません。 |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | この比率の逆（倒数）比率を生成し、返します |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | この比率を文字列にシリアライズし、返します |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | この比率の文字列表現を返します；\"SerializeDefault()\" と同じです |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | 2つの比率を比較し、両者が一致するかを示すブール値を返します。 |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | 2つの比率を比較し、両者が一致しないかを示すブール値を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | シングルのデフォルト比率 1/1 |

### 備考

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### 参照

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
