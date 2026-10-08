---
title: "TextualFormats"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Incapsula tutti i formati testuali basati su testo, inclusi markup XML HTML e altri. Include i seguenti formati Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /it/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Incapsula tutti i formati testuali (basati su testo), inclusi markup (XML, HTML) e altri. Include i seguenti formati: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ottiene l'estensione del file del formato di documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ottiene la famiglia di formato a cui appartiene il formato di documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ottiene l'identificatore univoco per la famiglia di formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ottiene il tipo MIME del formato di documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ottiene il nome della famiglia di formato. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Ottiene una collezione enumerabile di tutti i [`TextualFormats`](../textualformats). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Recupera un'istanza del tipo specificato [`TextualFormats`](../textualformats) che ha l'estensione file specificata. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina se questa istanza è uguale all'istanza specificata [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina se questa istanza è uguale all'istanza specificata [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina se questa istanza è uguale all'istanza specificata [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Restituisce un codice hash per l'oggetto corrente. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Converte una stringa che rappresenta un'estensione file in un oggetto [`TextualFormats`](../textualformats). |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help è un formato binario di aiuto online proprietario di Microsoft, composto da una raccolta di pagine HTML, un indice e altri strumenti di navigazione. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Il documento HyperText Markup Language (HTML) è l'estensione per le pagine web create per la visualizzazione nei browser. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) è un formato di file standard aperto per la condivisione di dati che utilizza testo leggibile dall'uomo per memorizzare e trasmettere i dati. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown è un linguaggio di markup leggero per creare testo formattato usando un editor di testo semplice. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | L'incapsulamento MIME di documenti HTML aggregati è un formato di archivio di pagine web usato per combinare, in un unico file informatico, il codice HTML e le sue risorse associate. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Il documento di testo semplice (TXT) rappresenta un documento di testo che contiene testo semplice sotto forma di righe. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Documento eXtensible Markup Language (XML) simile a HTML ma diverso nell'uso dei tag per definire gli oggetti. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/web/xml). |

### Vedi anche

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
