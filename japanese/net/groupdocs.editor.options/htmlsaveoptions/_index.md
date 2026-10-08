---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "EditableDocument../groupdocs.editor/editabledocument インスタンスを HTML 形式で保存するためのカスタムオプションを指定できます"
type: docs
weight: 900
url: /ja/net/groupdocs.editor.options/htmlsaveoptions/
---
## HtmlSaveOptions class

HTML 形式で保存するために、[`EditableDocument`](../../groupdocs.editor/editabledocument) インスタンスのカスタムオプションを指定できます

```csharp
public sealed class HtmlSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AttributeValueDelimiter](../../groupdocs.editor.options/htmlsaveoptions/attributevaluedelimiter) { get; set; } | HTML 要素の属性値を囲むデリミタとして、シングルクオート（デフォルト）またはダブルクオートのどちらを使用するかを制御します |
| [EmbedStylesheetsIntoMarkup](../../groupdocs.editor.options/htmlsaveoptions/embedstylesheetsintomarkup) { get; set; } | CSS スタイルシートの保存場所を制御します：外部リソースとして（`false`）保存するか、HTML マークアップ内の STYLE 要素（HTML-&gt;HEAD セクション）に埋め込むか（`true`） |
| [HtmlTagCase](../../groupdocs.editor.options/htmlsaveoptions/htmltagcase) { get; set; } | HTML マークアップ内でのタグ名の表記方法を制御します：すべて小文字（デフォルト）、すべて大文字、または先頭文字だけ大文字 |
| [SavingCallback](../../groupdocs.editor.options/htmlsaveoptions/savingcallback) { get; set; } | エンドユーザーが外部 HTML リソースすべてを保存するために実装しなければならないインターフェイスです。このプロパティは **must** `null` であってはならず、`null` の場合、GroupDocs.Editor は [`EditableDocument`](../../groupdocs.editor/editabledocument) を HTML 形式で保存中に例外をスローします。 |

### 参照

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
