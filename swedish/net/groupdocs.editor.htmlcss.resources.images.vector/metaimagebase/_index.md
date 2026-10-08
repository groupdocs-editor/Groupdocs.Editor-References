---
title: "MetaImageBase"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Bas‑abstrakt klass för WMF‑ och EMF‑bildformat"
type: docs
weight: 570
url: /sv/net/groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
## MetaImageBase class

Bas‑abstrakt klass för WMF‑ och EMF‑bildformat

```csharp
public abstract class MetaImageBase : VectorImageResourceBase
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Returnerar bildförhållandet för denna vektorbild |
| abstract [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/bytecontent) { get; } | Den implementerande typen bör returnera innehållet i denna vektorbild som en byte‑ström |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Returnerar korrekt filnamn för denna vektorbild, som består av namn och filändelse. Teoretiskt kan det skilja sig från namnet. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Bestämmer om denna rasterbild är frigjord (`true`) eller inte (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Returnerar linjära dimensioner för denna vektorbild (bredd och höjd) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Returnerar namn på denna vektorbild. Innehåller vanligtvis inte filnamnstillägg och kan teoretiskt skilja sig från filnamnet. |
| abstract [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/textcontent) { get; } | I implementeringen bör typen returnera innehållet i denna vektorbild i textform: base64‑kodad XML avseende bildtypen |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/type) { get; } | I implementeringen bör typen returnera information om typen av vektorbilden |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/dispose)() | I implementeringen bör typen avsluta denna instans |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Kontrollerar denna instans med den angivna för referenslikhet. |
| abstract [Save](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/save)(string) | I implementeringen bör typen spara denna bild till disken med angiven sökväg |
| abstract [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/savetopng)(Stream) | I implementeringen bör typen spara den aktuella vektorbilden i rasterformatet PNG till den angivna byte‑strömmen |
| abstract [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/savetosvg)(Stream) | I implementeringen bör WMF- eller EMF-typen spara den aktuella vektormeta‑bilden i vektorformatet SVG till den angivna byte‑strömmen |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Händelse som inträffar när denna rasterbild avyttras |

### Anmärkningar

Denna abstrakta klass ärvs av [`WmfImage`](../wmfimage) och [`EmfImage`](../emfimage)

### Se även

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
