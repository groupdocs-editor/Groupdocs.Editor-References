---
title: "EditableDocument"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Documento intermedio che contiene il contenuto prima e dopo la modifica"
type: docs
weight: 10
url: /it/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Documento intermedio, che contiene il contenuto prima e dopo la modifica

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Restituisce un elenco di tutte le risorse esistenti: tutti i fogli di stile, le immagini dall'HTML e tutti i fogli di stile, i font, l'audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Restituisce un elenco di risorse audio |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Consente di ottenere le risorse dei fogli di stile (CSS) (sia esterne che incorporate, ma non inline), che sono utilizzate da questo documento HTML |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Consente di ottenere le risorse dei font esterni, che sono utilizzate da questo documento HTML |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Consente di ottenere le risorse delle immagini esterne (immagini raster e vettoriali), che sono utilizzate da questo documento HTML |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Determina se questo documento Editable è già stato eliminato (true) o no (false) |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Factory statica, che crea un'istanza di EditableDocument da un file HTML, specificato da un percorso al file *.html stesso e da una cartella con le risorse collegate |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Factory statica, che crea un'istanza di [`EditableDocument`](../editabledocument) dal markup HTML specificato |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Factory statica, che crea un'istanza di EditableDocument dal markup HTML specificato e da un insieme di risorse collegate corrispondenti |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Factory statica, che crea un'istanza di EditableDocument da un markup HTML specificato e da risorse, situate nella cartella indicata dal percorso completo |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Elimina questa istanza di documento Editable, eliminando il suo contenuto e rendendo i suoi metodi e proprietà non funzionanti |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Restituisce il corpo del documento HTML (contenuto interno tra i tag BODY di apertura e chiusura senza questi tag) come stringa. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Restituisce il corpo del documento HTML (contenuto interno tra i tag BODY di apertura e chiusura senza questi tag) come stringa, dove i collegamenti alle risorse esterne contengono il modello specificato con segnaposti. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Restituisce il contenuto complessivo del documento HTML come stringa. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Restituisce il contenuto complessivo del documento HTML come stringa, dove i collegamenti alle risorse esterne contengono il modello specificato con segnaposti. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Restituisce il contenuto complessivo del documento HTML come flusso di byte scrivendo questo contenuto nello stream specificato con la codifica di testo specificata |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Restituisce il contenuto di tutti i fogli di stile esterni come un elenco di stringhe, dove ogni stringa rappresenta un foglio di stile. Restituisce un elenco vuoto, se non vi è CSS per questo documento. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Restituisce il contenuto di tutti i fogli di stile esterni come un elenco di stringhe, dove ogni stringa rappresenta un foglio di stile. Il prefisso specificato sarà applicato a ogni collegamento alla risorsa esterna in ciascun foglio di stile risultante. Restituisce un elenco vuoto, se non vi è CSS per questo documento. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Restituisce tutto il contenuto di questo documento HTML con tutte le risorse correlate sotto forma di una singola stringa, dove tutte le risorse sono incorporate nel markup HTML in forma codificata base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | Salva questo documento HTML nel file al percorso specificato, dove verrà memorizzato il markup HTML, e nella cartella allegata con le risorse. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | Salva questo documento HTML nel file al percorso specificato, dove verrà memorizzato il markup HTML, e nella cartella allegata con le risorse, situata al percorso specificato. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Salva il contenuto di questo [`EditableDocument`](../editabledocument) come documento HTML nello scrittore di testo specificato, mentre il secondo parametro delle opzioni consente di personalizzare la procedura di salvataggio e specificare la callback di salvataggio delle risorse |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Evento, che si verifica quando questo documento Editable viene eliminato, subito dopo aver completato il processo di eliminazione. |

### Osservazioni

Un'istanza della classe `EditableDocument` può essere prodotta dal metodo '[`Edit`](../editor/edit)' o creata dall'utente stesso usando factory statiche. `EditableDocument` memorizza internamente il documento in un proprio formato chiuso, compatibile (convertibile) con tutti i formati di importazione ed esportazione supportati da GroupDocs.Editor. Per rendere il documento modificabile in qualsiasi editor client-side WYSIWYG (come CKEditor o TinyMCE), `EditableDocument` fornisce metodi per generare markup HTML e produrre risorse, che possono essere accettate dall'utente.

### Vedi anche

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
