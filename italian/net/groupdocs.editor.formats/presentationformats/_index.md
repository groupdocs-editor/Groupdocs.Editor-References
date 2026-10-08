---
title: "PresentationFormats"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Incapsula tutti i formati Presentation. Include i seguenti formati"
type: docs
weight: 120
url: /it/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

Raccoglie tutti i formati di Presentazione. Include i seguenti formati:

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

Scopri di più sui formati Presentation [qui](https://wiki.fileformat.com/presentation).

```csharp
public class PresentationFormats : DocumentFormatBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ottiene l'estensione del file del formato di documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ottiene la famiglia di formato a cui appartiene il formato di documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ottiene l'identificatore univoco per la famiglia di formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ottiene il tipo MIME del formato di documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ottiene il nome della famiglia di formato. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | Ottiene una collezione enumerabile di tutti i [`PresentationFormats`](../presentationformats). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Recupera un'istanza del tipo specificato [`PresentationFormats`](../presentationformats) che ha l'estensione di file specificata. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina se questa istanza è uguale all'istanza specificata [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina se questa istanza è uguale all'istanza specificata [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina se questa istanza è uguale all'istanza specificata [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Restituisce un codice hash per l'oggetto corrente. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | Converte una stringa che rappresenta un'estensione di file in un oggetto [`PresentationFormats`](../presentationformats). |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation template (OTP). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Presentation Template (POT). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow (PPS). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 Presentation (PPT). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Presentazione Microsoft PowerPoint 95 (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Documento Microsoft Office Open XML PresentationML con macro abilitata (PPTM). Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Documento Microsoft Office Open XML PresentationML senza macro (PPTX). Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/pptx). |

### Vedi anche

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
