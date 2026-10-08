---
title: "FromNumber"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された数値から fontweight を作成します"
type: docs
weight: 50
url: /ja/net/groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber/
---
## FontWeight.FromNumber method

指定された数値から font-weight を作成します

```csharp
public static FontWeight FromNumber(ushort number)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 数値 | UInt16 | 符号なし整数で、[1..1000] の範囲内である必要があります |

### 戻り値

新しい FontWeight インスタンスまたは例外

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 指定された数値が [1..1000] の範囲外です |

### 参照

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
