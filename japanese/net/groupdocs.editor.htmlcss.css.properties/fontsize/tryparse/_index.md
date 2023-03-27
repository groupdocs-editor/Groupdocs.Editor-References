---
title: TryParse
second_title: GroupDocs.Editor for .NET API リファレンス
description: 指定されたキーワードをfontsizeの適切なキーワード値として認識し成功した場合はそれを返し失敗した場合は NULL を返します
type: docs
weight: 190
url: /ja/net/groupdocs.editor.htmlcss.css.properties/fontsize/tryparse/
---
## FontSize.TryParse method

指定されたキーワードを「font-size」の適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返します。

```csharp
public static bool TryParse(string keyword, out FontSize result)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| keyword | String | 解析するキーワード |
| result | FontSize& | 解析の結果、成功した、または[`Medium`](../medium)さもないと |

### 戻り値

解析が成功した場合は true、そうでない場合は false

### 関連項目

* struct [FontSize](../../fontsize)
* 名前空間 [GroupDocs.Editor.HtmlCss.Css.Properties](../../fontsize)
* 組み立て [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->