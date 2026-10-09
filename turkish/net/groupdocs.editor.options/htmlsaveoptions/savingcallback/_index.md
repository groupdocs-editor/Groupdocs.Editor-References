---
title: "SavingCallback"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Kullanıcı tarafından tüm dış HTML kaynaklarını kaydetmek için uygulanması gereken arayüz. Bu özellik null olmamalıdır, aksi takdirde GroupDocs.Editor, EditableDocumentgroupdocs.editor/editabledocument'ı HTML formatına kaydederken bir istisna fırlatır."
type: docs
weight: 50
url: /tr/net/groupdocs.editor.options/htmlsaveoptions/savingcallback/
---
## HtmlSaveOptions.SavingCallback property

Arayüz, tüm dış HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanmalıdır. Bu özellik **must** `null` olmamalıdır, aksi takdirde GroupDocs.Editor, [`EditableDocument`](../../../groupdocs.editor/editabledocument) öğesini HTML formatına kaydederken bir istisna fırlatır.

```csharp
public IHtmlSavingCallback SavingCallback { get; set; }
```

### Açıklamalar

Eğer [`EmbedStylesheetsIntoMarkup`](../embedstylesheetsintomarkup) özelliğinin değeri `true` olarak ayarlanırsa, tüm stil sayfaları HTML işaretlemesine gömülür ve bu nedenle bu kaydetme geri çağırmasına gönderilmez.

### Ayrıca Bakınız

* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
