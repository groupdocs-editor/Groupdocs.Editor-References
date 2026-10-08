---
title: "GetFirstDefined"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定されたセットからUndefinedでない最初のフォントタイプを返します。すべての項目がUndefinedの場合はUndefinedフォントタイプを返します"
type: docs
weight: 80
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined/
---
## FontType.GetFirstDefined method

指定されたセットから最初の"Undefined"以外のフォントタイプを返します。すべてが"Undefined"の場合は"Undefined"フォントタイプを返します

```csharp
public static FontType GetFirstDefined(params FontType[] fonts)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| フォント | FontType[] | 1つ以上の FontType 値、NULL または空のコレクションは許可されません |

### 戻り値

指定されたコレクションから Undefined でない最初の FontType 値、すべての項目が Undefined の場合は Undefined

### 参照

* struct [FontType](../../fonttype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
