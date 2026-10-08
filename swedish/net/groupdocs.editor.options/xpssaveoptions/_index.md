---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för generering och sparande av XPS XML Paper Specifications-dokument"
type: docs
weight: 1300
url: /sv/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

Tillåter att ange anpassade alternativ för generering och sparande av XPS (XML Paper Specifications)-dokument

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning. Att sätta detta alternativ till true kan avsevärt minska minnesförbrukningen vid generering av stora dokument på bekostnad av långsammare sparningstid. Standard är false (minnesoptimering är inaktiverad för bättre prestanda). |

### Anmärkningar

En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som ett ersättningsformat för EMF-filformatet och är likt PDF-filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
