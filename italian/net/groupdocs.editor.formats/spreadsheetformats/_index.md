---
title: SpreadsheetFormats
second_title: GroupDocs.Editor per Riferimento API .NET
description: Incapsula tutti i formati di fogli di calcolo binari XML e testuali esclusi tutti i formati basati su delimitatori testuali con separatore come CSV TSV delimitato da punto e virgola ecc. in cui è possibile salvare la cartella di lavoro. Include i seguenti formati Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . Ulteriori informazioni sui formati dei fogli di lavoroquihttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /it/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Incapsula tutti i formati di fogli di calcolo binari, XML e testuali (esclusi tutti i formati basati su delimitatori testuali con separatore come CSV, TSV, delimitato da punto e virgola ecc.), in cui è possibile salvare la cartella di lavoro. Include i seguenti formati: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Ulteriori informazioni sui formati dei fogli di lavoro[qui](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Restituisce un'estensione (senza carattere punto iniziale) di questo formato Foglio di calcolo in minuscolo |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Restituisce un codice MIME per questo formato |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Restituisce un nome completo formale di questo formato foglio di calcolo |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Restituisce l'istanza di[`SpreadsheetFormats`](../spreadsheetformats)struttura, associata all'estensione del nome file specificata o genera un'eccezione, se l'estensione non può essere analizzata correttamente |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Determina se questa istanza è uguale all'altro IDocumentFormat specificato instance |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Determina se questa istanza è uguale all'altro oggetto specificato, che è presumibilmente di SpreadsheetFormats in box |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Determina se questa istanza è uguale all'altra istanza SpreadsheetFormats specificata |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Restituisce un codice hash, immutabile per questa istanza |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Controlla due istanze SpreadsheetFormats su equality |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Controlla due istanze SpreadsheetFormats su disuguaglianza |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | I documenti con valori separati da virgola (CSV) rappresentano testo semplice che contiene record di dati con valori separati da virgola. Ogni riga in un file CSV è un nuovo record dall'insieme di record contenuti nel file. Ulteriori informazioni su questo formato di file[qui](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Formato di interscambio dati (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS) — memorizzato come un singolo documento XML non compresso |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS) sta per OpenDocument Spreadsheet Document formato modificabile dall'utente. I dati vengono memorizzati all'interno del file ODF in righe e colonne. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Formato XML Microsoft Office Excel 2002 ed Excel 2003 |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice o OpenOffice.org Calc Foglio di calcolo XML (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Il formato di file con valori separati da tabulazioni (TSV) rappresenta i dati separati da tabulazioni in formato di testo normale. Il formato file, simile a CSV, viene utilizzato per l'organizzazione dei dati in modo strutturato al fine di importare ed esportare tra diverse applicazioni. Ulteriori informazioni su questo formato file[qui](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Componente aggiuntivo di Excel (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binary File Format (XLS) rappresenta i file che possono essere creati da Microsoft Excel e da altri programmi simili per fogli di calcolo come OpenOffice Calc o Apple Numbers. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Cartella di lavoro binaria di Excel (XLSB) specifica il formato di file binario di Excel, ovvero una raccolta di record e strutture che specificano il contenuto della cartella di lavoro di Excel. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) è un tipo di file di foglio elettronico che supporta le macro. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) rappresenta i documenti introdotti da Microsoft con il rilascio di Microsoft Office 2007. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 Template (XLT) rappresenta i file modello creati con Microsoft Excel, un'applicazione per fogli di calcolo inclusa nella suite Microsoft Office. Microsoft Office 97-2003 supportava la creazione di nuovi file XLT e l'apertura di questi. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM) rappresenta i file generati da Microsoft Excel come file modello con attivazione macro. I file XLTM sono simili a XLTX nella struttura diversa da quella successiva non supporta la creazione di file modello con macro. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Il file Office Open XML Template Macro-Free (XLTX) rappresenta il modello Microsoft Excel basato sulle specifiche del formato file Office OpenXML. Viene utilizzato per creare un file modello standard che può essere utilizzato per generare file XLSX che presentano le stesse impostazioni specificate nel file XLTX. Ulteriori informazioni su questo formato file[qui](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Restituisce una classe interna, che fornisce possibilità enumerabili su tutti i formati di fogli di calcolo esistenti |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Implementa l'interfaccia generica IEnumerable, che abilita una possibilità 'foreach' per SpreadsheetFormats type |

### Guarda anche

* interface [IDocumentFormat](../idocumentformat)
* spazio dei nomi [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
