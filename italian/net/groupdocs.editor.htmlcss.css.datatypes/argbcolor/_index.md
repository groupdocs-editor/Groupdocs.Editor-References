---
title: ArgbColor
second_title: GroupDocs.Editor per Riferimento API .NET
description: Rappresenta un valore di colore in formato ARGB con convertitori e serializzatori
type: docs
weight: 190
url: /it/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Rappresenta un valore di colore in formato ARGB con convertitori e serializzatori

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
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Colore non inizializzato: tutti e 4 i canali sono impostati su 0. Uguale a Default e Transparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Indica se this[`ArgbColor`](../argbcolor) l'istanza è completamente opaca, senza trasparenza (il suo canale Alpha ha un valore massimo) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Indica se this[`ArgbColor`](../argbcolor) l'istanza è completamente trasparente: il suo canale alfa ha il valore minimo (0), quindi gli altri canali R, G e B non hanno alcun effetto visibile. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Indica se this[`ArgbColor`](../argbcolor) l'istanza è traslucida (non completamente trasparente, ma anche non completamente opaca) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Ottiene la parte rossa del colore. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Ottiene il valore Int32 del colore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Crea uno[`ArgbColor`](../argbcolor) valore dai canali rosso, verde e blu specificati, mentre il canale alfa è completamente opaco |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Crea uno[`ArgbColor`](../argbcolor) valore dai canali rosso, verde, blu e alfa specificati |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Crea un colore completamente opaco (A=255) da un singolo valore, che verrà applicato a tutti i canali |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Controlla due[`ArgbColor`](../argbcolor) colori per l'uguaglianza |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Verifica se un altro oggetto è uguale a questo[`ArgbColor`](../argbcolor) istanza. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Restituisce un codice hash che definisce il colore corrente. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Serializza questo[`ArgbColor`](../argbcolor)istanza alla notazione della funzione CSS più appropriata a seconda di translucency |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Serializza questo[`ArgbColor`](../argbcolor) istanza alla funzione CSS 'rgb' notation |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Serializza questo[`ArgbColor`](../argbcolor) istanza alla funzione CSS 'rgba' notation |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Uguale a[`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Confronta due colori e restituisce un valore booleano che indica se i due corrispondono. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Confronta due colori e restituisce un valore booleano che indica se i due non corrispondono. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Contiene tutti i "colori noti", che hanno un nome e un valore univoci fissi in CSS standart |

### Osservazioni

Questo tipo è progettato per essere utile per (ma non limitato a) operazioni CSS. Scopri di più: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Guarda anche

* interface [ICssDataType](../icssdatatype)
* spazio dei nomi [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
