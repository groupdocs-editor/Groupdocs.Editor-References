---
title: "Lunghezza"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Rappresenta un valore di lunghezza CSS in qualsiasi unità supportata, inclusi percentuale e tipo senza unità. I valori possono essere interi o float, zero negativo e positivo. Struttura immutabile."
type: docs
weight: 230
url: /it/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Rappresenta un valore di lunghezza CSS in qualsiasi unità supportabile, inclusi percentuale e tipo senza unità. I valori possono essere interi o floating point, negativi, zero e positivi. Struttura immutabile.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Restituisce un valore numerico float dell'istanza Length. Non genera mai eccezioni - converte il valore Integer in Float se necessario. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Restituisce un valore numerico intero di questa istanza Length, se è memorizzato internamente come intero, oppure genera un'eccezione, se era originariamente memorizzato come numero float. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Restituisce se la lunghezza è espressa in unità assolute. Una tale lunghezza può essere convertita in pixel. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Indica se questa istanza Length ha un valore predefinito — zero senza unità. Identico alla proprietà IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Indica se il valore numerico di questa istanza Length è stato originariamente specificato e memorizzato come numero float (FP32). |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Indica se il valore numerico di questa istanza Length è stato originariamente specificato e memorizzato come numero intero (INT32). |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Determina se il valore numerico di questa lunghezza è un numero negativo. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Determina se il valore numerico di questa lunghezza è un numero positivo. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Restituisce se la lunghezza è espressa in unità relative. Una tale lunghezza non può essere convertita in pixel. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Il valore è di tipo senza unità, ma non è zero - è un numero positivo o negativo. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Determina se questa istanza è zero senza unità o meno. Lo zero senza unità è il valore predefinito di questo tipo. Identico alla proprietà IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Determina se il valore numerico di questa lunghezza è zero. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Restituisce il tipo di unità di questa istanza Length. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Crea e restituisce un'istanza di tipo Length a partire dal numero double specificato e dall'unità. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Crea e restituisce un'istanza di tipo Length a partire dal numero float specificato e dall'unità. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Crea e restituisce un'istanza di tipo Length a partire dal numero intero specificato e dall'unità. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Analizza e restituisce la stringa specificata come valore Length, includendo il suo valore numerico e il nome dell'unità, oppure genera un'eccezione in caso di errore. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Restituisce una copia completa di questa istanza Length. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Definisce se questo valore è uguale all'altra lunghezza specificata. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Determina se questa lunghezza è uguale all'oggetto specificato. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Calcola e restituisce un hash-code di questa istanza Length combinando gli hash-code del valore e del tipo di unità. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Restituisce una rappresentazione stringa di questa lunghezza nella sua forma nativa originale (come è memorizzata), senza convertire il valore della lunghezza in un altro tipo di unità. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Converte la lunghezza nell'unità fornita, se possibile. Se l'unità corrente o quella fornita è relativa, verrà generata un'eccezione. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Converte la lunghezza in un numero di pixel, se possibile. Se l'unità corrente è relativa, verrà generata un'eccezione. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Restituisce una rappresentazione stringa di questa lunghezza nel tipo di unità specificato. Il valore numerico verrà convertito in base al tipo di unità. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Prova a analizzare il nome dell'unità specificato e restituisce il valore corrispondente di un enum Unit. Restituisce Unit.Unitless se non riesce a trovare un'unità appropriata. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Prova a analizzare una stringa specificata come valore Length, includendo il suo valore numerico e il nome dell'unità. |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Verifica l'uguaglianza delle due lunghezze fornite. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Verifica la disuguaglianza delle due lunghezze fornite. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Moltiplica la Length fornita per il fattore specificato. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Intero zero senza unità – valore predefinito, uguale al costruttore predefinito senza parametri. |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| enum [Unit](length.unit) | Tutte le unità di lunghezza supportate |

### Osservazioni

Questo tipo copre i seguenti tipi di dati CSS: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### Vedi anche

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
