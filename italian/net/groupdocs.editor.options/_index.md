---
title: "GroupDocs.Editor.Options"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Lo spazio dei nomi GroupDocs.Editor.Options fornisce interfacce per le opzioni di caricamento e salvataggio."
type: docs
weight: 160
url: /it/net/groupdocs.editor.options/
---
Lo spazio dei nomi GroupDocs.Editor.Options fornisce interfacce per le opzioni di caricamento e salvataggio.

## Classi

| Classe | Descrizione |
| --- | --- |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Opzioni per il caricamento di documenti Spreadsheet basati su testo (CSV, basati su tabulazione ecc.), che utilizzano un separatore (delimiter) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Contiene opzioni per la generazione e il salvataggio di documenti Spreadsheet basati su testo (CSV, basati su tabulazione ecc.), che utilizzano un separatore (delimiter) |
| [EbookEditOptions](./ebookeditoptions) | Consente di specificare e regolare opzioni personalizzate per la modifica di documenti E-book in tutti i formati supportati: ePub, MOBI e AZW3. |
| [EbookSaveOptions](./ebooksaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio del documento in tutti i formati e-Book supportabili: ePub, MOBI e AZW3. |
| [EmailEditOptions](./emaileditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti nei diversi formati di posta elettronica (email) |
| [EmailSaveOptions](./emailsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti di posta elettronica (email) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Classe astratta di base per le opzioni di tutti i documenti a layout fisso come PDF e XPS |
| [HtmlSaveOptions](./htmlsaveoptions) | Consente di specificare opzioni personalizzate per il salvataggio dell'istanza [`EditableDocument`](../groupdocs.editor/editabledocument) nel formato HTML |
| [MarkdownEditOptions](./markdowneditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti in formato Markdown (MD) |
| [MarkdownImageLoadArgs](./markdownimageloadargs) | Fornisce dati per l'evento ProcessImage. |
| [MarkdownSaveOptions](./markdownsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti Markdown |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio dei documenti MHTML (MIME encapsulation of aggregate HTML documents) |
| [PdfEditOptions](./pdfeditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti PDF |
| [PdfLoadOptions](./pdfloadoptions) | Contiene opzioni per il caricamento di documenti PDF nella classe Editor |
| [PdfSaveOptions](./pdfsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti PDF (Portable Document Format) |
| [PresentationEditOptions](./presentationeditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti di tutti i formati Presentation (compatibili con PowerPoint) supportabili |
| [PresentationLoadOptions](./presentationloadoptions) | Consente di specificare opzioni personalizzate per il caricamento di documenti di tutti i formati Presentation supportabili, come PPT(X), PPTM, PPS(X) ecc. |
| [PresentationSaveOptions](./presentationsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti Presentation (compatibili con PowerPoint) |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti di tutti i formati Spreadsheet (compatibili con Excel) supportabili |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Contiene opzioni per il caricamento di documenti Spreadsheet binari (Cells, compatibili con Excel) come XLS(X), ODS ecc. nella classe Editor |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti Spreadsheet (conforme a Excel) |
| [TextEditOptions](./texteditoptions) | Consente di specificare opzioni personalizzate per il caricamento di documenti di testo semplice (TXT) |
| [TextSaveOptions](./textsaveoptions) | Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti di testo semplice (TXT) |
| [WebFont](./webfont) | Rappresenta le impostazioni dei caratteri per il web |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Consente di specificare opzioni personalizzate per la modifica di documenti di tutti i formati WordProcessing (compatibili con Words) supportati, come DOC(X), RTF, ODT ecc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Contiene opzioni per caricare documenti WordProcessing (compatibili con Word) come DOC(X), RTF, ODT ecc. nella classe Editor |
| [WordProcessingProtection](./wordprocessingprotection) | Incapsula le opzioni di protezione del documento WordProcessing, generato da HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Consente di specificare opzioni personalizzate per generare e salvare documenti conformi a WordProcessing dopo che sono stati modificati |
| [WorksheetProtection](./worksheetprotection) | Incapsula le opzioni di protezione del foglio di lavoro, che consentono di proteggere un foglio di lavoro nel documento Spreadsheet di output da modifiche di tipo specificato con una password specificata. |
| [XmlEditOptions](./xmleditoptions) | Consente di specificare opzioni personalizzate per modificare documenti XML (eXtensible Markup Language) e convertirli in HTML |
| [XmlFormatOptions](./xmlformatoptions) | Contiene opzioni che consentono di regolare la formattazione del documento XML quando è rappresentato come HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Contiene opzioni che consentono di personalizzare l'evidenziazione XML durante la conversione da XML a HTML |
| [XpsSaveOptions](./xpssaveoptions) | Consente di specificare opzioni personalizzate per generare e salvare documenti XPS (XML Paper Specifications) |
## Structures

| Struttura | Descrizione |
| --- | --- |
| [PageRange](./pagerange) | Incapsula un intervallo di pagine, che può avere limiti aperti o chiusi. Per impostazione predefinita è "completamente aperto" - include tutte le pagine esistenti. La numerazione delle pagine inizia da 1, non da 0. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IEditOptions](./ieditoptions) | Interfaccia comune per tutte le opzioni responsabili delle conversioni da documento a HTML. Non dichiara membri. |
| [IHtmlSavingCallback](./ihtmlsavingcallback) | Interfaccia utilizzata durante il salvataggio al formato HTML e che deve essere implementata dall'utente finale per salvare la risorsa fornita e restituire un collegamento ad essa |
| [ILoadOptions](./iloadoptions) | Interfaccia comune per tutte le classi di opzioni, responsabile del caricamento di documenti di diversi formati di tipo |
| [IMarkdownImageLoadCallback](./imarkdownimageloadcallback) | Implementa questa interfaccia se desideri controllare come GroupDocs.Editor carica le immagini durante il caricamento del file in formato Markdown |
| [ISaveOptions](./isaveoptions) | Interfaccia per tutte le opzioni di salvataggio per tutti i tipi di documenti. Non dichiara membri. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Le opzioni di incorporamento dei caratteri controllano quali risorse di carattere devono essere incorporate nel documento WordProcessing o PDF di output |
| [FontExtractionOptions](./fontextractionoptions) | Le opzioni di estrazione dei caratteri controllano quali caratteri devono essere estratti e da dove |
| [MailMessageOutput](./mailmessageoutput) | Controlla quali parti del messaggio di posta devono essere consegnate al processo di output |
| [MarkdownImageLoadingAction](./markdownimageloadingaction) | Definisce la modalità di caricamento delle immagini durante l'apertura per la modifica del file in formato Markdown |
| [MarkdownTableContentAlignment](./markdowntablecontentalignment) | Consente di specificare l'allineamento del contenuto della tabella da utilizzare durante l'esportazione in formato Markdown |
| [PdfCompliance](./pdfcompliance) | Specifica il livello di conformità agli standard PDF |
| [TextDirection](./textdirection) | Rappresenta 3 possibili varianti su come trattare la direzione del testo nei documenti di testo semplice |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Contiene le opzioni disponibili per la gestione degli spazi iniziali durante l'apertura di un documento di testo semplice (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Contiene le opzioni disponibili per la gestione degli spazi finali durante l'apertura di un documento di testo semplice (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Rappresenta tutti i tipi di protezione disponibili del documento WordProcessing |
| [WorksheetProtectionType](./worksheetprotectiontype) | Rappresenta i tipi di protezione del foglio di calcolo (scheda) |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
