---
title: "WordProcessingSaveOptions"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti compatibili con WordProcessing dopo che sono stati modificati"
type: docs
weight: 1240
url: /it/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Consente di specificare opzioni personalizzate per generare e salvare documenti conformi a WordProcessing dopo che sono stati modificati

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Questo costruttore senza parametri crea una nuova istanza di WordProcessingSaveOptions con formato di output DOCX (può essere modificato successivamente tramite la proprietà [`OutputFormat`](./outputformat)) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Crea una nuova istanza di WordProcessingSaveOptions con il formato di output WordProcessing obbligatorio specificato, mentre tutti gli altri parametri sono predefiniti |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Consente di abilitare o disabilitare l'impaginazione che verrà utilizzata per il salvataggio del documento WordProcessing. Se il documento originale è stato aperto e modificato in modalità impaginazione, questa opzione dovrebbe essere anch'essa abilitata. Per impostazione predefinita è disabilitata. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Responsabile dell'incorporamento delle risorse di carattere nel documento WordProcessing di output. Per impostazione predefinita non incorpora alcun carattere (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Consente di impostare la sovrascrittura della locale predefinita (lingua) per il documento WordProcessing, che verrà applicata durante la sua creazione. Quando non è specificata (valore predefinito), MS Word (o altro programma) rileverà (o sceglierà) la locale del documento in base alle proprie impostazioni o ad altri fattori. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Consente di impostare la sovrascrittura della locale (lingua) per il documento WordProcessing per il testo RTL (da destra a sinistra), che verrà applicata durante la sua creazione. Quando non è specificata (valore predefinito), MS Word (o altro programma) rileverà (o sceglierà) la locale RTL del documento in base alle proprie impostazioni o ad altri fattori. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Consente di sovrascrivere la locale (lingua) per il documento WordProcessing per il testo dell'Est asiatico, che verrà applicata durante la sua creazione. Quando non è specificata (valore predefinito), MS Word (o altro programma) rileverà (o sceglierà) la locale dell'Est asiatico del documento in base alle proprie impostazioni o ad altri fattori. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Abilita i meccanismi di ottimizzazione della memoria durante la generazione di documenti da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria. Impostare questa opzione su true può ridurre significativamente il consumo di memoria durante la generazione di documenti di grandi dimensioni, a scapito di un tempo di salvataggio più lento. Il valore predefinito è false (l'ottimizzazione della memoria è disabilitata per garantire migliori prestazioni). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Consente di specificare un formato WordProcessing, che verrà utilizzato per il salvataggio del documento |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Consente di specificare, modificare, ottenere o rimuovere una password, che verrà utilizzata per codificare il documento WordProcessing generato. Specificare NULL o una stringa vuota per rimuovere (pulire) la password. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Consente di controllare e applicare le opzioni di protezione del documento per il documento WordProcessing di qualsiasi formato, che supporta la protezione del documento. Per impostazione predefinita è NULL - la protezione del documento non verrà utilizzata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Crea e restituisce una copia completa di questa istanza della classe WordProcessingSaveOptions |

### Osservazioni

WordProcessingSaveOptions viene applicato in situazioni in cui esiste un'istanza della classe EditableDocument, che contiene il contenuto di un documento modificato, ed è necessario salvare questo contenuto in un nuovo documento in formato WordProcessing.

### Vedi anche

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
