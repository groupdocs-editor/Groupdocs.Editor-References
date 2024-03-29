---
title: Ratio
second_title: GroupDocs.Editor per Riferimento API .NET
description: Rappresenta un tipo di dati CSS ratio utilizzato per descrivere le proporzioni nelle query multimediali e per le immagini raster denotando la proporzione tra due valori senza unità chiamati numeratore e denominatore. Struttura immutabile
type: docs
weight: 280
url: /it/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

Rappresenta un tipo di dati CSS "ratio", utilizzato per descrivere le proporzioni nelle query multimediali e per le immagini raster denotando la proporzione tra due valori senza unità chiamati "numeratore" e "denominatore". Struttura immutabile

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | Restituisce un denominatore di questo rapporto |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | Restituisce un numeratore di questo rapporto |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | Crea e restituisce un'istanza di Ratio dal numeratore e dal denominatore specificati |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | Calcola e restituisce questo rapporto come un singolo numero in virgola mobile |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | Restituisce una copia completa di questo rapporto |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | Determina se questa istanza è uguale all'oggetto non cast specificato, che presumibilmente è un'altra istanza "Ratio" |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | Determina se questa istanza è uguale al "Rapporto" specificato instance |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | Restituisce un codice hash per questa istanza, che non può essere modificato durante la sua durata |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | Genera e restituisce un rapporto inverso (reciproco) per questo rapporto |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | Serializza questo rapporto sulla stringa e lo restituisce |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | Restituisce una rappresentazione in forma di stringa di questo rapporto; uguale a "SerializeDefault()" |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | Confronta due rapporti e restituisce un valore booleano che indica se i due corrispondono. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | Confronta due rapporti e restituisce un valore booleano che indica se i due non corrispondono. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | Singolo rapporto predefinito 1/1 |

### Osservazioni

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### Guarda anche

* interface [ICssDataType](../icssdatatype)
* spazio dei nomi [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
