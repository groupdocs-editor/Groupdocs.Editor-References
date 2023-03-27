---
title: TiffImage
second_title: GroupDocs.Editor voor .NET API-referentie
description: Vertegenwoordigt één afbeelding in TIFFindeling Tagged Image File Format met zijn metadata en aanvullende methoden
type: docs
weight: 560
url: /nl/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
## TiffImage class

Vertegenwoordigt één afbeelding in TIFF-indeling (Tagged Image File Format) met zijn metadata en aanvullende methoden

```csharp
public sealed class TiffImage : RasterImageResourceBase
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [TiffImage](tiffimage#constructor)(string, Stream) | Maakt een nieuwe GifImage-instantie van inhoud, weergegeven als bytestroom, en met opgegeven naam |
| [TiffImage](tiffimage#constructor_1)(string, string) | Maakt een nieuwe TiffImage-instantie op basis van inhoud, weergegeven als een base64-gecodeerde tekenreeks en met de opgegeven naam |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Retourneert een beeldverhouding van deze afbeelding als de breedte-tot-hoogte-relatie |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Retourneert de inhoud van deze rasterafbeelding als bytestream |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Retourneert de juiste bestandsnaam van deze rasterafbeelding, die bestaat uit naam en extensie. Theoretisch kan afwijken van de naam. |
| [FramesCount](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/framescount) { get; } | Retourneert een aantal frames (afbeeldingen) binnen deze TIFF-afbeelding. Kan niet kleiner zijn dan 1. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Bepaalt of deze rasterafbeelding wordt weggegooid of niet |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Geeft de lengte van dit rasterafbeeldingsbestand terug in bytes |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Retourneert lineaire afmetingen van deze rasterafbeelding (breedte en hoogte) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Geeft de naam van deze rasterafbeelding terug. Bevat meestal geen bestandsnaamextensie en kan theoretisch verschillen van bestandsnaam. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Retourneert inhoud van deze rasterafbeelding als base64-gecodeerde string |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/type) { get; } | Retourneert ImageType.Tiff |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Verwijdert deze rasterafbeelding, verwijdert de inhoud en maakt de meeste methoden en eigenschappen niet-werkend |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Controleert deze instantie met gespecificeerde referentiegelijkheid. |
| [GenerateBitmap](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/generatebitmap)() | Genereert en retourneert een nieuwe instantie van de 'System.Drawing.Bitmap' van deze rasterafbeelding. |
| [ReduceToNewHeight](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/reducetonewheight)(ushort) | Creëert en retourneert een nieuwe verkleinde afbeeldingsresource van hetzelfde type, maar met gespecificeerde nieuwe verkleinde hoogte en proportioneel verkleinde breedte. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Slaat deze rasterafbeelding op in het opgegeven bestand |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid)(Stream) | Controleert of opgegeven stream een geldige TIFF-afbeelding is |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid_1)(string) | Controleert of opgegeven base64-gecodeerde tekenreeks een geldige TIFF-afbeelding is |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Gebeurtenis die optreedt wanneer deze rasterafbeelding wordt weggegooid |

### Opmerkingen

Zie https://en.wikipedia.org/wiki/TIFF voor details. In zeer zeldzame gevallen is TIFF aanwezig in WordProcessing-documenten.

### Zie ook

* class [RasterImageResourceBase](../rasterimageresourcebase)
* naamruimte [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
