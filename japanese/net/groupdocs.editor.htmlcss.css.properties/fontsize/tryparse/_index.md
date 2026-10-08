---
title: "TryParse"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定されたキーワードをフォントサイズの適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返します。"
type: docs
weight: 190
url: /ja/net/groupdocs.editor.htmlcss.css.properties/fontsize/tryparse/
---
## FontSize.TryParse method

指定されたキーワードを 'font-size' の適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返そうとします。

```csharp
public static bool TryParse(string keyword, out FontSize result)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キーワード | 文字列 | 解析するキーワード |
| result | FontSize& | 解析が成功した場合は結果、そうでなければ [`Medium`](../medium) です。 |

### 戻り値

解析が成功した場合は true、そうでない場合は false

### 参照

* struct [FontSize](../../fontsize)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
