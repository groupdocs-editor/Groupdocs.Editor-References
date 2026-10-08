---
title: "RecognizeLists"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "ドキュメントがプレーンテキスト形式からインポートされる際に、番号付きリスト項目がどのように認識されるかを指定できます。デフォルト値は true です。"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

ドキュメントがプレーンテキスト形式からインポートされる際に、番号付きリスト項目がどのように認識されるかを指定できます。デフォルト値は true です。

```csharp
public bool RecognizeLists { get; set; }
```

### 備考

このオプションが false に設定されている場合、リスト認識アルゴリズムはリスト番号がドット、右括弧、または箇条書き記号（例: \"•\", \"*\", \"-\", \"o\"）で終わる段落をリストとして検出します。true に設定すると、空白もリスト番号の区切りとして使用されます。アラビア数字スタイルの番号付け（1., 1.1.2.）のリスト認識アルゴリズムは、空白とドット（\".\"）の両方を使用します。

### 参照

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
