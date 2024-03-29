---
title: EBookFormats
second_title: GroupDocs.Editor per Riferimento API .NET
description: Incapsula tutti i formati di eBook. Include i seguenti tipi di file Mobi./ebookformats/mobi  Epub./ebookformats/epub  Azw3./ebookformats/azw3
type: docs
weight: 40
url: /it/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats structure

Incapsula tutti i formati di eBook. Include i seguenti tipi di file: [`Mobi`](./mobi) , [`Epub`](./epub) , [`Azw3`](./azw3)

```csharp
public struct EBookFormats : IDocumentFormat, IEquatable<EBookFormats>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/ebookformats/extension) { get; } | Restituisce un'estensione (senza carattere punto iniziale) di questo formato EBook in minuscolo |
| [Mime](../../groupdocs.editor.formats/ebookformats/mime) { get; } | Restituisce un codice MIME per questo formato |
| [Name](../../groupdocs.editor.formats/ebookformats/name) { get; } | Restituisce un nome completo formale di questo formato eBook |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | Restituisce l'istanza di[`EBookFormats`](../ebookformats) struttura, associata all'estensione del nome file specificata o genera un'eccezione, se l'estensione non può essere analizzata correttamente |
| [Equals](../../groupdocs.editor.formats/ebookformats/equals#equals)(EBookFormats) | Determina se questa istanza è uguale all'altra istanza EBookFormats specificata |
| [Equals](../../groupdocs.editor.formats/ebookformats/equals#equals_1)(IDocumentFormat) | Determina se questa istanza è uguale all'altro IDocumentFormat specificato instance |
| override [Equals](../../groupdocs.editor.formats/ebookformats/equals#equals_2)(object) | Determina se questa istanza è uguale all'altro oggetto specificato, che è presumibilmente di EBookFormats in box |
| override [GetHashCode](../../groupdocs.editor.formats/ebookformats/gethashcode)() | Restituisce un codice hash, immutabile per questa istanza |
| override [ToString](../../groupdocs.editor.formats/ebookformats/tostring)() | Restituisce un nome di formato di questo formato |
| [operator ==](../../groupdocs.editor.formats/ebookformats/op_equality) | Controlla due istanze EBookFormats date sull'uguaglianza |
| [operator !=](../../groupdocs.editor.formats/ebookformats/op_inequality) | Controlla due istanze EBookFormats date sulla disuguaglianza |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3, noto anche come Kindle Format 8 (KF8), è la versione modificata del formato di file digitale di ebook AZW sviluppato per i dispositivi Amazon Kindle. Il formato è un miglioramento dei vecchi file AZW. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | Il formato di pubblicazione elettronica (ePub) è un formato di file di e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/ebook/epub/) . |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI è il nome dato al formato sviluppato per il MobiPocket Reader. Attualmente è utilizzato da Amazon con uno schema DRM leggermente diverso e chiamato AZW. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/ebook/mobi/) . |
| static readonly [All](../../groupdocs.editor.formats/ebookformats/all) | Restituisce una classe interna, che fornisce possibilità enumerabili su tutti i formati di eBook esistenti |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [AllEnumerable](ebookformats.allenumerable) | Implementa l'interfaccia generica IEnumerable, che abilita una possibilità 'foreach' per EBookFormats type |

### Osservazioni

Ulteriori informazioni sul formato Mobi[Qui](https://docs.fileformat.com/ebook/mobi/) , sul formato AZW3[Qui](https://docs.fileformat.com/ebook/azw3/) e sul formato ePub[Qui](https://docs.fileformat.com/ebook/epub/) .

### Guarda anche

* interface [IDocumentFormat](../idocumentformat)
* spazio dei nomi [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
