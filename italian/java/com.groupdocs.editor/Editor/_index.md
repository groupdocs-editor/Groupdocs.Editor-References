---
title: "Editor"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Classe principale che incapsula i metodi di conversione."
type: docs
weight: 11
url: /it/java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Classe principale, che incapsula i metodi di conversione.
La classe Editor fornisce metodi per caricare, modificare e salvare documenti di tutti i formati supportati. È eliminabile, quindi usa una direttiva 'using' o rilascia manualmente le sue risorse tramite la chiamata al metodo 'Dispose()'. Il caricamento dei documenti avviene tramite i costruttori. Modifica del documento - tramite il metodo 'Edit', e salvataggio del documento risultante dopo la modifica - tramite il metodo 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Inizializza una nuova istanza della classe [Editor](../../com.groupdocs.editor/editor) e crea un nuovo documento vuoto basato sul formato specificato. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Inizializza una nuova istanza di Editor con il documento di input specificato (come stream) |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Inizializza una nuova istanza di Editor con il documento di input specificato (come un |
stream) con le sue opzioni di caricamento e le impostazioni di Editor
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Inizializza una nuova istanza di Editor con il documento di input specificato (come percorso completo del file) |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Inizializza una nuova istanza di Editor con il documento di input specificato (come percorso completo del file) con le sue opzioni di caricamento |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Apre un documento precedentemente caricato per la modifica utilizzando le opzioni specifiche del formato, generando e restituendo un'istanza della classe '' che, a sua volta, contiene metodi per produrre markup HTML e risorse associate. |
|
|  | [edit()](#edit--) | Apre un documento precedentemente caricato per la modifica utilizzando le opzioni predefinite per |
generare e restituire un'istanza della classe 'EditableDocument', che,
a sua volta, contiene metodi per produrre markup HTML e
risorse.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Converte il documento modificato specificato, rappresentato come istanza di |
'EditableDocument', nel documento risultante del formato specificato e
ne salva il contenuto nello stream specificato
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Converte il documento modificato specificato, rappresentato come istanza di '', nel documento risultante del formato specificato e ne salva il contenuto in un file tramite il percorso file specificato |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Converte il documento modificato specificato (rappresentato da un [EditableDocument](../../com.groupdocs.editor/editabledocument)) in un documento di output il cui formato è determinato dall'estensione del nome file, e lo salva nel percorso file specificato. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Converte il documento originale dopo la modifica (ad esempio, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
nel documento risultante del formato specificato e ne salva il contenuto nello stream fornito.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Salva il contenuto del documento corrente nello stream di output specificato. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Restituisce i metadati del documento che è stato caricato in questa istanza di 'Editor' |
|
|  | [dispose()](#dispose--) | Dispone di questa istanza di Editor, in modo che rilasci tutte le risorse interne |
risorse e diventa non disponibile per ulteriori utilizzi
|
|  | [isDisposed()](#isDisposed--) | Indica se questa istanza di Editor è già stata eliminata e non può essere |
utilizzata ulteriormente (true) o meno ed è attiva (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Inizializza una nuova istanza della classe [Editor](../../com.groupdocs.editor/editor) e crea un nuovo documento vuoto basato sul formato specificato.

<br />

*** ** * ** ***

> ```
>   IDocumentFormat format = WordProcessingFormats.Docx;
>  Editor editor = new Editor(format);
>  {
>      // Use the editor instance to edit and save documents
>  }
>  
>  
> ```

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | rappresenta il formato file del documento che sarà creato. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Inizializza una nuova istanza di Editor con il documento di input specificato (come stream)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Delegate, che dovrebbe restituire uno stream con il contenuto del documento. Non dovrebbe essere NULL. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Inizializza una nuova istanza di Editor con il documento di input specificato (come un
stream) con le sue opzioni di caricamento e le impostazioni di Editor


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Delegate, che dovrebbe restituire uno stream con il contenuto del documento. Non dovrebbe essere NULL. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, che dovrebbe restituire le opzioni di caricamento del documento. Può essere NULL e può restituire null - in tal caso il tipo di documento verrà rilevato automaticamente e verranno applicate le opzioni di caricamento predefinite per quel tipo. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Inizializza una nuova istanza di Editor con il documento di input specificato (come percorso completo del file)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso completo del file. Non dovrebbe essere NULL. Deve essere valido e il file deve esistere. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Inizializza una nuova istanza di Editor con il documento di input specificato (come percorso completo del file) con le sue opzioni di caricamento


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso completo del file. Non dovrebbe essere NULL. Deve essere valido e il file deve esistere. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, che dovrebbe restituire le opzioni di caricamento del documento. Può essere NULL e può restituire null - in tal caso il tipo di documento verrà rilevato automaticamente e verranno applicate le opzioni di caricamento predefinite per quel tipo. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Apre un documento precedentemente caricato per la modifica utilizzando le opzioni specifiche del formato, generando e restituendo un'istanza della classe '' che, a sua volta, contiene metodi per produrre markup HTML e risorse associate.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Opzioni del documento specifiche del formato, che consentono di ottimizzare il processo di conversione. Non dovrebbe essere NULL. Non dovrebbe confliggere con le opzioni di caricamento precedentemente applicate. |


*** ** * ** ***

Quando il documento originale di input viene caricato nell'istanza 'Editor' tramite il costruttore, questo metodo consente di aprire il documento per la modifica convertendolo in un formato intermedio, che è incapsulato all'interno di un'istanza della classe 'EditableDocument'. 'EditableDocument', restituito da questo metodo, contiene tutti i metodi e le proprietà necessari per produrre markup HTML e le risorse corrispondenti (come immagini, font e fogli di stile) in tutte le configurazioni necessarie per il successivo passaggio a qualsiasi editor HTML WYSIWYG. Questa sovraccarico ottiene le opzioni di modifica, che sono specifiche per le famiglie di formati.

*** ** * ** ***


**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Edit+document)
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument)
### edit() {#edit--}
```
public final EditableDocument edit()
```


Apre un documento precedentemente caricato per la modifica utilizzando le opzioni predefinite per
generare e restituire un'istanza della classe 'EditableDocument', che,
a sua volta, contiene metodi per produrre markup HTML e
risorse.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Quando il documento originale di input viene caricato nell'istanza 'Editor' tramite il costruttore, questo metodo consente di aprire il documento per la modifica convertendolo in un formato intermedio, che è incapsulato all'interno di un'istanza della classe 'EditableDocument'. 'EditableDocument', restituito da questo metodo, contiene tutti i metodi e le proprietà necessari per produrre markup HTML e le risorse corrispondenti (come immagini, font e fogli di stile) in tutte le configurazioni necessarie per il successivo passaggio a qualsiasi editor HTML WYSIWYG. Questa sovraccarico applica le opzioni di modifica, che sono quelle predefinite per il formato a cui appartiene il documento di input.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Converte il documento modificato specificato, rappresentato come istanza di
'EditableDocument', nel documento risultante del formato specificato e
ne salva il contenuto nello stream specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versione del documento di input, che è stato modificato in un editor HTML WYSIWYG e memorizzato come istanza della classe 'EditableDocument', che dovrebbe essere convertita in un documento di output di un formato specifico. |
|
|  | outputDocument | java.io.OutputStream | Stream di output, in cui verrà registrato il contenuto del documento risultante. Non dovrebbe essere NULL, smaltito, dovrebbe supportare la scrittura. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Opzioni di salvataggio del documento, che definiscono il formato del documento risultante, nonché le opzioni di salvataggio generali e specifiche del formato. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Converte il documento modificato specificato, rappresentato come istanza di '', nel documento risultante del formato specificato e ne salva il contenuto in un file tramite il percorso file specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versione del documento di input, che è stato modificato in un editor HTML WYSIWYG e memorizzato come istanza della classe '' , che dovrebbe essere convertita in un documento di output di un formato specifico. Non deve essere null o smaltito. |
|
|  | filePath | java.lang.String | Percorso del file in cui verrà salvato il documento di output. Se esiste già un file con lo stesso nome, verrà completamente sovrascritto. La stringa del percorso non deve essere null, vuota o contenere solo spazi. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Opzioni di salvataggio del documento, che definiscono il formato del documento risultante, nonché le opzioni di salvataggio generali e specifiche del formato. Non deve essere null. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Converte il documento modificato specificato (rappresentato da un [EditableDocument](../../com.groupdocs.editor/editabledocument)) in un documento di output il cui formato è determinato dall'estensione del nome file, e lo salva nel percorso file specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versione del documento di input che è stato modificato in un editor HTML WYSIWYG e memorizzato come istanza di [EditableDocument](../../com.groupdocs.editor/editabledocument). Non deve essere  null  o smaltito. |
|
|  | filePath | java.lang.String | Percorso del file in cui verrà salvato il documento di output. Se esiste un file con lo stesso nome, verrà completamente sovrascritto. La stringa del percorso non deve essere null, vuota o contenere solo spazi bianchi. Poiché le opzioni di salvataggio predefinite e il formato di output sono determinati da questo nome file, deve avere un'estensione valida. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Converte il documento originale dopo la modifica (ad esempio,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
nel documento risultante del formato specificato e ne salva il contenuto nello stream fornito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Il flusso su cui verrà salvato il documento di output. Questo flusso dovrebbe essere scrivibile e posizionato all'inizio del contenuto del documento. Non deve essere null. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Opzioni di salvataggio del documento che definiscono il formato del documento risultante, nonché le opzioni di salvataggio generali e specifiche del formato. Non deve essere null. |

<br />

*** ** * ** ***

Se l'outputDocument o saveOptions sono null, verrà sollevata una NullPointerException. Se il documento da salvare è mancante, verrà sollevata una NullPointerException.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - Il flusso contenente il contenuto del documento salvato.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Salva il contenuto del documento corrente nello stream di output specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Il flusso su cui verrà salvato il contenuto del documento. Questo non può essere null. |

<br />

*** ** * ** ***

Questo metodo copia il contenuto dalla rappresentazione interna del documento allo stream di output fornito. La posizione originale dello stream viene preservata dopo l'operazione di salvataggio.

<br />

|

**Returns:**
java.io.OutputStream - Il flusso con il contenuto del documento salvato.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Restituisce i metadati del documento che è stato caricato in questa istanza di 'Editor'


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | password | java.lang.String | L'utente può specificare una password per un documento, se questo documento è crittografato con la password. Può essere NULL o una stringa vuota, equivalenti a una password assente. Per quei formati di documento che non supportano la protezione con password, questo argomento verrà ignorato. Se il documento è crittografato e la password non è specificata in questo parametro, ma era stata specificata in precedenza nelle opzioni di caricamento durante la creazione di questa istanza, verrà utilizzata. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Dispone di questa istanza di Editor, in modo che rilasci tutte le risorse interne
risorse e diventa non disponibile per ulteriori utilizzi


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Indica se questa istanza di Editor è già stata eliminata e non può essere
utilizzata ulteriormente (true) o meno ed è attiva (false)


**Returns:**
boolean
