---
title: "寸法"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "任意の単位で、1つのラスタ矩形画像の幅と高さという線形寸法を表します。変更不可能な構造体です。"
type: docs
weight: 450
url: /ja/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

任意の単位でのラスタ矩形画像の線形寸法（幅と高さ）を表します。不変構造体。

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | 指定された幅と高さから新しいインスタンスを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | 空の Dimensions インスタンスを返します。 |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | 面積（幅 × 高さ）を返します。 |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | この寸法のアスペクト比（幅/高さ）です。 |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | 画像の高さを返します。 |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | この "Dimensions" インスタンスが空でデフォルトかどうか、すなわち正しい幅と高さが格納されていないかを判定します。 |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | 指定された 'Dimensions' が正方形かどうか、すなわち幅が高さと等しいかを判定します。 |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | 画像の幅を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | このインスタンスの完全なコピーを返します。 |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | このインスタンスが指定された "Dimensions" インスタンスと等しいかどうかを判定します。 |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します。おそらく別の "Dimensions" インスタンスです。 |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | このインスタンスのハッシュコードを返します。ライフタイム中に変更できません。 |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | 指定された高さに基づき、現在のインスタンスから比例的にサイズ変更された新しい "Dimensions" インスタンスを作成し、返します。 |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | 指定された幅に基づき、現在のインスタンスから比例的にサイズ変更された新しい "Dimensions" インスタンスを作成し、返します。 |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | この "Dimensions" の文字列表現を返します。 |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | 2つの「Dimensions」値が等しいかどうかを確認します。つまり、幅と高さが等しいか、または両方が空です。 |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | 2つの「Dimensions」値が等しくないかどうかを確認します。つまり、対応する幅または高さが異なる場合です。 |

### 参照

* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
