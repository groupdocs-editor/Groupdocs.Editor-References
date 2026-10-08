---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "文字列で表されたファイル拡張子を EmailFormatsgroupdocs.editor.formats/emailformats オブジェクトに変換します。"
type: docs
weight: 150
url: /ja/net/groupdocs.editor.formats/emailformats/op_explicit/
---
## EmailFormats Explicit operator

文字列で表されたファイル拡張子を [`EmailFormats`](../../emailformats) オブジェクトに変換します。

```csharp
public static explicit operator EmailFormats(string extension)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 拡張子 | 文字列 | 変換対象のファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |

### 戻り値

指定されたファイル拡張子に対応する [`EmailFormats`](../../emailformats) オブジェクトです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [EmailFormats](../../emailformats) | 指定されたファイル拡張子が null の場合にスローされます。 |

### 参照

* class [EmailFormats](../../emailformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
