---
title: "TextDecorationLineType"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Rappresenta i tipi di linea di decorazione del testo underline, underscore, overline e linethrough (barrato)."
type: docs
weight: 290
url: /it/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Rappresenta i tipi di linea di decorazione del testo: sottolineatura (underscore), sovralineatura e barrato (strikethrough)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Indica se questa istanza ha un valore iniziale — None. |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Indica se line-through (strikethrough) è abilitato. |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Indica se overline è abilitato. |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Indica se underline (underscore) è abilitato. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Restituisce un valore di tutti i flag in questa istanza come testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Crea e restituisce un'istanza di [`TextDecorationLineType`](../textdecorationlinetype) con i flag, definiti dai parametri specificati. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Indica se questa [`TextDecorationLineType`](../textdecorationlinetype) istanza è uguale a quella specificata non convertita |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Indica se questa [`TextDecorationLineType`](../textdecorationlinetype) istanza è uguale a quella specificata |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Restituisce un codice hash di questa istanza |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Restituisce un valore di tutti i flag in questa istanza come testo. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Prova a analizzare una stringa specificata e restituisce una valida istanza di [`TextDecorationLineType`](../textdecorationlinetype) |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Combina (unisce) due tipi di linea specificati e produce un nuovo tipo di linea risultante, dove le flag sono unite (unione) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Restituisce l'intersezione tra il primo e il secondo tipo di linea, dove sono abilitate solo le flag che sono abilitate simultaneamente in entrambi gli operandi. Ha la priorità più alta tra tutti gli operatori (superiore a unione e differenza) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Verifica se due valori \"TextDecorationLineType\" sono uguali |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Converte un Byte specifico (ottetto a 8 bit) al corrispondente [`TextDecorationLineType`](../textdecorationlinetype), lancia un'eccezione se la conversione non è valida (2 operatori) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Verifica se due valori \"TextDecorationLineType\" non sono uguali |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Sottrae il secondo tipo di linea specificato dal primo tipo di linea specificato e produce un nuovo tipo di linea risultante, dove sono presenti solo le flag del primo operando che non si trovano nel secondo operando (differenza) |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Ogni riga di testo ha una linea al centro. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Non produce alcuna decorazione del testo. Valore iniziale. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Ogni riga di testo ha una linea sopra di essa. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Ogni riga di testo è sottolineata. |

### Osservazioni

Struttura immutabile. Simile a https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### Vedi anche

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
