---
title: "FontSize"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Rappresenta la dimensione del carattere come un'unità speciale o un valore di lunghezza che specifica la dimensione del carattere, storicamente la larghezza della M maiuscola."
type: docs
weight: 260
url: /it/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Rappresenta una dimensione del carattere come unità speciale o valore di lunghezza, che specifica la dimensione del carattere (storicamente la larghezza della lettera maiuscola \"M\").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Indica se questa dimensione del carattere è definita con una dimensione assoluta come parola chiave, basata sulla dimensione predefinita del carattere dell'utente (che è media). |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Indica se questa dimensione del carattere ha un valore iniziale (Media). |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Indica se questa dimensione del carattere è definita con un valore [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length). |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Indica se questa dimensione del carattere è definita con una dimensione relativa come parola chiave. Il carattere sarà più grande o più piccolo rispetto alla dimensione del carattere dell'elemento genitore, approssimativamente secondo il rapporto usato per separare le parole chiave di dimensione assoluta. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Un valore di lunghezza, se questa dimensione del carattere è stata definita con esso, altrimenti viene sollevata un'eccezione. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Restituisce un valore di questa dimensione del carattere come stringa. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Crea una dimensione del carattere da una lunghezza specificata. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Determina se questa istanza di dimensione del carattere è uguale a quella specificata. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Determina se questa istanza di dimensione del carattere è uguale a quella specificata non convertita. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Restituisce un codice hash per questa istanza |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Cerca di riconoscere una parola chiave specificata come valore corretto della parola chiave 'font-size' e la restituisce in caso di successo o NULL in caso di fallimento. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Verifica se due valori "FontSize" sono uguali. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Verifica se due valori "FontSize" non sono uguali. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | La dimensione assoluta normalmente grande. |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Dimensione relativa più grande - il carattere sarà più grande rispetto alla dimensione del carattere dell'elemento genitore, approssimativamente secondo il rapporto usato per separare le parole chiave di dimensione assoluta sopra. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Dimensione media. Valore iniziale. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | La dimensione assoluta normalmente piccola. |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Dimensione relativa più piccola - il carattere sarà più piccolo rispetto alla dimensione del carattere dell'elemento genitore, approssimativamente secondo il rapporto usato per separare le parole chiave di dimensione assoluta sopra. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | La dimensione assoluta mediamente grande. |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | La dimensione assoluta mediamente piccola. |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | La dimensione assoluta molto grande. |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | La dimensione assoluta molto piccola |

### Vedi anche

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
