---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara Markdown-dokument"
type: docs
weight: 1000
url: /sv/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Tillåter att ange anpassade alternativ för att generera och spara Markdown-dokument

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | Anger om bilder sparas i Base64‑format till utdatafilen. Standard är `false`. |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | Anger den fysiska mappen där bilder sparas vid export av ett dokument till Markdown‑formatet. Standard är null. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesbruk. Att sätta detta alternativ till `true` kan avsevärt minska minnesförbrukningen vid generering av stora dokument, men med kostnaden av långsammare sparningstid. Standard är `false` (minnesoptimering är inaktiverad för bättre prestanda). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Allow anger hur innehåll i tabeller ska justeras vid export till Markdown‑formatet. Standardvärdet är Auto. |

### Anmärkningar

Klassen MarkdownSaveOptions måste användas av användaren när det finns en instans av klassen EditableDocument som innehåller redigerat dokumentinnehåll, och det krävs att detta innehåll sparas till ett nytt dokument i Markdown‑format.

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
