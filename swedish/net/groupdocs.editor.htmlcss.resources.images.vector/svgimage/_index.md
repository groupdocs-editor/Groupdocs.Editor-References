---
title: "SvgImage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en vektorbild i SVG (Scalable Vector Graphics)-format med dess metadata, dimensioner och ytterligare metoder för att spara till PNG"
type: docs
weight: 580
url: /sv/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

Representerar en vektorbild i SVG (Scalable Vector Graphics)-format med dess metadata (dimensioner) och ytterligare metoder (sparar till PNG)

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | Skapar en ny SvgImage-instans från innehåll, representerat som byte‑ström, och med angivet namn |
| [SvgImage](svgimage#constructor_1)(string, string) | Skapar en ny SvgImage-instans från innehåll, representerat som vanlig sträng, och med angivet namn |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Returnerar bildförhållandet för denna vektorbild |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | Returnerar innehållet i denna SVG-bild som en binärström med originalposition |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Returnerar korrekt filnamn för denna vektorbild, som består av namn och filändelse. Teoretiskt kan det skilja sig från namnet. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Bestämmer om denna rasterbild är frigjord (`true`) eller inte (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Returnerar linjära dimensioner för denna vektorbild (bredd och höjd) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Returnerar namn på denna vektorbild. Innehåller vanligtvis inte filnamnstillägg och kan teoretiskt skilja sig från filnamnet. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | Returnerar innehållet i denna SVG-bild som base64‑kodad binärt innehåll (inte som rå text i XML‑format) |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | Returns [`Svg`](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | Returnerar innehållet i denna SVG-bild i dess ursprungliga XML‑kompatibla textform |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | Avslutar denna rasterbild genom att frigöra dess innehåll och göra de flesta av dess metoder och egenskaper oanvändbara |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Kontrollerar denna instans med den angivna för referenslikhet. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | Sparar denna SVG-bild till filen |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | Sparar denna vektor‑SVG-bild som en raster‑PNG-bild |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | Utför en ytlig kontroll för att avgöra om angivet textbaserat XML‑kompatibelt innehåll representerar en SVG-bild |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Händelse som inträffar när denna rasterbild avyttras |

### Se även

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
