---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för att spara EditableDocument../groupdocs.editor/editabledocument‑instansen till HTML-formatet"
type: docs
weight: 900
url: /sv/net/groupdocs.editor.options/htmlsaveoptions/
---
## HtmlSaveOptions class

Tillåter att ange anpassade alternativ för att spara [`EditableDocument`](../../groupdocs.editor/editabledocument)-instansen till HTML-formatet

```csharp
public sealed class HtmlSaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AttributeValueDelimiter](../../groupdocs.editor.options/htmlsaveoptions/attributevaluedelimiter) { get; set; } | Styr vilken avgränsare som används runt attributvärden i HTML-element: enkelfnutt (standardvärde) eller dubbelfnutt |
| [EmbedStylesheetsIntoMarkup](../../groupdocs.editor.options/htmlsaveoptions/embedstylesheetsintomarkup) { get; set; } | Styr var CSS-stilmallen/-mallarna ska lagras: som externa resurser (`false`), eller inbäddas i HTML-markupen, inuti STYLE-elementet i HTML-&gt;HEAD‑sektionen (`true`) |
| [HtmlTagCase](../../groupdocs.editor.options/htmlsaveoptions/htmltagcase) { get; set; } | Styr hur HTML‑taggnamnen visas i HTML-markupen: Endast gemener (standardvärde), Endast versaler eller Första bokstaven versal |
| [SavingCallback](../../groupdocs.editor.options/htmlsaveoptions/savingcallback) { get; set; } | Gränssnitt som måste implementeras av slutanvändaren för att spara alla externa HTML-resurser. Denna egenskap **måste** får inte vara `null`, annars kommer GroupDocs.Editor att kasta ett undantag när [`EditableDocument`](../../groupdocs.editor/editabledocument) sparas till HTML-format. |

### Se även

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
