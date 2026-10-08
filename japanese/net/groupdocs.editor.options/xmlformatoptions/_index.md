---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "XML ドキュメントが HTML として表現される際の書式設定を調整できるオプションを含みます。"
type: docs
weight: 1280
url: /ja/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

XML ドキュメントが HTML として表現される際の書式設定を調整できるオプションを含みます。

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | 有効にすると、すべての XML 要素内の属性‑値ペアがそれぞれ新しい行に配置されます。デフォルトは false（無効）で、属性‑値ペアはすべて単一行に配置されます。 |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | この XML 書式設定オプションのインスタンスがデフォルト値を持つかどうかを示します。 |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | 有効にすると、子を持たない XML 要素内のリーフテキストノード（テキストコンテンツ）は、左インデントを大きくして新しい行にレンダリングされます。デフォルトは false（無効）で、リーフテキストノードは親と同じ行に配置され、インデントは追加されません。 |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | 新しい行ごとの左インデントのオフセットを指定できます。単位なしの非ゼロ値は使用できません。デフォルトは 10pt です。 |

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
