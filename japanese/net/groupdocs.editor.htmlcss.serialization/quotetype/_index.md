---
title: "QuoteType"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "シングルクオート と ダブルクオート の引用文字を表します。"
type: docs
weight: 660
url: /ja/net/groupdocs.editor.htmlcss.serialization/quotetype/
---
## QuoteType structure

引用文字を表します - シングルクオート (') とダブルクオート (\")

```csharp
public struct QuoteType : IEquatable<QuoteType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Character](../../groupdocs.editor.htmlcss.serialization/quotetype/character) { get; } | 引用する文字 |
| [Code](../../groupdocs.editor.htmlcss.serialization/quotetype/code) { get; } | 現在の文字のコードポイント (U+0027 または U+0022) |
| [HtmlEncoded](../../groupdocs.editor.htmlcss.serialization/quotetype/htmlencoded) { get; } | HTML エンコードされた文字 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals_1)(object) | この引用タイプのインスタンスが指定されたキャストされていないものと等しいかどうかを示します。 |
| [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals)(QuoteType) | この引用タイプのインスタンスが指定されたものと等しいかどうかを示します。 |
| override [GetHashCode](../../groupdocs.editor.htmlcss.serialization/quotetype/gethashcode)() | この文字のハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.htmlcss.serialization/quotetype/tostring)() | 現在の値に応じて "SingleQuote" または "DoubleQuote" 文字列を返します。 |
| [operator ==](../../groupdocs.editor.htmlcss.serialization/quotetype/op_equality) | 2 つの "QuoteType" 値が等しいかどうかをチェックします。 |
| [explicit operator](../../groupdocs.editor.htmlcss.serialization/quotetype/op_explicit#op_explicit) | 指定された [`QuoteType`](../quotetype) インスタンスを Char にキャストします (2 operators) |
| [operator !=](../../groupdocs.editor.htmlcss.serialization/quotetype/op_inequality) | 2 つの "QuoteType" 値が等しくないかどうかをチェックします。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [DoubleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/doublequote) | 二重引用符 (U+0022 QUOTATION MARK 文字) |
| static readonly [SingleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/singlequote) | 単一引用符 (U+0027 APOSTROPHE 文字) |

### 参照

* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
