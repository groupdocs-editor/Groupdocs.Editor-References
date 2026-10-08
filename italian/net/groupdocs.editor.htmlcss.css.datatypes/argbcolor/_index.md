---
title: "ArgbColor"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Rappresenta un valore di colore in formato ARGB a 32 bit, 8 bit per canale, includendo la trasparenza, con convertitori e serializzatori."
type: docs
weight: 160
url: /it/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Rappresenta un valore di lunghezza CSS in formato ARGB a 32 bit (8 bit per canale inclusa la trasparenza) con convertitori e serializzatori

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Ottiene la parte alfa del colore. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Ottiene la parte alfa del colore in percentuale (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Ottiene la parte blu del colore. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Ottiene la parte verde del colore. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Indica se questa istanza di [`ArgbColor`](../argbcolor) è predefinita (Trasparente) – tutti e 4 i canali sono impostati a 0 |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Colore non inizializzato – tutti e 4 i canali sono impostati a 0. Uguale a Predefinito e Trasparente. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Indica se questa istanza di [`ArgbColor`](../argbcolor) è completamente opaca, senza trasparenza (il suo canale Alpha ha valore massimo) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Indica se questa istanza di [`ArgbColor`](../argbcolor) è completamente trasparente – il suo canale Alpha ha il valore minimo (0), quindi gli altri canali R, G e B non hanno effetto visibile. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Indica se questa istanza di [`ArgbColor`](../argbcolor) è traslucida (non completamente trasparente, ma nemmeno completamente opaca) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Ottiene la parte rossa del colore. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Ottiene il valore Int32 del colore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Crea un valore [`ArgbColor`](../argbcolor) dai canali Rosso, Verde e Blu specificati, mentre il canale Alfa è completamente opaco |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Crea un valore [`ArgbColor`](../argbcolor) dai canali Rosso, Verde, Blu e Alfa specificati |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Crea un colore completamente opaco (A=255) da un singolo valore, che verrà applicato a tutti i canali |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Verifica l'uguaglianza di due colori [`ArgbColor`](../argbcolor) |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Verifica se un altro oggetto è uguale a questa istanza di [`ArgbColor`](../argbcolor). |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Restituisce un codice hash che definisce il colore corrente. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Serializza questa istanza di [`ArgbColor`](../argbcolor) nella notazione di funzione CSS più appropriata in base alla trasparenza |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Serializza questa istanza di [`ArgbColor`](../argbcolor) nella notazione della funzione CSS 'rgb' |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Serializza questa istanza di [`ArgbColor`](../argbcolor) nella notazione della funzione CSS 'rgba' |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Stesso di [`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Confronta due colori e restituisce un valore booleano che indica se i due corrispondono. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Confronta due colori e restituisce un valore booleano che indica se i due non corrispondono. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Contiene tutti i "colori noti", che hanno un nome unico fisso e un valore in CSS standard |

### Osservazioni

Questo tipo è progettato per essere utile per (ma non limitato a) operazioni CSS. Vedi di più: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Vedi anche

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
