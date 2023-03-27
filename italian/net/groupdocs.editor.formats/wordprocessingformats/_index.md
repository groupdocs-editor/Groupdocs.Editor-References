---
title: WordProcessingFormats
second_title: GroupDocs.Editor per Riferimento API .NET
description: Incapsula tutti i formati di WordProcessing. Include i seguenti tipi di file Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . Ulteriori informazioni sui formati di elaborazione testiQuihttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /it/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Incapsula tutti i formati di WordProcessing. Include i seguenti tipi di file: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . Ulteriori informazioni sui formati di elaborazione testi[Qui](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Restituisce un'estensione (senza carattere punto iniziale) di questo formato WordProcessing in minuscolo |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Restituisce un codice MIME per questo formato |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Restituisce un nome completo formale di questo WordProcessing format |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Restituisce l'istanza di[`WordProcessingFormats`](../wordprocessingformats) struttura, associata all'estensione del nome file specificata o genera un'eccezione, se l'estensione non può essere analizzata correttamente |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Determina se questa istanza è uguale all'altro IDocumentFormat specificato instance |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Determina se questa istanza è uguale all'altro oggetto specificato, che è presumibilmente di WordProcessingFormats in box |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Determina se questa istanza è uguale all'altra istanza di WordProcessingFormats specificata |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Restituisce un codice hash, immutabile per questa istanza |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | Restituisce il nome di questo particolare formato, uguale alla proprietà 'Nome' |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Controlla due determinate istanze di WordProcessingFormats sull'uguaglianza |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Restituisce un valore in byte dal campo sottostante di WordProcessingFormats specificato instance (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | Controlla due istanze di WordProcessingFormats sulla disuguaglianza |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 Binary File Format (DOC) rappresenta i documenti generati da Microsoft Word o altri documenti di elaborazione testi in formato file binario. Ulteriori informazioni su questo formato file[Qui](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | I file DOCM (Office Open XML WordProcessingML Macro-Enabled Document) sono documenti generati da Microsoft Word 2007 o versioni successive con la possibilità di eseguire macro. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) è un formato ben noto per i documenti di Microsoft Word. Introdotto a partire dal 2007 con il rilascio di Microsoft Office 2007, la struttura di questo nuovo formato di documento è stata modificata da semplice binario a una combinazione di file XML e binari. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | I modelli di MS Word 97-2007 sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) rappresenta il file modello creato con Microsoft Word 2007 o versioni successive. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML archiviato in un file XML flat anziché in un pacchetto ZIP |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | I file Open Document Format Text Document (ODT) sono tipi di documenti creati con applicazioni di elaborazione testi basate sul formato OpenDocument Text File. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) rappresenta i documenti modello generati dalle applicazioni in conformità con il formato standard OpenDocument di OASIS. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) rappresenta un metodo di codifica di testo e grafica formattati per l'utilizzo all'interno delle applicazioni. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Formato XML di Microsoft Office Word 2003 — WordProcessingML o WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Restituisce una classe interna, che fornisce possibilità enumerabili su tutti i formati di WordProcessing esistenti |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | Implementa l'interfaccia generica IEnumerable, che abilita una possibilità 'foreach' per WordProcessingFormats type |

### Osservazioni

codici MIME vengono presi dalle risorse fornite: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### Guarda anche

* interface [IDocumentFormat](../idocumentformat)
* spazio dei nomi [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
