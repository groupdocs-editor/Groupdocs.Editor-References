---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "XML を HTML に変換する際のハイライトをカスタマイズできるオプションを含みます。"
type: docs
weight: 1290
url: /ja/net/groupdocs.editor.options/xmlhighlightoptions/
---
## XmlHighlightOptions class

XML から HTML への変換中の XML ハイライトをカスタマイズできるオプションを含みます。

```csharp
public sealed class XmlHighlightOptions : IEditOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AttributeNamesFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/attributenamesfontsettings) { get; } | 属性名のフォントを表す役割を持ちます。 |
| [AttributeValuesFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/attributevaluesfontsettings) { get; } | 属性値のフォントを表す役割を持ちます。 |
| [CDataFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/cdatafontsettings) { get; } | CDATA セクション（開始タグと終了タグのペアを含む）のフォントを表す役割を持ちます。 |
| [HtmlCommentsFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/htmlcommentsfontsettings) { get; } | HTML コメント（開始タグと終了タグのペアを含む）のフォントを表す役割を持ちます。 |
| [InnerTextFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/innertextfontsettings) { get; } | 内部タグテキストのフォントを表す役割を持ちます。 |
| [IsDefault](../../groupdocs.editor.options/xmlhighlightoptions/isdefault) { get; } | この XML ハイライトオプションオブジェクトがデフォルトのフォント設定を持っているかどうかを判断します。 |
| [XmlTagsFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/xmltagsfontsettings) { get; } | XML タグ（タグ名を含む角括弧）のフォントを表す役割を持ちます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ResetToDefault](../../groupdocs.editor.options/xmlhighlightoptions/resettodefault)() | 現在のフォント設定をデフォルト値にリセットします。 |

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
