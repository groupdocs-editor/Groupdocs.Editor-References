---
title: FixedLayoutFormats
second_title: GroupDocs.Editor per Riferimento API .NET
description: Incapsula tutti i formati a layout fisso noti anche come pagina fissa inclusi PDF e XPS questo non include le immagini raster
type: docs
weight: 80
url: /it/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

Incapsula tutti i formati a layout fisso (noti anche come "pagina fissa"), inclusi PDF e XPS (questo non include le immagini raster)

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | Restituisce un'estensione (senza carattere punto iniziale) di questo formato a layout fisso in minuscolo |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | Restituisce un codice MIME per questo formato |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | Restituisce un nome completo formale di questo layout fisso format |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Restituisce l'istanza di[`FixedLayoutFormats`](../fixedlayoutformats)struttura, associata all'estensione del nome file specificata o genera un'eccezione, se l'estensione non può essere analizzata correttamente |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | Determina se questa istanza è uguale all'altra istanza FixedLayoutFormats specificata |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | Determina se questa istanza è uguale all'altro IDocumentFormat specificato instance |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | Determina se questa istanza è uguale all'altro oggetto specificato, che è presumibilmente di FixedLayoutFormats boxed |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | Restituisce un codice hash, immutabile per questa istanza |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | Restituisce il nome di questo particolare formato, uguale alla proprietà 'Nome' |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | Controlla due determinate istanze FixedLayoutFormats su equality |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | Restituisce un valore in byte dal campo sottostante di FixedLayoutFormats specificato instance (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | Controlla due determinate istanze FixedLayoutFormats su disuguaglianza |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era introdurre uno standard per la rappresentazione di documenti e altro materiale di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. Ulteriori informazioni su questo formato di file[qui](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | Il file XPS rappresenta i file di layout di pagina basati sulle specifiche XML Paper create da Microsoft. È stato sviluppato per sostituire il formato di file EMF ed è simile al formato di file PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento. Ulteriori informazioni su questo formato di file[qui](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | Restituisce una classe interna, che fornisce possibilità enumerabili su tutti i formati a layout fisso esistenti |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | Implementa l'interfaccia generica IEnumerable, che abilita una possibilità 'foreach' per il tipo FixedLayoutFormats |

### Osservazioni

Varie applicazioni di visualizzazione o pubblicazione di documenti consentono agli utenti di aprire (Adobe Acrobat, XPS Viewer) e talvolta modificare (Adobe InDesign) documenti di formati specifici. Queste applicazioni in genere producono i cosiddetti documenti in formato "pagina fissa". Un tale formato di documento descrive esattamente dove è posizionato il contenuto di un documento su ogni pagina. Internamente, il formato PDF o XPS contiene una descrizione di ogni pagina, nonché istruzioni di disegno, specificando il layout del contenuto sulla pagina. Questo è simile ai formati immagine, che descrivono dove viene mostrato il contenuto in forma raster o vettoriale.

### Guarda anche

* interface [IDocumentFormat](../idocumentformat)
* spazio dei nomi [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
