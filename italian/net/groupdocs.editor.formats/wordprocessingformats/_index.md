---
title: "WordProcessingFormats"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Raggruppa tutti i formati WordProcessing. Include i seguenti tipi di file"
type: docs
weight: 150
url: /it/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Raccoglie tutti i formati di elaborazione testi. Include i seguenti tipi di file:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Scopri di più sui formati di elaborazione testi [qui](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ottiene l'estensione del file del formato di documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ottiene la famiglia di formato a cui appartiene il formato di documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ottiene l'identificatore univoco per la famiglia di formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ottiene il tipo MIME del formato di documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ottiene il nome della famiglia di formato. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Ottiene una collezione enumerabile di tutti i [`WordProcessingFormats`](../wordprocessingformats). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Recupera un'istanza del tipo specificato [`WordProcessingFormats`](../wordprocessingformats) che ha l'estensione di file specificata. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina se questa istanza è uguale all'istanza specificata [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina se questa istanza è uguale all'istanza specificata [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina se questa istanza è uguale all'istanza specificata [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Restituisce un codice hash per l'oggetto corrente. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Converte una stringa che rappresenta un'estensione di file in un oggetto [`WordProcessingFormats`](../wordprocessingformats). |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | Il formato binario di MS Word 97-2007 (DOC) rappresenta documenti generati da Microsoft Word o altri programmi di elaborazione testi in formato binario. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | I file Office Open XML WordProcessingML Macro-Enabled Document (DOCM) sono documenti generati da Microsoft Word 2007 o versioni successive con la capacità di eseguire macro. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) è un formato molto diffuso per i documenti Microsoft Word. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | Il modello MS Word 97-2007 (DOT) è un file modello creato da Microsoft Word con impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) rappresenta file modello creati con Microsoft Word 2007 o versioni successive. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML memorizzato in un file XML piatto anziché in un pacchetto ZIP. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | I file Open Document Format Text Document (ODT) sono un tipo di documento creati con applicazioni di elaborazione testi basate sul formato OpenDocument Text File. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) rappresenta documenti modello generati da applicazioni conformi al formato standard OpenDocument dell'OASIS. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) rappresenta un metodo di codifica di testo formattato e grafica per l'uso all'interno delle applicazioni. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML Format — WordProcessingML o WordML (.XML). |

### Vedi anche

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
