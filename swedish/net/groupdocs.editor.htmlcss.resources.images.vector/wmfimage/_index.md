---
title: "WmfImage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en vektorbild i WMF Windows MetaFile-format med dess metadata och ytterligare metoder"
type: docs
weight: 600
url: /sv/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
## WmfImage class

Representerar en vektorbild i WMF (Windows MetaFile)-format med dess metadata och ytterligare metoder

```csharp
public sealed class WmfImage : MetaImageBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WmfImage](wmfimage#constructor)(string, Stream) | Skapar en ny WmfImage-instans från innehåll, representerat som byte‑ström, och med angivet namn |
| [WmfImage](wmfimage#constructor_1)(string, string) | Skapar en ny WmfImage-instans från innehåll, representerat som base64‑kodad sträng, och med angivet namn |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Returnerar bildförhållandet för denna vektorbild |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/bytecontent) { get; } | Returnerar innehållet i denna WMF-bild som en binärström |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Returnerar korrekt filnamn för denna vektorbild, som består av namn och filändelse. Teoretiskt kan det skilja sig från namnet. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Bestämmer om denna rasterbild är frigjord (`true`) eller inte (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Returnerar linjära dimensioner för denna vektorbild (bredd och höjd) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Returnerar namn på denna vektorbild. Innehåller vanligtvis inte filnamnstillägg och kan teoretiskt skilja sig från filnamnet. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/textcontent) { get; } | Returnerar innehållet i denna WMF-bild som vanlig text |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/type) { get; } | Returnerar ImageType.Wmf |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/dispose)() | Avyttrar denna WMF-bild genom att avyttra dess innehåll och göra de flesta av dess metoder och egenskaper inaktiva |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Kontrollerar denna instans med den angivna för referenslikhet. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/save)(string) | Sparar denna WMF-bild till filen |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetopng)(Stream) | Sparar denna vektor‑WMF-bild till en raster‑PNG‑bild |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetosvg)(Stream) | Sparar denna vektor‑WMF-bild till en vektor‑SVG‑bild |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid)(Stream) | Kontrollerar om den angivna strömmen är en giltig WMF-bild |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid_1)(string) | Kontrollerar om den angivna base64‑kodade strängen är en giltig WMF-bild |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Händelse som inträffar när denna rasterbild avyttras |

### Se även

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
