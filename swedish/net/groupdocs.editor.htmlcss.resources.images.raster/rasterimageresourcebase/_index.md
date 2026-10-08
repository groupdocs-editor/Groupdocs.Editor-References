---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Basisklass för alla stödda rasterbilder med fast namn, dimensioner, bildförhållande, typ, storlek och innehåll."
type: docs
weight: 540
url: /sv/net/groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
## RasterImageResourceBase class

Basklass för alla stödjade rasterbilder med fast namn, dimensioner, bildförhållande, typ, storlek och innehåll.

```csharp
public abstract class RasterImageResourceBase : IImageResource
```

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
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/type) { get; } | Den implementerande typen bör returnera information om rasterbildens typ |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Avslutar denna rasterbild genom att frigöra dess innehåll och göra de flesta av dess metoder och egenskaper oanvändbara |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals#equals)(IHtmlResource) | Kontrollerar denna instans med den angivna för referenslikhet. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Sparar denna rasterbild till den angivna filen |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Händelse som inträffar när denna rasterbild avyttras |

### Se även

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
