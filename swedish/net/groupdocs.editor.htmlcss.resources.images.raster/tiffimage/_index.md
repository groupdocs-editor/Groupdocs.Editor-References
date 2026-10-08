---
title: "TiffImage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en bild i TIFF Tagged Image File Format-format med dess metadata och ytterligare metoder"
type: docs
weight: 550
url: /sv/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
## TiffImage class

Representerar en bild i TIFF (Tagged Image File Format)-format med dess metadata och ytterligare metoder.

```csharp
public sealed class TiffImage : RasterImageResourceBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TiffImage](tiffimage#constructor)(string, Stream) | Skapar en ny GifImage-instans från innehåll, representerat som byte‑ström, och med angivet namn |
| [TiffImage](tiffimage#constructor_1)(string, string) | Skapar en ny TiffImage-instans från innehåll, representerat som base64‑kodad sträng, och med angivet namn |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Returnerar bildens bildförhållande som förhållandet bredd till höjd |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Returnerar innehållet i denna rasterbild som en byte-ström |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Returnerar korrekt filnamn för denna rasterbild, som består av namn och filändelse. Teoretiskt kan det skilja sig från namnet. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Avgör om denna rasterbild är borttagen eller inte |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Returnerar längden på denna rasterbildsfil i byte |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Returnerar linjära dimensioner för denna rasterbild (bredd och höjd) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Returnerar namn på denna rasterbild. Innehåller vanligtvis inte filändelse och kan teoretiskt skilja sig från filnamnet. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Returnerar innehållet i denna rasterbild som en base64-kodad sträng |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/type) { get; } | Returnerar [`Tiff`](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Avslutar denna rasterbild genom att frigöra dess innehåll och göra de flesta av dess metoder och egenskaper oanvändbara |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Kontrollerar denna instans med den angivna för referenslikhet. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Sparar denna rasterbild till den angivna filen |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid)(Stream) | Kontrollerar om den angivna strömmen är en giltig TIFF-bild |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid_1)(string) | Kontrollerar om den angivna base64‑kodade strängen är en giltig TIFF-bild |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Händelse som inträffar när denna rasterbild avyttras |

### Anmärkningar

Se https://en.wikipedia.org/wiki/TIFF för detaljer. I mycket sällsynta fall förekommer TIFF i WordProcessing-dokument.

### Se även

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
