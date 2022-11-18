---
title: Dimensions
second_title: GroupDocs.Editor för .NET API-referens
description: Representerar de linjära dimensionerna bredd och höjd för en rektangulär rasterbild i godtycklig enhet. Oföränderlig struktur.
type: docs
weight: 360
url: /sv/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

Representerar de linjära dimensionerna (bredd och höjd) för en rektangulär rasterbild i godtycklig enhet. Oföränderlig struktur.

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | Skapar en ny instans från specificerad bredd och höjd |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | Returnerar en tom Dimensions-instans |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | Returnerar ett område (bredd x höjd) |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | Bildförhållande för dessa dimensioner som bredd/höjd |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | Returnerar höjden på bilden |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | Avgör om denna "Dimensions"-instans är tom och standard, dvs. den lagrar inte korrekt bredd och höjd |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | Bestämmer om specificerade 'Dimensioner' representerar kvadrat, dvs om bredden är lika med height |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | Returnerar bredden på bilden |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromSize](../../groupdocs.editor.htmlcss.resources.images/dimensions/fromsize)(Size) | Genererar och returnerar en ny instans från specificerad System.Drawing.Size instans |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | Returnerar en fullständig kopia av denna instans |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | Bestämmer om denna instans är lika med specificerad "Dimensions" instans |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | Bestämmer om den här instansen är lika med det angivna ocastade objektet, vilket förmodligen är en annan "Dimensions"-instans |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | Returnerar en hashkod för denna instans, som inte kan ändras under dess livstid |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | Skapar och returnerar en ny "Dimensions"-instans, som ändras proportionellt från nuvarande, baserat på specificerad höjd |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | Skapar och returnerar en ny "Dimensions"-instans, som ändras proportionellt från nuvarande, baserat på specificerad width |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | Returnerar en strängrepresentation av denna "Dimensioner" |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | Kontrollerar om två "Dimensioner"-värden är lika, dvs. de har lika bredd och höjd, eller båda är tomma |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | Kontrollerar om två "Dimensioner"-värden inte är lika, dvs deras motsvarande bredd och/eller höjd är olika |

### Se även

* namnutrymme [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->