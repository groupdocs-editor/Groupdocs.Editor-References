---
title: "SavingCallback"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Gränssnitt som måste implementeras av slutanvändaren för att spara alla externa HTML‑resurser. Denna egenskap får inte vara null, annars kommer GroupDocs.Editor att kasta ett undantag när EditableDocumentgroupdocs.editor/editabledocument sparas i HTML‑format."
type: docs
weight: 50
url: /sv/net/groupdocs.editor.options/htmlsaveoptions/savingcallback/
---
## HtmlSaveOptions.SavingCallback property

Gränssnitt, som måste implementeras av slutanvändaren för att spara alla externa HTML‑resurser. Denna egenskap **måste** inte vara `null`, annars kommer GroupDocs.Editor att kasta ett undantag när [`EditableDocument`](../../../groupdocs.editor/editabledocument) sparas i HTML‑format.

```csharp
public IHtmlSavingCallback SavingCallback { get; set; }
```

### Anmärkningar

Om värdet på egenskapen [`EmbedStylesheetsIntoMarkup`](../embedstylesheetsintomarkup) är satt till `true` kommer alla stilmallar att inbäddas i HTML‑markup och därför inte skickas till detta sparnings‑callback.

### Se även

* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
