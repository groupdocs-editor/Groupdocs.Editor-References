---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara MHTML MIME‑inkapslingen av sammansatta HTML-dokument"
type: docs
weight: 1020
url: /sv/net/groupdocs.editor.options/mhtmlsaveoptions/
---
## MhtmlSaveOptions class

Tillåter att ange anpassade alternativ för att generera och spara MHTML (MIME encapsulation of aggregate HTML documents)-dokument

```csharp
public sealed class MhtmlSaveOptions : ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MhtmlSaveOptions](mhtmlsaveoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ExportCidUrls](../../groupdocs.editor.options/mhtmlsaveoptions/exportcidurls) { get; set; } | Anger om CID (Content-ID)-URL:er ska användas för att referera resurser (bilder, typsnitt, CSS) som ingår i MHTML-dokument. Standardvärdet är `false`. |
| [ExportDocumentProperties](../../groupdocs.editor.options/mhtmlsaveoptions/exportdocumentproperties) { get; set; } | Anger om inbyggda och anpassade dokumentegenskaper ska exporteras till MHTML. Standardvärdet är `false`. |
| [ExportLanguageInformation](../../groupdocs.editor.options/mhtmlsaveoptions/exportlanguageinformation) { get; set; } | Anger om språkinformation ska exporteras till MHTML. Standardvärdet är `false`. |

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
