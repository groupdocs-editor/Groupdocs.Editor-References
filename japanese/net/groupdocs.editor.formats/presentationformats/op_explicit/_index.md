---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "ファイル拡張子を表す文字列を PresentationFormatsgroupdocs.editor.formats/presentationformats オブジェクトに変換します。"
type: docs
weight: 150
url: /ja/net/groupdocs.editor.formats/presentationformats/op_explicit/
---
## PresentationFormats Explicit operator

ファイル拡張子を表す文字列を [`PresentationFormats`](../../presentationformats) オブジェクトに変換します。

```csharp
public static explicit operator PresentationFormats(string extension)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 拡張子 | 文字列 | 変換対象のファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |

### 戻り値

指定されたファイル拡張子に対応する [`PresentationFormats`](../../presentationformats) オブジェクトです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PresentationFormats](../../presentationformats) | 指定されたファイル拡張子が null の場合にスローされます。 |

### 参照

* class [PresentationFormats](../../presentationformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
