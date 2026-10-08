---
title: "TryParse"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された文字列を数値と単位名を含む Length 値として解析しようとします"
type: docs
weight: 280
url: /ja/net/groupdocs.editor.htmlcss.css.datatypes/length/tryparse/
---
## Length.TryParse method

指定された文字列を解析し、数値と単位名を含む Length 値として取得しようとします。

```csharp
public static bool TryParse(string input, out Length result)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 入力 | 文字列 | 解析すべき入力文字列 |
| 結果 | Length& | 解析結果を含む出力パラメータです。解析が失敗した場合、デフォルトの Length 値（単位なしゼロ）が含まれます。 |

### 戻り値

解析が成功した場合は true、失敗した場合は false

### 参照

* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
