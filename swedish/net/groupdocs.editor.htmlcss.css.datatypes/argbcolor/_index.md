---
title: "ArgbColor"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar ett färgvärde i 32‑bit ARGB-format, 8 bitar per kanal inklusive transparens, med konverterare och serialiserare"
type: docs
weight: 160
url: /sv/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Representerar ett färgvärde i 32-bitars ARGB-format (8 bitar per kanal inklusive transparens) med konverterare och serialiserare

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Hämtar alfadelen av färgen. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Hämtar alfadelen av färgen i procent (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Hämtar blåa delen av färgen. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Hämtar den gröna delen av färgen. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Indikerar om detta [`ArgbColor`](../argbcolor)-objekt är standard (Transparent) – alla 4 kanaler är satta till 0 |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Oinitierad färg – alla 4 kanaler är satta till 0. Samma som Standard och Transparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Indikerar om detta [`ArgbColor`](../argbcolor)-objekt är helt ogenomskinligt, utan transparens (dess alfakanal har maximalt värde) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Indikerar om detta [`ArgbColor`](../argbcolor)-objekt är helt transparent – dess alfakanal har det minsta (0) värdet, så de andra R-, G- och B-kanalerna har ingen synlig effekt. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Indikerar om detta [`ArgbColor`](../argbcolor)-objekt är genomskinligt (varken helt transparent eller helt ogenomskinligt) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Hämtar den röda delen av färgen. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Hämtar Int32‑värdet för färgen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Skapar ett [`ArgbColor`](../argbcolor)-värde från angivna röd-, grön- och blåkanaler, medan alfakanalen är helt ogenomskinlig |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Skapar ett [`ArgbColor`](../argbcolor)-värde från angivna röd-, grön-, blå- och alfakanaler |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Skapar en helt ogenomskinlig (A=255) färg från ett enda värde, som kommer att tillämpas på alla kanaler |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Kontrollerar två [`ArgbColor`](../argbcolor) färger för likhet |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Testar om ett annat objekt är lika med detta [`ArgbColor`](../argbcolor)-instans. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Returnerar en hashkod som definierar den aktuella färgen. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Serialiserar denna [`ArgbColor`](../argbcolor)-instans till den mest lämpliga CSS-funktionsnotationen beroende på genomskinlighet |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Serialiserar denna [`ArgbColor`](../argbcolor)-instans till 'rgb'-CSS-funktionsnotationen |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Serialiserar denna [`ArgbColor`](../argbcolor)-instans till 'rgba'-CSS-funktionsnotationen |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Samma som [`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Jämför två färger och returnerar ett booleskt värde som indikerar om de två matchar. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Jämför två färger och returnerar ett booleskt värde som indikerar om de två inte matchar. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Innehåller alla \"kända färger\", som har ett fast unikt namn och värde i CSS-standarden |

### Anmärkningar

Denna typ är avsedd att vara användbar för (men inte begränsad till) CSS‑operationer. Se mer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Se även

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
