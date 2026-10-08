---
title: "EmfImage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en vektorbild i Enhanced metafile-format (EMF) med dess metadata och ytterligare metoder"
type: docs
weight: 560
url: /sv/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
## EmfImage class

Representerar en vektorbild i Enhanced Metafile Format (EMF) med dess metadata och ytterligare metoder

```csharp
public sealed class EmfImage : MetaImageBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EmfImage](emfimage#constructor)(string, Stream) | Skapar en ny EmfImage-instans från innehåll, representerat som byte‑ström, och med angivet namn |
| [EmfImage](emfimage#constructor_1)(string, string) | Skapar en ny EmfImage-instans från innehåll, representerat som base64‑kodad sträng, och med angivet namn |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Returnerar bildförhållandet för denna vektorbild |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/bytecontent) { get; } | Returnerar innehållet i denna EMF-bild som en binärström |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Returnerar korrekt filnamn för denna vektorbild, som består av namn och filändelse. Teoretiskt kan det skilja sig från namnet. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Bestämmer om denna rasterbild är frigjord (`true`) eller inte (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Returnerar linjära dimensioner för denna vektorbild (bredd och höjd) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Returnerar namn på denna vektorbild. Innehåller vanligtvis inte filnamnstillägg och kan teoretiskt skilja sig från filnamnet. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/textcontent) { get; } | Returnerar innehållet i denna EMF-bild som vanlig text |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/type) { get; } | Returnerar ImageType.Emf |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/dispose)() | Avslutar denna EMF-bild genom att frigöra dess innehåll och göra de flesta av dess metoder och egenskaper oanvändbara. |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Kontrollerar denna instans med den angivna för referenslikhet. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/save)(string) | Sparar denna EMF-bild till filen |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetopng)(Stream) | Sparar denna vektor‑EMF-bild som en raster‑PNG-bild |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetosvg)(Stream) | Sparar denna vektor‑EMF-bild som en vektor‑SVG-bild |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid)(Stream) | Kontrollerar om den angivna strömmen är en giltig EMF-bild |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid_1)(string) | Kontrollerar om den angivna base64‑kodade strängen är en giltig EMF-bild |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Händelse som inträffar när denna rasterbild avyttras |

### Se även

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
