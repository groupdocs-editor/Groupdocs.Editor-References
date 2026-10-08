---
title: "ArgbColor"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "32 ビット ARGB 形式（各チャンネル 8 ビット）で透明度を含む 1 つの色値を表し、コンバータとシリアライザを備えています"
type: docs
weight: 160
url: /ja/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

変換器とシリアライザーを備えた、32 ビット ARGB 形式（透明度を含む各チャンネル 8 ビット）の単一カラー値を表します

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | 色のアルファ部分を取得します。 |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | 色のアルファ部分をパーセンテージ (0..1) で取得します。 |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | 色の青（ブルー）部分を取得します。 |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | 色の緑（グリーン）部分を取得します。 |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | この [`ArgbColor`](../argbcolor) インスタンスがデフォルト（透明）かどうかを示します - 4 つのチャンネルすべてが 0 に設定されています |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | 未初期化の色 - 4 つのチャンネルすべてが 0 に設定されています。デフォルトおよび透明と同じです。 |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | この [`ArgbColor`](../argbcolor) インスタンスが完全に不透明かどうかを示します（透明度がなく、アルファチャンネルが最大値です） |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | この [`ArgbColor`](../argbcolor) インスタンスが完全に透明かどうかを示します - アルファチャンネルが最小値（0）であるため、他の R、G、B チャンネルは視覚的に影響しません。 |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | この [`ArgbColor`](../argbcolor) インスタンスが半透明かどうかを示します（完全に透明でもなく、完全に不透明でもありません） |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | 色の赤（レッド）部分を取得します。 |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | 色の Int32 値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | 指定された赤、緑、青チャンネルから 1 つの [`ArgbColor`](../argbcolor) 値を作成し、アルファチャンネルは完全に不透明にします |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | 指定された赤、緑、青、アルファチャンネルから 1 つの [`ArgbColor`](../argbcolor) 値を作成します |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | 単一の値から完全に不透明（A=255）な色を作成し、その値はすべてのチャンネルに適用されます |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | 2 つの [`ArgbColor`](../argbcolor) の色が等しいかどうかをチェックします |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | 別のオブジェクトがこの [`ArgbColor`](../argbcolor) インスタンスと等しいかどうかをテストします。 |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | 現在の色を定義するハッシュコードを返します。 |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | この [`ArgbColor`](../argbcolor) インスタンスを、半透明度に応じた最適な CSS 関数表記にシリアライズします |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | この [`ArgbColor`](../argbcolor) インスタンスを 'rgb' CSS 関数表記にシリアライズします |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | この [`ArgbColor`](../argbcolor) インスタンスを 'rgba' CSS 関数表記にシリアライズします |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | `[`SerializeDefault`](./serializedefault)` と同じです。 |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | 2 つの色を比較し、両者が一致するかどうかを示すブール値を返します。 |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | 2つの色を比較し、2つが一致しないかどうかを示すブール値を返します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | CSS 標準で固定されたユニークな名前と値を持つすべての「既知の色」を含みます |

### 備考

この型は CSS 操作に役立つように設計されています（ただしこれに限定されません）。詳細はこちら: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### 参照

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
