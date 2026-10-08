---
title: "FontWeight"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Fontweight プロパティはフォントの太さ（ウェイト）を設定します。利用可能なウェイトは現在設定されているフォントファミリーに依存します。"
type: docs
weight: 280
url: /ja/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

font-weight プロパティはフォントの太さ（または太字）を設定します。利用可能な太さは現在設定されているフォントファミリーに依存します。

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | この font-weight インスタンスがフォントのウェイト（太さ）の絶対値を整数として保持しているかどうかを示します |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | この font-size に初期値（Medium）があるかどうかを示します |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | この font-weight インスタンスがフォントのウェイト（太さ）の相対値を保持しているかどうかを示します（親要素の太さと比較）。 |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | 1 から 1000 の範囲（包括）の整数値を返します。この数値はフォントの太さを表しますが、現在の太さが絶対値ではなく相対値の場合は例外をスローします。 |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | この font-weight の値を文字列として返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | 指定された数値から font-weight を作成します |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | 指定された FontWeight インスタンスが等しいかどうかを判定します |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | この FontWeight インスタンスがキャストされていない指定されたものと等しいかどうかを判定します |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | このインスタンスのハッシュコードを返します |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | 指定された文字列を解析し、成功した場合は有効な FontWeight インスタンスを返そうとします |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | 2つの \"FontWeight\" 値が等しいかどうかをチェックします |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | 2つの \"FontWeight\" 値が等しくないかどうかをチェックします |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | 太字のフォントウェイト。700 と同じです。 |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | 親要素より1段階重い相対フォントウェイト |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | 親要素より1段階軽い相対フォントウェイト |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | 標準のフォントウェイト。400 と同じです。 |

### 参照

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
