---
title: "ImageType"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar ett stödjande bildformat som stödjer både raster- och vektorformat"
type: docs
weight: 480
url: /sv/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

Representerar en stödjande bildtyp (format), stöder både raster- och vektorformat.

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | BMP‑bildformat |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | EMF (Enhanced MetaFile) vektor‑bildformat |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | GIF‑bildformat |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | ICON‑bildformat |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | JPEG‑bildformat |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | PNG‑bildformat |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | SVG vektor‑bildformat |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | TIFF (Tagged Image File Format) raster‑bildformat |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | Odefinierad bildtyp – speciellt värde som normalt inte bör förekomma |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | WMF (Windows MetaFile) vektorbildtyp |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | Filändelse (utan inledande punkt) för en viss bildtyp i gemener. För den odefinierade typen returneras en sträng 'unsefined'. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | Returnerar ett formellt namn för detta bildformat. Returnerar aldrig NULL. Om instansen inte är korrupt kastas aldrig ett undantag. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | Anger om detta specifika format är vektor (true) eller raster (false) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | MIME-kod för en viss bildtyp som en sträng. För den odefinierade typen returneras en sträng 'unsefined'. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | Returnerar ImageType‑värde, som motsvarar filändelsen, som extraheras från det angivna filnamnet |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | Returnerar ImageType‑värde, som motsvarar den angivna MIME‑koden |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | Bestämmer om detta objekt är lika med den angivna "ImageType"‑instansen |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | Bestämmer om detta objekt är lika med det angivna okastade objektet, som sannolikt är en annan "ImageType"‑instans |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | Returnerar en hash‑kod, som är ett oföränderligt tal för detta specifika objekt |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | Returnerar en FormalName‑egenskap |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | Definierar om två specifika ImageType‑instanser är lika |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | Definierar om två specifika ImageType‑instanser inte är lika |

### Se även

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
