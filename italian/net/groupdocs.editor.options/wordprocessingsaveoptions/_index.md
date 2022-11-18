---
title: WordProcessingSaveOptions
second_title: GroupDocs.Editor per Riferimento API .NET
description: Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti compatibili con WordProcessing dopo che sono stati modificati
type: docs
weight: 1010
url: /it/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti compatibili con WordProcessing dopo che sono stati modificati

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions)(WordProcessingFormats) | Crea una nuova istanza di WordProcessingSaveOptions con il formato di output WordProcessing obbligatorio specificato, mentre tutti gli altri parametri sono default |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Consente di abilitare o disabilitare l'impaginazione che verrà utilizzata per salvare il documento WordProcessing. Se il documento originale è stato aperto e modificato in modalità impaginazione, anche questa opzione dovrebbe essere abilitata. Di default è disabilitato. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Responsabile dell'incorporamento delle risorse dei caratteri nel documento di elaborazione di testi di output. Per impostazione predefinita non incorpora alcun tipo di carattere (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Consente di impostare l'override della locale (lingua) predefinita per il documento WordProcessing, che verrà applicato durante la sua creazione. Quando non è specificato (valore predefinito), MS Word (o altro programma) rileverà (o sceglierà) la locale del documento in base alle proprie impostazioni o ad altri fattori. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Consente di impostare l'override locale (lingua) per il documento WordProcessing per il testo RTL (da destra a sinistra), che verrà applicato durante la sua creazione. Quando non è specificato (valore predefinito), MS Word (o altro programma) rileverà (o sceglierà) il documento RTL locale in base alle proprie impostazioni o ad altri fattori. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Consente di sovrascrivere la locale (lingua) per il documento WordProcessing per il testo dell'Asia orientale, che verrà applicata durante la sua creazione. Quando non è specificato (valore predefinito), MS Word (o altro programma) rileverà (o sceglierà ) il documento East-Asian locale in base alle proprie impostazioni o ad altri fattori. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Abilita i meccanismi di ottimizzazione della memoria durante la generazione di documenti da HTML, che degradano le prestazioni come costo della riduzione dell'utilizzo della memoria. L'impostazione di questa opzione su true può ridurre significativamente il consumo di memoria durante la generazione di documenti di grandi dimensioni al costo di un tempo di salvataggio più lento. L'impostazione predefinita è false (l'ottimizzazione della memoria è disabilitata per migliorare le prestazioni). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Consente di specificare un formato WordProcessing, che verrà utilizzato per salvare il documento |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Consente di specificare, modificare, ottenere o rimuovere una password, che verrà utilizzata per codificare il documento WordProcessing generato. Specificare NULL o una stringa vuota per rimuovere (pulire) la password. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Consente di controllare e applicare le opzioni di protezione del documento per il documento WordProcessing di qualsiasi formato, che supporta la protezione del documento. Per impostazione predefinita è NULL - la protezione del documento non verrà utilizzata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Crea e restituisce una copia completa di questa istanza di WordProcessingSaveOptions class |

### Osservazioni

WordProcessingSaveOptions viene applicato in situazioni in cui è presente un'istanza della classe EditableDocument, che contiene il contenuto di un documento modificato ed è necessario salvare questo contenuto nel nuovo documento del formato WordProcessing.

### Guarda anche

* interface [ISaveOptions](../isaveoptions)
* spazio dei nomi [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
