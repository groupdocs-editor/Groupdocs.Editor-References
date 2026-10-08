---
title: "ExportCidUrls"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Anger om CID ContentID‑URL:er ska användas för att referera resurser som bilder, typsnitt och CSS som inkluderas i MHTML‑dokument. Standardvärdet är falskt."
type: docs
weight: 20
url: /sv/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

Anger om CID (Content-ID)-URL:er ska användas för att referera resurser (bilder, typsnitt, CSS) som ingår i MHTML-dokument. Standardvärdet är `false`.

```csharp
public bool ExportCidUrls { get; set; }
```

### Anmärkningar

Som standard refereras resurser i MHTML-dokument med filnamn (till exempel "image.png"), som matchas mot "Content-Location"-rubriker i MIME-delar. Detta alternativ möjliggör en alternativ metod, där referenser till resursfiler skrivs som CID (Content-ID)-URL:er (till exempel "cid:image.png") och matchas mot "Content-ID"-rubriker.

I teorin bör det inte finnas någon skillnad mellan de två referensmetoderna och någon av dem bör fungera bra i vilken webbläsare eller e-postklient som helst. I praktiken misslyckas dock vissa klienter med att hämta resurser efter filnamn. Om din webbläsare eller e-postklient vägrar att ladda resurser som ingår i ett MTHML-dokument (visar inte bilder eller laddar inte CSS-stilar), försök exportera dokumentet med CID-URL:er.

### Se även

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
