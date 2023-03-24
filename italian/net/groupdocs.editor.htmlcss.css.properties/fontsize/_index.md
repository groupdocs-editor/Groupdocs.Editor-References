---
title: FontSize
second_title: GroupDocs.Editor per Riferimento API .NET
description: Rappresenta una dimensione del carattere come ununità speciale o un valore di lunghezza che specifica la dimensione del carattere storicamente la larghezza della M maiuscola.
type: docs
weight: 290
url: /it/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Rappresenta una dimensione del carattere come un'unità speciale o un valore di lunghezza, che specifica la dimensione del carattere (storicamente la larghezza della "M" maiuscola).

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Indica se questa dimensione del carattere è definita con una dimensione assoluta come parola chiave, in base alla dimensione del carattere predefinita dell'utente (che è media) |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Indica se questa dimensione del font ha un valore iniziale (Medium) |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Indica se questa dimensione del carattere è definita con a[`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) valore |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Indica se questa dimensione del carattere è definita con una dimensione relativa come parola chiave. Il carattere sarà più grande o più piccolo rispetto alla dimensione del carattere dell'elemento genitore, approssimativamente in base al rapporto utilizzato per separare le parole chiave di dimensione assoluta. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Un valore di lunghezza, se questa dimensione del carattere è stata definita con esso o ha generato un'eccezione altrimenti |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Restituisce un valore di questa dimensione del carattere come stringa |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Crea una dimensione del carattere dalla lunghezza specificata |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Determina se questa istanza della dimensione del carattere è uguale a specified |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Determina se questa istanza della dimensione del carattere è uguale a uncasted specificato |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Restituisce un codice hash per questa istanza |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Tenta di riconoscere una parola chiave specificata come un valore di parola chiave appropriato di 'font-size' e di restituirlo in caso di successo o NULL in caso di errore. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Controlla se due valori "FontSize" sono uguali |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Controlla se due valori "FontSize" non sono uguali |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | La dimensione assoluta normalmente grande |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Dimensione relativa più grande: il carattere sarà più grande rispetto alla dimensione del carattere dell'elemento genitore, approssimativamente in base al rapporto utilizzato per separare le parole chiave di dimensione assoluta sopra. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Taglia media. Valore iniziale. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | La dimensione assoluta normalmente piccola |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Dimensione relativa più piccola: il carattere sarà più piccolo rispetto alla dimensione del carattere dell'elemento genitore, approssimativamente in base al rapporto utilizzato per separare le parole chiave di dimensione assoluta sopra. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | La mediocre grande dimensione assoluta |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | La mediocre piccola dimensione assoluta |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | La dimensione assoluta molto grande |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | La piccolissima dimensione assoluta |

### Guarda anche

* spazio dei nomi [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
