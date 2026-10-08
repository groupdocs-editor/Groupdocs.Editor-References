---
title: "Dimensioner"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar de linjära dimensionerna bredd och höjd för en rasterrektangulär bild i en godtycklig enhet. Oföränderlig struct."
type: docs
weight: 450
url: /sv/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

Representerar de linjära dimensionerna (bredd och höjd) för en rasterrektangulär bild i en godtycklig enhet. Oföränderlig struct.

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | Skapar en ny instans från angiven bredd och höjd. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | Returnerar en tom Dimensions‑instans |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | Returnerar ett område (Bredd x Höjd) |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | Bildförhållande för dessa dimensioner som bredd/höjd |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | Returnerar bildens höjd. |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | Bestämmer om detta "Dimensions"‑objekt är tomt och standard, d.v.s. det lagrar inte korrekt bredd och höjd |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | Bestämmer om angivet 'Dimensions' representerar en kvadrat, d.v.s. om bredden är lika med höjden |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | Returnerar bildens bredd |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | Returnerar en fullständig kopia av detta objekt |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | Avgör om detta objekt är lika med den angivna "Dimensions"-instansen |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | Avgör om detta objekt är lika med det angivna okastade objektet, som sannolikt är en annan "Dimensions"-instans |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | Returnerar en hashkod för detta objekt, som inte kan ändras under dess livstid |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | Skapar och returnerar en ny "Dimensions"-instans som är proportionellt omdimensionerad från den nuvarande, baserat på angiven höjd |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | Skapar och returnerar en ny "Dimensions"-instans som är proportionellt omdimensionerad från den nuvarande, baserat på angiven bredd |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | Returnerar en strängrepresentation av denna "Dimensions" |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | Kontrollerar om två "Dimensions"-värden är lika, d.v.s. de har samma bredd och höjd, eller båda är tomma |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | Kontrollerar om två "Dimensions"-värden inte är lika, d.v.s. deras motsvarande bredd och/eller höjd skiljer sig |

### Se även

* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
