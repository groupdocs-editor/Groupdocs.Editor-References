---
title: EditableDocument
second_title: GroupDocs.Editor per Riferimento API .NET
description: Documento intermedio che contiene contenuti prima e dopo la modifica
type: docs
weight: 10
url: /it/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Documento intermedio, che contiene contenuti prima e dopo la modifica

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Restituisce un elenco di tutte le risorse esistenti: tutti i fogli di stile, le immagini da HTML e tutti i fogli di stile, i caratteri, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Restituisce un elenco di risorse audio |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Restituisce un elenco di risorse CSS |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Consente di ottenere risorse di font esterne, utilizzate da questo documento HTML |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Consente di ottenere risorse immagine esterne (immagini raster e vettoriali), utilizzate da questo documento HTML |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Determina se questo documento modificabile è già stato eliminato (vero) o meno (falso) |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Factory statica, che crea un'istanza di EditableDocument da un file HTML, specificato da un percorso al file *.html stesso e una cartella con risorse collegate |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Factory statica, che crea un'istanza di EditableDocument dal markup HTML specificato e un set di risorse collegate corrispondenti |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Factory statica, che crea un'istanza di EditableDocument da un markup HTML specificato e da risorse, situate nella cartella, specificata dal percorso completo |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Elimina questa istanza di documento modificabile, eliminandone il contenuto e rendendo i suoi metodi e proprietà non funzionanti |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Restituisce un corpo del documento HTML (contenuto interno tra tag BODY di apertura e chiusura senza questi tag) come stringa. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Restituisce un corpo del documento HTML (contenuto interno tra i tag BODY di apertura e chiusura senza questi tag) come stringa, dove i collegamenti alle risorse esterne contengono il prefisso specificato. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Restituisce il contenuto complessivo del documento HTML come stringa. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Restituisce il contenuto complessivo del documento HTML come stringa, dove i collegamenti alle risorse esterne contengono il prefisso specificato. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Restituisce il contenuto di tutti i fogli di stile esterni come un elenco di stringhe, dove una stringa rappresenta un foglio di stile. Restituisce un elenco vuoto, se non sono presenti CSS per questo documento. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Restituisce il contenuto di tutti i fogli di stile esterni come un elenco di stringhe, dove una stringa rappresenta un foglio di stile. Il prefisso specificato verrà applicato a ogni collegamento alla risorsa esterna in ogni foglio di stile risultante. Restituisce un elenco vuoto, se non esiste un CSS per questo documento. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Restituisce tutto il contenuto di questo documento HTML con tutte le risorse correlate sotto forma di una singola stringa, dove tutte le risorse sono incorporate all'interno del markup HTML in un formato con codifica base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Salva questo documento HTML nel file nel percorso specificato, dove verrà memorizzato il markup HTML, e nella cartella di accompagnamento con le risorse. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Salva questo documento HTML nel file nel percorso specificato, dove verrà archiviato il markup HTML, e nella cartella con le risorse di accompagnamento, che si trova nel percorso specificato. |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Evento che si verifica quando questo documento modificabile viene eliminato, subito dopo aver terminato il processo di eliminazione |

### Osservazioni

L'istanza della classe EditableDocument può essere prodotta dal '[`Edit`](../editor/edit) metodo o creato dall'utente stesso utilizzando factory statiche. EditableDocument memorizza internamente il documento nel proprio formato chiuso, che è compatibile (convertibile) con tutti i formati di importazione ed esportazione, supportati da GroupDocs.Editor. Per rendere il documento modificabile in qualsiasi editor lato client WYSIWYG (come CKEditor o TinyMCE), EditableDocument fornisce metodi per generare markup HTML e produrre risorse, che possono essere accettate dall'utente.

### Guarda anche

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* spazio dei nomi [GroupDocs.Editor](../../groupdocs.editor)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
