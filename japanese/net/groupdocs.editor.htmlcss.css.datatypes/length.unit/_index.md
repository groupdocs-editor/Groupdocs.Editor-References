---
title: "Length.Unit"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "サポートされているすべての長さ単位"
type: docs
weight: 240
url: /ja/net/groupdocs.editor.htmlcss.css.datatypes/length.unit/
---
## Length.Unit enumeration

サポートされているすべての長さ単位

```csharp
public enum Unit
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Unitless | `0` | 単位なし - 定義された長さ単位がありません。デフォルト値です。 |
| Px | `1` | ピクセル。表示デバイスに対して相対的です。画面表示の場合、通常はディスプレイのデバイスピクセル（ドット）1つです。 |
| Em | `2` | Em。 この単位は要素の計算されたフォントサイズを表します。 |
| Ex | `3` | Ex（x-長さ）。この単位は要素のフォントの x 高さを表します。'x' 文字を含むフォントでは、通常はフォントの小文字の高さです。多くのフォントで 1ex ≈ 0.5em です。 |
| Cm | `4` | Cm。1センチメートル（10ミリメートル）です。 |
| Mm | `5` | Mm。1ミリメートルです。 |
| In | `6` | In。1インチ（2.54センチメートル）です。 |
| Pt | `7` | Pt。1ポイントはインチの 1/72、または 0.353 mm です。 |
| Pc | `8` | Pc。1パイカ（12ポイント）です。 |
| Ch | `9` | Ch。この単位は要素のフォントにおける文字 '0'（ゼロ、Unicode文字 U+0030）の幅、正確には前進幅を表します。 |
| Rem | `10` | Rem。この単位はルート要素（例: &lt;html&gt; 要素）のフォントサイズを表します。このルート要素のフォントサイズに使用される場合、その初期値を表します。 |
| Vw | `11` | Vw - ビューポート幅。ビューポート幅の 1/100です。 |
| Vh | `12` | Vh - ビューポート高さ。ビューポート高さの 1/100です。 |
| Vmin | `13` | Vmin。ビューポートの高さと幅の最小値の 1/100です。 |
| Vmax | `14` | Vmax。ビューポートの高さと幅の最大値の 1/100です。 |
| Percent | `15` | この値は固定（外部）値に対して相対的で、コンテキストに依存します。1% = 外部値の 1/100です。 |

### 備考

https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units

### 参照

* struct [Length](../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
