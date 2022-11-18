---
title: Length
second_title: GroupDocs.Editor per Riferimento API .NET
description: Rappresenta un valore di lunghezza CSS in qualsiasi unità supportata inclusa la percentuale e il tipo senza unità. I valori possono essere interi o float negativi zero e positivi. Struttura immutabile.
type: docs
weight: 190
url: /it/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Rappresenta un valore di lunghezza CSS in qualsiasi unità supportata, inclusa la percentuale e il tipo senza unità. I valori possono essere interi o float, negativi, zero e positivi. Struttura immutabile.

```csharp
public struct Length : ICloneable, IEquatable<  >, IEquatable<Length>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Restituisce un valore numerico float dell'istanza Length. Non genera mai un'eccezione: converte il valore intero in virgola mobile se necessario. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Restituisce un valore numerico intero di questa istanza di Length, se è memorizzato internamente come numero intero, o genera un'eccezione, se originariamente era memorizzato come numero float. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Ottiene se la lunghezza è espressa in unità assolute. Tale lunghezza può essere convertita in pixel. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Indica se questa istanza di Length ha un valore predefinito: zero senza unità. Uguale alla proprietà IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Indica se il valore numerico di questa istanza di Length è stato originariamente specificato e archiviato come float (FP32) numero |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Indica se il valore numerico di questa istanza di Length è stato originariamente specificato e archiviato come numero intero (INT32) number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Determina se il valore numerico di questa lunghezza è un numero negativo |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Determina se il valore numerico di questa lunghezza è un numero positivo |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Ottiene se la lunghezza è data in unità relative. Tale lunghezza non può essere convertita in pixel. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Il valore ha un tipo senza unità, ma non è uno zero - numero positivo o negativo |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Determina se questa istanza è uno zero senza unità o meno. Zero senza unità è il valore predefinito di questo tipo. Uguale alla proprietà IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Determina se il valore numerico di questa lunghezza è un numero zero |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Restituisce un tipo di unità di questa istanza di Lunghezza. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Crea e restituisce un'istanza di tipo Length in base al numero doppio specificato e all'unità |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Crea e restituisce un'istanza di tipo Length in base al numero float specificato e all'unità |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Crea e restituisce un'istanza di tipo Length in base al numero intero specificato e all'unità |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Analizza e restituisce la stringa specificata come valore di lunghezza, incluso il valore numerico e il nome dell'unità, oppure genera un'eccezione in caso di errore |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Restituisce una copia completa di questa istanza di Lunghezza |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Definisce se questo valore è uguale all'altra lunghezza specificata |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Determina se questa lunghezza è uguale all'oggetto specificato |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Calcola e restituisce un codice hash di questa istanza di Lunghezza combinando i codici hash del valore e del tipo di unità |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Restituisce una rappresentazione di stringa di questa lunghezza nella sua forma nativa originale (così come è memorizzata), senza convertire il valore della lunghezza in un altro tipo di unità |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Converte la lunghezza nell'unità data, se possibile. Se l'attuale o l'unità data è relativa, verrà generata un'eccezione. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Converte la lunghezza in un numero di pixel, se possibile. Se l'unità corrente è relativa, verrà generata un'eccezione. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Restituisce una rappresentazione di stringa di questa lunghezza nel tipo di unità specificato. Il valore numerico verrà convertito in corrispondenza della modifica del tipo di unità. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Tenta di analizzare il nome dell'unità specificata e restituire il valore corrispondente di un'unità enum. Restituisce Unit.Unitless se non riesce a trovare l'unità appropriata. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Tenta di analizzare una stringa specificata come un valore Lunghezza, incluso il suo valore numerico e il nome dell'unità |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Controlla l'uguaglianza delle due lunghezze date. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Controlla la disuguaglianza delle due lunghezze date. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Intero senza unità zero - valore predefinito, uguale al costruttore senza parametri predefinito |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| enum [Unit](length.unit) | Tutte le unità di lunghezza supportate |

### Osservazioni

Questo tipo copre i seguenti tipi di dati CSS: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/percentuale

### Guarda anche

* spazio dei nomi [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
