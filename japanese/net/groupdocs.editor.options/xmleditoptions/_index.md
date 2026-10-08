---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "XML (eXtensible Markup Language) ドキュメントの編集および HTML への変換のためのカスタムオプションを指定できるようにします"
type: docs
weight: 1270
url: /ja/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

XML（eXtensible Markup Language）ドキュメントの編集および HTML への変換のためのカスタムオプションを指定できます。

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | 属性値の引用符タイプ (シングルまたはダブルクオート) を指定できるようにします。デフォルトはダブルクオートです。 |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | テキストドキュメントの文字エンコーディングで、開く際に適用されます。デフォルトは null で、内部ドキュメントエンコーディングが適用されます。 |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | 破損した XML 構造を修正するメカニズムを有効または無効にできるようにします。デフォルトは無効 (false) です。 |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | XML が HTML で表現される際に適用される XML フォーマッティングを調整できるようにします。デフォルトのフォーマッティングが使用され、調整可能です。null に設定できません。 |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | XML が HTML で表現される際に適用される XML ハイライトを調整できるようにします。デフォルトのハイライトが使用され、調整可能です。null に設定できません。 |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | 属性値内のメールアドレスを認識するアルゴリズムを有効にできるようにします |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | URI 認識アルゴリズムを有効にできるようにします |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | 内部タグテキストの末尾空白の切り捨てを有効にできるようにします。デフォルトは無効 (false) で、末尾空白は保持されます。 |

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
