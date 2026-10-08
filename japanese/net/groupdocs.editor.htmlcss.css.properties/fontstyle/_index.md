---
title: "FontStyle"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "フォントファミリーから通常、イタリック、またはオブリークのフェイスでフォントをどのようにスタイル付けするかを定義します。"
type: docs
weight: 270
url: /ja/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

フォントファミリーから、標準、イタリック、またはオブリークのフェイスでフォントをどのようにスタイル設定するかを定義します。

```csharp
public struct FontStyle
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | この font-style に初期値（Normal）があるかどうかを示します |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | このフォントスタイルの値を文字列として返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | この font-style インスタンスが指定されたものと等しいかどうかを判定します |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | この font-style インスタンスが指定されたキャストされていないものと等しいかどうかを判定します |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | このインスタンスのハッシュコードを返します |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | 指定されたキーワードを 'font-style' の適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返そうとします。 |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | \"FontStyle\" の 2 つの値が等しいかどうかをチェックします |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | \"FontStyle\" の 2 つの値が等しくないかどうかをチェックします |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | イタリックとして分類されたフォントを選択します。イタリック版が利用できない場合は、オブリークとして分類されたものが代わりに使用されます。どちらも利用できない場合、スタイルは人工的にシミュレートされます。 |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | フォントファミリー内で通常として分類されたフォントを選択します。初期値です。 |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | オブリークとして分類されたフォントを選択します。オブリーク版が利用できない場合は、イタリックとして分類されたものが代わりに使用されます。どちらも利用できない場合、スタイルは人工的にシミュレートされます。 |

### 参照

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
