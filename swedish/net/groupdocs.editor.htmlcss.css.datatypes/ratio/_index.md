---
title: "Förhållande"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en CSS‑datatyp för förhållanden som används för att beskriva bildförhållanden i media‑frågor och för rasterbilder genom att ange proportionen mellan två enhetslösa värden som kallas täljare och nämnare. Oföränderlig struct."
type: docs
weight: 250
url: /sv/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

Representerar en \"ratio\" CSS-datatyp, som används för att beskriva bildförhållanden i media queries och för rasterbilder genom att ange förhållandet mellan två enhetslösa värden som kallas \"numerator\" och \"denominator\". Oföränderlig struktur.

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | Returnerar en nämnare för detta förhållande |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/isdefault) { get; } | Bestämmer om detta förhållande har standardvärde eller är en "1/1" (Single) |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | Returnerar en täljare för detta förhållande |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | Skapar och returnerar en Ratio‑instans från angiven täljare och nämnare |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | Beräknar och returnerar detta förhållande som ett enda flyttal |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | Returnerar en fullständig kopia av detta förhållande |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | Bestämmer om detta objekt är lika med det angivna okastade objektet, som sannolikt är en annan "Ratio"‑instans |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | Bestämmer om detta objekt är lika med den angivna "Ratio"‑instansen |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | Returnerar en hashkod för detta objekt, som inte kan ändras under dess livstid |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | Genererar och returnerar ett invers (reciprokt) förhållande för detta förhållande |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | Serialiserar detta förhållande till en sträng och returnerar den |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | Returnerar en strängrepresentation av detta förhållande; samma som "SerializeDefault()" |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | Jämför två förhållanden och returnerar ett booleskt värde som indikerar om de två matchar. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | Jämför två förhållanden och returnerar ett booleskt värde som indikerar om de två inte matchar. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | Enkel standardförhållande 1/1 |

### Anmärkningar

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### Se även

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
