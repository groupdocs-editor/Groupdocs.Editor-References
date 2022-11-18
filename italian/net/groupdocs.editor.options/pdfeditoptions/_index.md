---
title: PdfEditOptions
second_title: GroupDocs.Editor per Riferimento API .NET
description: Consente di specificare opzioni personalizzate per la modifica di documenti PDF
type: docs
weight: 830
url: /it/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

Consente di specificare opzioni personalizzate per la modifica di documenti PDF

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | Crea e restituisce una nuova istanza della classe PdfEditOptions, in cui tutte le opzioni sono impostate sui valori predefiniti |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | Crea e restituisce una nuova istanza della classe PdfEditOptions con l'impaginazione specificata e tutte le altre opzioni predefinite |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Consente di abilitare (true) o disabilitare (false) l'impaginazione nel documento HTML risultante. Di default è disabilitato (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Consente di impostare un intervallo di pagine da elaborare. Per impostazione predefinita, vengono elaborate tutte le pagine di un documento a layout fisso. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Ottiene o imposta il flag che indica se le immagini devono essere ignorate durante la conversione del documento di input a layout fisso nell'HTML risultante. L'impostazione predefinita è false: le immagini vengono conservate. |

### Guarda anche

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* spazio dei nomi [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->