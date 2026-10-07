---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Omvat alle fixed-layout, ook wel bekend als fixed-page-formaten, die PDF en XPS omvatten; dit omvat geen rasterafbeeldingen."
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Omvat alle vaste lay-out (ook bekend als "fixed-page") formaten, die PDF en XPS omvatten (dit omvat geen rasterafbeeldingen)

<br />

*** ** * ** ***

Verschillende documentweergave- of publicatietoepassingen stellen gebruikers in staat om (Adobe Acrobat, XPS Viewer) te openen en soms (Adobe InDesign) te bewerken documenten met specifieke formaten. Deze toepassingen produceren doorgaans zogenoemde “fixed-page” formaatdocumenten. Zo’n documentformaat beschrijft nauwkeurig waar de inhoud van een document op elke pagina wordt geplaatst. Intern bevat het PDF- of XPS-formaat een beschrijving van elke pagina, evenals tekeninstructies die de lay-out van de inhoud op de pagina specificeren. Dit is vergelijkbaar met beeldformaten, die beschrijven waar de inhoud wordt weergegeven, zowel in raster- als vectorvorm.

<br />


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) is een type document dat in de jaren 90 door Adobe is gemaakt. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAll()](#getAll--) | Haalt een enumerateerbare collectie op van alle [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Haalt een instantie op van het opgegeven type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) dat de opgegeven bestandsextensie heeft. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)-object. |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format (PDF) is een type document dat in de jaren 90 door Adobe is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Haalt een enumerateerbare collectie op van alle [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
Waarde: Een IEnumerable{FixedLayoutFormats} die alle instanties van [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) bevat.


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Haalt een instantie op van het opgegeven type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) dat de opgegeven bestandsextensie heeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie van het documentformaat. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)-object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie om te converteren. Als de extensie meerdere punten bevat, wordt het deel na het laatste punt gebruikt. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

