---
title: "SavingCallback"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "エンドユーザーがすべての外部 HTML リソースを保存するために実装しなければならないインターフェイスです。このプロパティが null であってはならず、そうでない場合 GroupDocs.Editor は EditableDocumentgroupdocs.editor/editabledocument を HTML 形式で保存中に例外をスローします。"
type: docs
weight: 50
url: /ja/net/groupdocs.editor.options/htmlsaveoptions/savingcallback/
---
## HtmlSaveOptions.SavingCallback property

エンドユーザーがすべての外部 HTML リソースを保存するために実装しなければならないインターフェイスです。このプロパティは **must** not be `null` であり、そうでない場合 GroupDocs.Editor は [`EditableDocument`](../../../groupdocs.editor/editabledocument) を HTML 形式で保存中に例外をスローします。

```csharp
public IHtmlSavingCallback SavingCallback { get; set; }
```

### 備考

[`EmbedStylesheetsIntoMarkup`](../embedstylesheetsintomarkup) プロパティの値が `true` に設定されている場合、すべてのスタイルシートが HTML マークアップに埋め込まれ、したがってこの保存コールバックに渡されません。

### 参照

* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
