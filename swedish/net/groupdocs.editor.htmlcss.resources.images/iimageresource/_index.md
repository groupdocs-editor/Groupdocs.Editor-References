---
title: "IImageResource"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en bildresurs av vilken typ som helst, raster eller vektor"
type: docs
weight: 470
url: /sv/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

Representerar bildresurs av vilken typ som helst, raster eller vektor.

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | I en implementering bör typen returnera bildförhållandet för en specifik bild oavsett dess typ. Både vektor- och rasterbilder har ett inneboende bildförhållande mellan bredd och höjd. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | I en implementering bör typen returnera bildens linjära dimensioner. För rasterbilder är detta de inneboende dimensionerna i pixlar. Vektorbilder har däremot inga fasta dimensioner, men deras metadata kan innehålla vissa grundläggande dimensioner i olika måttenheter. |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | I en implementering bör typen returnera en specifik bildtyp som en instans av den specifika ImageType, som kapslar in all typ‑specifik information |

### Anmärkningar

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### Se även

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
