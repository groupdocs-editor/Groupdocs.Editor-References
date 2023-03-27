---
title: TextualFormats
second_title: GroupDocs.Editor per Riferimento API .NET
description: Incapsula tutti i formati testuali basati su testo inclusi markup XML HTML e altri. Include i seguenti formati Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /it/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Incapsula tutti i formati testuali (basati su testo), inclusi markup (XML, HTML) e altri. Include i seguenti formati: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Restituisce un'estensione (senza carattere punto iniziale) di questo formato testuale in minuscolo |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Restituisce un codice MIME per questo formato |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Restituisce un nome completo formale di questo formato testuale |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Restituisce l'istanza di[`TextualFormats`](../textualformats) struttura, associata all'estensione del nome file specificata o genera un'eccezione, se l'estensione non può essere analizzata correttamente |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Determina se questa istanza è uguale all'altro IDocumentFormat specificato instance |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Determina se questa istanza è uguale all'altro oggetto specificato, che è presumibilmente di TextualFormats boxed |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Determina se questa istanza è uguale all'altra istanza TextualFormats specificata |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Restituisce un codice hash, immutabile per questa istanza |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Restituisce il nome di questo particolare formato, uguale alla proprietà 'Nome' |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Controlla due istanze TextualFormats date su equality |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Controlla due istanze TextualFormats date su inequality |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help è un formato binario della guida in linea proprietario di Microsoft, costituito da una raccolta di pagine HTML, un indice e altri strumenti di navigazione. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Il documento HyperText Markup Language (HTML) è l'estensione per le pagine Web create per la visualizzazione nei browser. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) è un formato di file standard aperto per la condivisione di dati che utilizza testo leggibile dall'uomo per archiviare e trasmettere dati. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown è un linguaggio di markup leggero per la creazione di testo formattato utilizzando un editor di testo semplice. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | L'incapsulamento MIME di documenti HTML aggregati è un formato di archivio di pagine Web utilizzato per combinare, in un singolo file di computer, il codice HTML e le relative risorse associate. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) rappresenta un documento di testo che contiene testo normale sotto forma di linee. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Documento XML (eXtensible Markup Language) simile all'HTML ma diverso nell'uso dei tag per la definizione degli oggetti. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Restituisce una classe interna, che fornisce possibilità enumerabili su tutti i formati testuali esistenti. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Implementa l'interfaccia generica IEnumerable, che abilita una possibilità 'foreach' per TextualFormats type |

### Guarda anche

* interface [IDocumentFormat](../idocumentformat)
* spazio dei nomi [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
