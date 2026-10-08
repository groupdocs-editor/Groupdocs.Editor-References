---
title: "FontSize"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "フォントサイズを特別な単位または長さの値として表し、歴史的に大文字 M の幅としてフォントのサイズを指定します。"
type: docs
weight: 260
url: /ja/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

フォントサイズを特別な単位または長さの値として表し、フォントのサイズ（歴史的には大文字 \"M\" の幅）を指定します。

```csharp
public struct FontSize : IEquatable<FontSize>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | この font-size がユーザーのデフォルトフォントサイズ（medium）に基づくキーワードとして絶対サイズで定義されているかどうかを示します |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | この font-size に初期値（Medium）があるかどうかを示します |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | この font-size が [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) 値で定義されているかどうかを示します |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | この font-size がキーワードとして相対サイズで定義されているかどうかを示します。フォントは親要素のフォントサイズに対して大きくまたは小さくなり、絶対サイズキーワードを分ける際に使用される比率に大まかに従います。 |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | この font-size がそれで定義されている場合は長さの値を、そうでない場合は例外をスローします |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | このフォントサイズの値を文字列として返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | 指定された長さからフォントサイズを作成します |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | このフォントサイズインスタンスが指定されたものと等しいかどうかを判定します |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | このフォントサイズインスタンスがキャストされていない指定されたものと等しいかどうかを判定します |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | このインスタンスのハッシュコードを返します |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | 指定されたキーワードを 'font-size' の適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返そうとします。 |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | 二つの "FontSize" 値が等しいかどうかをチェックします |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | 二つの "FontSize" 値が等しくないかどうかをチェックします |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | 通常の大きな絶対サイズ |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | より大きな相対サイズ - フォントは親要素の font-size に対して相対的に大きくなります。上記の絶対サイズキーワードを分ける際に使用された比率でおおよそ決まります。 |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | 中サイズ。初期値。 |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | 通常の小さな絶対サイズ |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | より小さな相対サイズ - フォントは親要素の font-size に対して相対的に小さくなります。上記の絶対サイズキーワードを分ける際に使用された比率でおおよそ決まります。 |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | 平均的な大きな絶対サイズ |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | 平均的な小さな絶対サイズ |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | 非常に大きな絶対サイズ |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | 非常に小さな絶対サイズ |

### 参照

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
