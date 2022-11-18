---
title: PresentationFormats
second_title: GroupDocs.Editor per Riferimento API .NET
description: Incapsula tutti i formati di presentazione. Include i seguenti formati Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. Ulteriori informazioni sui formati di presentazionequihttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /it/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Incapsula tutti i formati di presentazione. Include i seguenti formati: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). Ulteriori informazioni sui formati di presentazione[qui](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Restituisce un'estensione (senza carattere punto iniziale) di questo formato Presentazione in minuscolo |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Restituisce un codice MIME per questo formato |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Restituisce un nome completo formale di questo formato di presentazione |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Restituisce l'istanza di[`PresentationFormats`](../presentationformats)struttura, associata all'estensione del nome file specificata o genera un'eccezione, se l'estensione non può essere analizzata correttamente |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Determina se questa istanza è uguale all'altro IDocumentFormat specificato instance |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Determina se questa istanza è uguale all'altro oggetto specificato, che è presumibilmente di PresentationFormats in box |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Determina se questa istanza è uguale all'altra istanza di PresentationFormats specificata |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Restituisce un codice hash, immutabile per questa istanza |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Controlla due istanze di PresentationFormats sull'uguaglianza |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Controlla due istanze di PresentationFormats su disuguaglianza |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | Il file OpenDocument Presentation (ODP) rappresenta il formato di file di presentazione utilizzato da OpenOffice.org nello standard OASISOpen. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | Il file modello di presentazione OpenDocument (OTP) rappresenta i file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument. Ulteriori informazioni su questo formato file[qui](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Il file modello di presentazione (POT) di Microsoft PowerPoint 97-2003 rappresenta i file modello di Microsoft PowerPoint creati dalle versioni di PowerPoint 97-2003. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) sono file con supporto per le macro. I file POTM vengono creati con PowerPoint 2007 o versioni successive e contengono impostazioni predefinite che possono essere utilizzate per creare ulteriori file di presentazione. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Il file POTX (Macro-Free Template) di Microsoft Office Open XML PresentationML rappresenta le presentazioni dei modelli di Microsoft PowerPoint create con Microsoft PowerPoint 2007 e versioni successive. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | I file Microsoft PowerPoint 97-2003 SlideShow (PPS) vengono creati utilizzando Microsoft PowerPoint a scopo di presentazione. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | I file Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM) vengono creati con Microsoft PowerPoint 2007 o versioni successive. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | I file Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX) vengono creati utilizzando Microsoft PowerPoint 2007 e versioni successive a scopo di presentazione. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint Presentation (.ppt) rappresenta un file PowerPoint costituito da una raccolta di diapositive da visualizzare come SlideShow. Specifica il formato di file binario utilizzato da Microsoft PowerPoint 97-2003. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Presentazione Microsoft PowerPoint 95 (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | File PPTM (Microsoft Office Open XML PresentationML) creati con Microsoft PowerPoint 2007 o versioni successive. Sono simili ai file PPTX con la differenza che i laterali non possono eseguire macro sebbene possano contenere macro. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML Presentation (.pptx) è un file di presentazione creato con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato di file di presentazione PPT che era binario, il formato PPTX si basa sul formato di file di presentazione XML aperto di Microsoft PowerPoint. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Restituisce una classe interna, che fornisce possibilità enumerabili su tutti i formati di presentazione esistenti |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Implementa l'interfaccia generica IEnumerable, che abilita una possibilità 'foreach' per il tipo PresentationFormats |

### Guarda anche

* interface [IDocumentFormat](../idocumentformat)
* spazio dei nomi [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
