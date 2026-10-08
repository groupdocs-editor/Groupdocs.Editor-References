---
title: "ToStringSpecified"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された単位タイプでこの長さを文字列として返します。数値は単位タイプの変更に応じて変換されます。"
type: docs
weight: 260
url: /ja/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

指定された単位タイプでこの長さを文字列として返します。数値は単位タイプの変更に応じて変換されます。

```csharp
public string ToStringSpecified(Unit unit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 単位 | 単位 | シリアライズして文字列に変換する前にこのインスタンスが変換されるべき指定された単位。有効である必要があり、単位なしにすることはできません。 |

### 戻り値

文字列表現

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidEnumArgumentException | 値が定義されていません |
| ArgumentOutOfRangeException | 単位なしの値は許可されていません |

### 参照

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
