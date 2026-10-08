---
title: "TryParse"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定されたキーワードをフォントスタイルの適切なキーワード値として認識し、成功した場合は返し、失敗した場合は NULL を返します。"
type: docs
weight: 80
url: /ja/net/groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse/
---
## FontStyle.TryParse method

指定されたキーワードを 'font-style' の適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返そうとします。

```csharp
public static bool TryParse(string keyword, out FontStyle result)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キーワード | 文字列 | 解析するキーワード |
| result | FontStyle& | 解析が成功した場合の結果、またはそれ以外の場合は [`Normal`](../normal) |

### 戻り値

解析が成功した場合は true、そうでない場合は false

### 参照

* struct [FontStyle](../../fontstyle)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
