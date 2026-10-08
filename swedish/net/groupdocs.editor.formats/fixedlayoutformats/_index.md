---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar fixedlayout fixedpage-dokumentformat såsom PDF, exklusive rasterbildformat."
type: docs
weight: 100
url: /sv/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats class

Representerar fast layout (fast sida) dokumentformat, såsom PDF, exklusive rasterbildformat.

```csharp
public class FixedLayoutFormats : DocumentFormatBase
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Hämtar filändelsen för dokumentformatet. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Hämtar formatfamiljen som dokumentformatet tillhör. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Hämtar det unika identifieraren för formatfamiljen. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Hämtar MIME-typen för dokumentformatet. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Hämtar namnet på formatfamiljen. |
| static [All](../../groupdocs.editor.formats/fixedlayoutformats/all) { get; } | Hämtar alla tillgängliga instanser av [`FixedLayoutFormats`](../fixedlayoutformats). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Hämtar en [`FixedLayoutFormats`](../fixedlayoutformats)‑instans som matchar den angivna filändelsen. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-instansen. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestämmer om denna instans är lika med den angivna [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-instansen. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestämmer om denna instans är lika med den angivna [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-instansen. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returnerar en hashkod för det aktuella objektet. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit) | Konverterar uttryckligen en filändelsestring till en [`FixedLayoutFormats`](../fixedlayoutformats)‑instans. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF), introducerat av Adobe, erbjuder en standardiserad representation av dokument oberoende av programvara, hårdvara och operativsystem. För ytterligare detaljer, se: [PDF file format](https://docs.fileformat.com/pdf/). |

### Anmärkningar

Fast‑layoutformat specificerar exakt placeringen och återgivningen av innehåll på varje sida. Vanligt förekommande i dokumentvisnings‑, publicerings- eller redigeringsprogram som Adobe Acrobat och Adobe InDesign. Dessa format definierar internt sidlayout och innehållspositionering med vektorgrafik och textinstruktioner.

### Se även

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
