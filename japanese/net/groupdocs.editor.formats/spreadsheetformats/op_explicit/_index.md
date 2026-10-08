---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "文字列（ファイル拡張子を表す）を SpreadsheetFormatsgroupdocs.editor.formats/spreadsheetformats オブジェクトに変換します。"
type: docs
weight: 180
url: /ja/net/groupdocs.editor.formats/spreadsheetformats/op_explicit/
---
## SpreadsheetFormats Explicit operator

文字列（ファイル拡張子を表す）を [`SpreadsheetFormats`](../../spreadsheetformats) オブジェクトに変換します。

```csharp
public static explicit operator SpreadsheetFormats(string extension)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 拡張子 | 文字列 | 変換対象のファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |

### 戻り値

指定されたファイル拡張子に対応する [`SpreadsheetFormats`](../../spreadsheetformats) オブジェクトです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [SpreadsheetFormats](../../spreadsheetformats) | 指定されたファイル拡張子が null の場合にスローされます。 |

### 参照

* class [SpreadsheetFormats](../../spreadsheetformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
