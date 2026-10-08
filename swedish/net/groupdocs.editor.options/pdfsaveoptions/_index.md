---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara PDF‑dokument (Portable Document Format)."
type: docs
weight: 1070
url: /sv/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

Tillåter att ange anpassade alternativ för att generera och spara PDF (Portable Document Format)-dokument

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | Anger PDF‑standardens efterlevnadsnivå för utdata‑dokument. Standard är PdfCompliance.Pdf17. |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | Ansvarig för att bädda in teckensnitt som används i originaldokumentet i det resulterande PDF‑dokumentet. Som standard bäddas inga teckensnitt in (NotEmbed). |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning. Att sätta detta alternativ till true kan avsevärt minska minnesförbrukningen vid generering av stora dokument på bekostnad av långsammare sparningstid. Standard är false (minnesoptimering är inaktiverad för bättre prestanda). |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | Lösenord som kommer att tillämpas på det genererade PDF‑dokumentet som användarlösenord, krävs för att öppna det. Om NULL eller tomt kommer inget lösenord att tillämpas på dokumentet. Annars krypteras dokumentet med RC4 (nyckellängd 128 bit). Som standard är NULL – lösenordet tillämpas inte. |

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
