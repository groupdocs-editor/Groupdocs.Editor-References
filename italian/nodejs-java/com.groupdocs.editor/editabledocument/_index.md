---
title: "EditableDocument"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Documento intermedio che contiene il contenuto prima e dopo la modifica"
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Documento intermedio, che contiene contenuti prima e dopo la modifica


*** ** * ** ***

Un'istanza della classe EditableDocument può essere prodotta dal metodo Editor.edit() o creata dall'utente stesso utilizzando factory statiche. EditableDocument memorizza internamente il documento in un proprio formato chiuso, compatibile (convertibile) con tutti i formati di importazione ed esportazione supportati da GroupDocs.Editor. Per rendere il documento modificabile in qualsiasi editor WYSIWYG lato client (come CKEditor o TinyMCE), EditableDocument fornisce metodi per generare markup HTML e produrre risorse che possono essere accettate dall'utente.

<br />


## Campi

| Campo | Descrizione |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getImages()](#getImages--) | Consente di ottenere risorse immagine esterne (immagini raster), che sono utilizzate |
da questo documento HTML
|
|  | [getFonts()](#getFonts--) | Consente di ottenere risorse font esterne, che sono utilizzate da questo HTML |
documento
|
|  | [getCss()](#getCss--) | Restituisce un elenco di risorse CSS |
|
|  | [getAudio()](#getAudio--) | Restituisce un elenco di risorse audio |
|
|  | [getAllResources()](#getAllResources--) | Restituisce un elenco di tutte le risorse esistenti: tutti i fogli di stile, le immagini da |
HTML e tutti i fogli di stile, i font
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Restituisce il contenuto complessivo del documento HTML come flusso di byte scrivendo questo contenuto nello stream specificato con la codifica di testo specificata |
|
|  | [getBodyContent()](#getBodyContent--) | Restituisce il corpo del documento HTML (contenuto tra l'apertura e la chiusura |
TAG BODY senza questi tag) come stringa.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Restituisce il corpo del documento HTML (contenuto tra l'apertura e la chiusura |
TAG BODY senza questi tag) come stringa, dove i collegamenti alle risorse esterne
contengono il prefisso specificato.
|
|  | [getContent()](#getContent--) | Restituisce il contenuto complessivo del documento HTML come stringa. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Restituisce il contenuto complessivo del documento HTML come stringa, dove i collegamenti a |
le risorse esterne contengono il prefisso specificato.
|
|  | [getCssContent()](#getCssContent--) | Restituisce il contenuto di tutti i fogli di stile esterni come un elenco di stringhe, dove |
una stringa rappresenta un foglio di stile.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Restituisce il contenuto di tutti i fogli di stile esterni come un elenco di stringhe, dove |
una stringa rappresenta un foglio di stile.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Restituisce tutto il contenuto di questo documento HTML con tutte le risorse correlate in un |
formato di una singola stringa, dove tutte le risorse sono incorporate all'interno dell'HTML
markup in forma codificata base64.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Salva questo documento HTML nel file sul percorso specificato, dove il markup HTML |
verrà memorizzato, e nella cartella allegata con le risorse.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Salva questo documento HTML nel file sul percorso specificato, dove il markup HTML |
verrà memorizzato, e nella cartella allegata con le risorse, che è
situata sul percorso specificato.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Factory statica, che crea un'istanza di EditableDocument da |
markup HTML specificato e un insieme di risorse collegate corrispondenti
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Factory statica, che crea un'istanza di EditableDocument da un markup HTML specificato e da risorse, situate nella cartella, specificata dal percorso completo |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Factory statica, che crea un'istanza di EditableDocument da un HTML |
file, che è specificato da un percorso al file \*.html stesso e a una cartella
con risorse collegate
|
|  | [dispose()](#dispose--) | Rilascia questa istanza di documento Editable, rilasciando il suo contenuto e |
rendendo i suoi metodi e proprietà non funzionanti
|
|  | [isDisposed()](#isDisposed--) | Determina se questo documento Editable è già stato rilasciato (true) o |
no (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Consente di ottenere risorse immagine esterne (immagini raster), che sono utilizzate
da questo documento HTML


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Consente di ottenere risorse font esterne, che sono utilizzate da questo HTML
documento


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Restituisce un elenco di risorse CSS


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Restituisce un elenco di risorse audio


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Restituisce un elenco di tutte le risorse esistenti: tutti i fogli di stile, le immagini da
HTML e tutti i fogli di stile, i font


*** ** * ** ***

Questa proprietà restituisce un risultato concatenato delle proprietà 'Images', 'Fonts' e 'Css'

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Restituisce il contenuto complessivo del documento HTML come flusso di byte scrivendo questo contenuto nello stream specificato con la codifica di testo specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | archiviazione | java.io.OutputStream | Flusso di byte non nullo, che supporta la scrittura |
|
|  | codifica | java.nio.charset.Charset | Codifica di testo non nulla, che dovrebbe essere applicata durante la scrittura del contenuto testuale nello storage specificato |


TStream
: Qualsiasi implementazione di java.io.InputStream
|

**Returns:**
java.io.OutputStream - Istanza dello storage specificato

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Restituisce il corpo del documento HTML (contenuto tra l'apertura e la chiusura
TAG BODY senza questi tag) come stringa.


**Returns:**
java.lang.String - Stringa, che contiene il corpo del documento HTML


*** ** * ** ***

Gli editor WYSIWYG operano sul corpo del documento e non possono elaborare correttamente le sue informazioni meta dal blocco HEAD. Questo metodo è progettato per tali casi. Questa sovraccarico non consente di regolare gli URI per le richieste di risorse esterne.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Restituisce il corpo del documento HTML (contenuto tra l'apertura e la chiusura
TAG BODY senza questi tag) come stringa, dove i collegamenti alle risorse esterne
contengono il prefisso specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Attraverso questo parametro è possibile specificare un prefisso, che verrà aggiunto ai collegamenti a tutte le immagini esterne negli elementi IMG, presenti nella stringa HTML risultante. Se NULL o vuoto, i prefissi non verranno aggiunti. |


*** ** * ** ***

Gli editor WYSIWYG operano sul corpo del documento e non possono elaborare correttamente le sue informazioni meta dal blocco HEAD. Questo metodo è progettato per tali casi. Questa sovraccarico consente di regolare gli URI per le richieste di risorse esterne.

<br />

|

**Returns:**
java.lang.String - Stringa, che contiene il corpo del documento HTML con i collegamenti, adeguati alle immagini esterne

### getContent() {#getContent--}
```
public String getContent()
```


Restituisce il contenuto complessivo del documento HTML come stringa.


**Returns:**
java.lang.String - Stringa, che contiene il contenuto del documento HTML

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Restituisce il contenuto complessivo del documento HTML come stringa, dove i collegamenti a
le risorse esterne contengono il prefisso specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Attraverso questo parametro è possibile specificare un prefisso, che verrà aggiunto ai collegamenti a tutte le immagini esterne negli elementi IMG, presenti nella stringa HTML risultante. Se NULL o vuoto, i prefissi non verranno aggiunti. |
|
|  | externalCssTemplate | java.lang.String | Attraverso questo parametro è possibile specificare un prefisso, che verrà aggiunto ai collegamenti a tutti i fogli di stile esterni negli elementi LINK, presenti nella stringa HTML risultante. Se NULL o vuoto, i prefissi non verranno aggiunti. |
|

**Returns:**
java.lang.String - Stringa, che contiene il contenuto del documento HTML con i collegamenti, adeguati alle risorse esterne

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Restituisce il contenuto di tutti i fogli di stile esterni come un elenco di stringhe, dove
una stringa rappresenta un foglio di stile. Restituisce una lista vuota, se non c'è
CSS per questo documento.


**Returns:**
java.util.List<java.lang.String> - Una lista di stringhe, dove ogni stringa contiene il contenuto di un documento CSS

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Restituisce il contenuto di tutti i fogli di stile esterni come un elenco di stringhe, dove
una stringa rappresenta un foglio di stile. Il prefisso specificato verrà applicato a
ogni collegamento alla risorsa esterna in ogni foglio di stile risultante.
Restituisce una lista vuota, se non c'è CSS per questo documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | Attraverso questo parametro è possibile specificare un prefisso, che verrà aggiunto ai collegamenti a tutte le immagini esterne, presenti nelle dichiarazioni CSS nelle stringhe CSS risultanti. Se NULL o vuoto, i prefissi non verranno aggiunti. |
|
|  | externalFontsPrefix | java.lang.String | Attraverso questo parametro è possibile specificare un prefisso, che verrà aggiunto ai collegamenti a tutti i font esterni nel |
|

**Returns:**
java.util.List<java.lang.String> - Una lista di stringhe, dove ogni stringa contiene il contenuto di un documento CSS

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Restituisce tutto il contenuto di questo documento HTML con tutte le risorse correlate in un
formato di una singola stringa, dove tutte le risorse sono incorporate all'interno dell'HTML
markup in forma codificata base64.


**Returns:**
java.lang.String - String, che non è NULL o vuoto in nessun caso

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Salva questo documento HTML nel file sul percorso specificato, dove il markup HTML
verrà memorizzato, e nella cartella allegata con le risorse.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Percorso completo al file, dove verrà memorizzato il markup HTML. Il file sarà creato o sovrascritto, se esiste. La cartella delle risorse allegata sarà creata nella stessa cartella in cui esiste il file HTML. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Salva questo documento HTML nel file sul percorso specificato, dove il markup HTML
verrà memorizzato, e nella cartella allegata con le risorse, che è
situata sul percorso specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Percorso completo al file, dove verrà memorizzato il markup HTML. Non può essere NULL o vuoto. Il file sarà creato o sovrascritto, se esiste. |
|
|  | resourcesFolderPath | java.lang.String | Percorso completo alla cartella allegata, dove saranno archiviate tutte le risorse correlate. Se NULL o vuoto, la cartella sarà creata automaticamente nella stessa directory in cui si trova il file \*.html. Se specificata e non esiste, verrà creata. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Factory statica, che crea un'istanza di EditableDocument da
markup HTML specificato e un insieme di risorse collegate corrispondenti


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, che contiene markup HTML grezzo, che deve essere analizzato. Non può essere NULL, vuoto o non valido. |
|
|  | resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Raccolta di tutte le risorse (immagini, fogli di stile, font) utilizzate nel documento HTML, specificata nel parametro  newHtmlContent . Può essere assente (NULL o raccolta vuota). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Factory statica, che crea un'istanza di EditableDocument da un markup HTML specificato e da risorse, situate nella cartella, specificata dal percorso completo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, che contiene markup HTML grezzo, che deve essere analizzato. Non può essere NULL, vuoto o non valido. |
|
|  | resourceFolderPath | java.lang.String | Percorso obbligatorio alla cartella con le risorse. Tutti i fogli di stile presenti in questa cartella saranno utilizzati. Non può essere NULL o una stringa vuota, e questa cartella deve esistere. |

<br />

*** ** * ** ***

Questa factory statica è utile quando il contenuto del documento HTML è presentato come stringa, ma tutte le risorse si trovano in una cartella e spesso i collegamenti a queste risorse nel markup HTML sono non validi o assenti. Quando si invoca questo metodo, esso analizza la cartella specificata e applica automaticamente tutti i fogli di stile trovati al documento. Questo metodo è molto utile quando si ottiene il contenuto da diversi editor HTML, i quali solitamente rimuovono i metadati del documento e così via.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Factory statica, che crea un'istanza di EditableDocument da un HTML
file, che è specificato da un percorso al file \*.html stesso e a una cartella
con risorse collegate


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String, che contiene un percorso completo al file HTML. Non può essere null, deve essere un percorso file valido, e il file stesso deve esistere. |
|
|  | resourceFolderPath | java.lang.String | Percorso opzionale alla cartella con le risorse HTML. Se NULL, non valido o se tale cartella non esiste, l'Editor cercherà di trovare questa cartella da solo, analizzando il markup HTML. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia questa istanza di documento Editable, rilasciando il suo contenuto e
rendendo i suoi metodi e proprietà non funzionanti


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determina se questo documento Editable è già stato rilasciato (true) o
no (false)


**Returns:**
boolean
