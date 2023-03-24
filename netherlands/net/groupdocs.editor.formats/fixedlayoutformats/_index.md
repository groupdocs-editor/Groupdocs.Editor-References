---
title: FixedLayoutFormats
second_title: GroupDocs.Editor voor .NET API-referentie
description: Bevat alle indelingen met een vaste layout ook bekend als vaste paginas inclusief PDF en XPS dit omvat geen rasterafbeeldingen
type: docs
weight: 80
url: /nl/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

Bevat alle indelingen met een vaste lay-out (ook bekend als "vaste pagina's"), inclusief PDF en XPS (dit omvat geen rasterafbeeldingen)

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | Retourneert een extensie (zonder beginpunt) van deze indeling met vaste lay-out in kleine letters |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | Retourneert een MIME-code voor deze indeling |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | Retourneert een formele volledige naam van deze vaste layout format |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Retourneert instantie van[`FixedLayoutFormats`](../fixedlayoutformats) structuur, gekoppeld aan de opgegeven bestandsnaamextensie, of genereert een uitzondering als de extensie niet correct kan worden geparseerd |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | Bepaalt of deze instantie gelijk is aan de andere gespecificeerde FixedLayoutFormats instantie |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de andere opgegeven IDocumentFormat-instantie |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | Bepaalt of deze instantie gelijk is aan het andere opgegeven object, dat vermoedelijk een boxed FixedLayoutFormats is |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | Retourneert een hash-code, die onveranderlijk is voor deze instantie |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | Retourneert de naam van dit specifieke formaat, hetzelfde als 'Name' property |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | Controleert twee gegeven FixedLayoutFormats-instanties op gelijkheid |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | Retourneert een bytewaarde uit het onderliggende veld van de opgegeven FixedLayoutFormats-instantie (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | Controleert twee gegeven FixedLayoutFormats-instanties op inequality |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF) is een type document dat in de jaren negentig door Adobe is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van applicatiesoftware, hardware en het besturingssysteem. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | XPS-bestand vertegenwoordigt paginalay-outbestanden die zijn gebaseerd op XML-papierspecificaties gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF-bestandsformaat en is vergelijkbaar met het PDF-bestandsformaat, maar gebruikt XML in lay-out, uiterlijk en afdrukinformatie van een document. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | Retourneert een interne klasse, die ontelbare mogelijkheden biedt voor alle bestaande formaten met een vaste lay-out |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | Implementeert IEnumerable generieke interface, die een 'foreach'-mogelijkheid mogelijk maakt voor de FixedLayoutFormats type |

### Opmerkingen

Met verschillende toepassingen voor het bekijken of publiceren van documenten kunnen gebruikers documenten van specifieke indelingen openen (Adobe Acrobat, XPS Viewer) en soms bewerken (Adobe InDesign). Deze toepassingen produceren doorgaans documenten in het zogenaamde "vaste pagina"-formaat. Zo'n documentformaat beschrijft precies waar de inhoud van een document op elke pagina wordt geplaatst. Intern bevat het PDF- of XPS-formaat een beschrijving van elke pagina, evenals tekeninstructies, die de lay-out van de inhoud op de pagina specificeren. Dit is vergelijkbaar met afbeeldingsindelingen en beschrijft waar de inhoud wordt weergegeven in raster- of vectorvorm.

### Zie ook

* interface [IDocumentFormat](../idocumentformat)
* naamruimte [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
