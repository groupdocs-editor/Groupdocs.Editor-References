---
title: GroupDocs.Editor.Options
second_title: GroupDocs.Editor per Riferimento API .NET
description: Lo spazio dei nomi GroupDocs.Editor.Options fornisce le interfacce per le opzioni di caricamento e salvataggio.
type: docs
weight: 130
url: /it/net/groupdocs.editor.options/
---
Lo spazio dei nomi GroupDocs.Editor.Options fornisce le interfacce per le opzioni di caricamento e salvataggio.

## Classi

| Classe | Descrizione |
| --- | --- |
| [Azw3SaveOptions](./azw3saveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio degli e-book AZW3, noto anche come Formato Kindle 8 (KF8) |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Opzioni per il caricamento di documenti di foglio di calcolo basati su testo (CSV, basati su schede ecc.), che utilizzano un separatore (delimitatore) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Contiene opzioni per la generazione e il salvataggio di documenti di fogli di calcolo basati su testo (CSV, basati su schede ecc.), che utilizzano un separatore (delimitatore) |
| [EbookEditOptions](./ebookeditoptions) | Consente di specificare e regolare le opzioni personalizzate per la modifica di documenti e-book in tutti i formati supportati: ePub, MOBI e AZW3. |
| [EmailEditOptions](./emaileditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti nei diversi formati di posta elettronica (e-mail) |
| [EmailSaveOptions](./emailsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti di posta elettronica (e-mail) |
| [EpubSaveOptions](./epubsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio dei documenti EPUB IDPF (standard aperto per gli e-book creati dall'International Digital Publishing Forum) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Classe astratta di base per le opzioni per tutti i documenti di formati a layout fisso come PDF e XPS |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio dei documenti MHTML (incapsulamento MIME di documenti HTML aggregati) |
| [PdfEditOptions](./pdfeditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti PDF |
| [PdfLoadOptions](./pdfloadoptions) | Contiene opzioni per caricare documenti PDF nella classe Editor |
| [PdfSaveOptions](./pdfsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti PDF (Portable Document Format) |
| [PresentationEditOptions](./presentationeditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti di tutti i formati di presentazione supportati (compatibili con PowerPoint) |
| [PresentationLoadOptions](./presentationloadoptions) | Consente di specificare opzioni personalizzate per il caricamento di documenti di tutti i formati di presentazione supportati come PPT(X), PPTM, PPS(X) ecc. |
| [PresentationSaveOptions](./presentationsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti di presentazione (compatibili con PowerPoint) |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti di tutti i formati di fogli di calcolo supportati (compatibili con Excel) |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Contiene opzioni per il caricamento di documenti binari di fogli di calcolo (Cell, compatibili con Excel) come XLS(X), ODS ecc. nella classe Editor |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti di fogli di calcolo (compatibili con Excel) |
| [TextEditOptions](./texteditoptions) | Consente di specificare opzioni personalizzate per il caricamento di documenti in testo semplice (TXT) |
| [TextSaveOptions](./textsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti in testo normale (TXT) |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti di tutti i formati di WordProcessing supportati (compatibili con Words) come DOC(X), RTF, ODT ecc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Contiene opzioni per il caricamento di documenti WordProcessing (compatibili con Word) come DOC(X), RTF, ODT ecc. nella classe Editor |
| [WordProcessingProtection](./wordprocessingprotection) | Incapsula le opzioni di protezione del documento per il documento WordProcessing, generato da HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti compatibili con WordProcessing dopo che sono stati modificati |
| [WorksheetProtection](./worksheetprotection) | Incapsula le opzioni di protezione del foglio di lavoro, che consentono di proteggere un foglio di lavoro nel documento Foglio di calcolo di output dalla modifica del tipo specificato con una password specificata. |
| [XmlEditOptions](./xmleditoptions) | Consente di specificare opzioni personalizzate per caricare documenti XML (eXtensible Markup Language) e convertirli in HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Contiene opzioni che consentono di personalizzare l'evidenziazione XML durante la conversione da XML a HTML |
| [XpsEditOptions](./xpseditoptions) | Consente di specificare opzioni personalizzate per la modifica dei documenti (XML Paper Specifications) |
| [XpsSaveOptions](./xpssaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti XPS (XML Paper Specifications) |
## Strutture

| Struttura | Descrizione |
| --- | --- |
| [PageRange](./pagerange) | Incapsula un intervallo di pagine, che può avere limiti aperti o chiusi. Per impostazione predefinita è "completamente aperto" - include tutte le pagine esistenti. La numerazione delle pagine inizia da 1, non da 0. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IEditOptions](./ieditoptions) | Interfaccia comune per tutte le opzioni, responsabili delle conversioni da documento a HTML. Dichiara nessun membro. |
| [ILoadOptions](./iloadoptions) | Interfaccia comune per tutte le classi di opzioni, responsabile del caricamento di documenti di diversi formati di tipo |
| [ISaveOptions](./isaveoptions) | Interfaccia per tutte le opzioni di salvataggio per tutti i tipi di documenti. Dichiara nessun membro. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Le opzioni di incorporamento dei caratteri controllano quali risorse dei caratteri devono essere incorporate nel documento WordProcessing o PDF di output |
| [FontExtractionOptions](./fontextractionoptions) | Le opzioni di estrazione dei caratteri controllano quali caratteri devono essere estratti e da dove |
| [MailMessageOutput](./mailmessageoutput) | Controlla quali parti del messaggio di posta devono essere consegnate all'output processing |
| [PdfCompliance](./pdfcompliance) | Specifica il livello di conformità agli standard PDF |
| [TextDirection](./textdirection) | Rappresenta 3 possibili varianti su come trattare la direzione del testo nei documenti di testo semplice |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Contiene le opzioni disponibili per la gestione dello spazio iniziale durante l'apertura del documento di testo normale (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Contiene le opzioni disponibili per la gestione dello spazio finale durante l'apertura del documento di testo normale (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Rappresenta tutti i tipi di protezione disponibili del documento WordProcessing |
| [WorksheetProtectionType](./worksheetprotectiontype) | Rappresenta i tipi di protezione del foglio di lavoro del foglio di calcolo (scheda) |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
