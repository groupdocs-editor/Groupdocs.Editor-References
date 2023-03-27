---
title: ArgbColor
second_title: GroupDocs.Editor for .NET API リファレンス
description: コンバーターとシリアライザーを使用して ARGB 形式で 1 つの色の値を表します
type: docs
weight: 190
url: /ja/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

コンバーターとシリアライザーを使用して ARGB 形式で 1 つの色の値を表します

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | 色のアルファ部分を取得します. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | 色のアルファ部分をパーセントで取得します (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | 色の青の部分を取得します。 |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | 色の緑の部分を取得します. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | 初期化されていない色 - 4 つのチャネルすべてが 0 に設定されています。デフォルトおよび透明と同じです。 |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | これが[`ArgbColor`](../argbcolor)インスタンスは完全に不透明で、透明度はありません (そのアルファ チャンネルには最大値があります) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | これが[`ArgbColor`](../argbcolor)インスタンスは完全に透過的です - そのアルファ チャネルには最小値 (0) があるため、他の R、G、および B チャネルには目に見える効果はありません。 |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | これが[`ArgbColor`](../argbcolor)インスタンスは半透明です (完全に透明ではありませんが、完全に不透明でもありません) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | 色の赤い部分を取得します. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | 色の Int32 値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | 作成します[`ArgbColor`](../argbcolor)指定された赤、緑、青のチャネルからの値、アルファ チャネルは完全に不透明 |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | 作成します[`ArgbColor`](../argbcolor)指定された赤、緑、青、およびアルファ チャネルからの値 |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | 単一の値から完全に不透明 (A=255) の色を作成し、すべてのチャンネルに適用されます |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | 2 をチェック[`ArgbColor`](../argbcolor)equality の色 |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | 別のオブジェクトがこれと等しいかどうかをテストします[`ArgbColor`](../argbcolor)インスタンス. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | 現在の色を定義するハッシュ コードを返します。 |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | これをシリアル化します[`ArgbColor`](../argbcolor)translucency に応じて最も適切な CSS 関数表記へのインスタンス |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | これをシリアル化します[`ArgbColor`](../argbcolor)「rgb」CSS 関数 notation のインスタンス |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | これをシリアル化します[`ArgbColor`](../argbcolor)「rgba」CSS 関数 notation のインスタンス |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | と同じ[`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | 2 つの色を比較し、2 つの色が一致するかどうかを示すブール値を返します。 |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | 2 つの色を比較し、2 つの色が一致しないかどうかを示すブール値を返します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | CSS 標準で固定された一意の名前と値を持つすべての「既知の色」が含まれます |

### 備考

このタイプは、CSS 操作に役立つように設計されています (ただし、CSS 操作に限定されません)。もっと見る: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### 関連項目

* interface [ICssDataType](../icssdatatype)
* 名前空間 [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->