---
title: "Editor"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Classe principale che incapsula i metodi di conversione. La classe Editor fornisce metodi per caricare, modificare e salvare documenti di tutti i formati supportati. È disposable, quindi utilizza una direttiva using o rilascia manualmente le sue risorse tramite la chiamata al metodo Dispose. Il caricamento dei documenti avviene tramite i costruttori. La modifica dei documenti avviene tramite il metodo Edit e il salvataggio del documento risultante dopo la modifica avviene tramite il metodo Save."
type: docs
weight: 20
url: /it/net/groupdocs.editor/editor/
---
## Editor class

Classe principale, che incapsula i metodi di conversione. La classe Editor fornisce metodi per caricare, modificare e salvare documenti di tutti i formati supportati. È eliminabile, quindi utilizza una direttiva 'using' o rilascia manualmente le sue risorse tramite la chiamata al metodo 'Dispose()'. Il caricamento dei documenti avviene tramite i costruttori. La modifica dei documenti - tramite il metodo 'Edit', e il salvataggio del documento risultante dopo la modifica - tramite il metodo 'Save'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | Inizializza una nuova istanza della classe [`Editor`](../editor) e crea un nuovo documento vuoto basato sul formato specificato. |
| [Editor](editor#constructor_1)(Stream) | Inizializza una nuova istanza di Editor con il documento di input specificato (come stream). |
| [Editor](editor#constructor_3)(string) | Inizializza una nuova istanza di Editor con il documento di input specificato (come percorso completo del file) e le impostazioni di Editor |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | Inizializza una nuova istanza di Editor con il documento di input specificato (come stream) e le relative opzioni di caricamento. |
| [Editor](editor#constructor_4)(string, ILoadOptions) | Inizializza una nuova istanza di Editor con il documento di input specificato (come percorso completo del file) e le relative opzioni di caricamento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | Fornisce l'accesso alle funzionalità per la gestione dei campi modulo all'interno del documento. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Indica se questa istanza di Editor è già stata eliminata e non può più essere utilizzata (true) oppure non è ancora stata eliminata ed è quindi attiva (false) |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Elimina questa istanza di Editor, rilasciando tutte le risorse interne e rendendola non più disponibile per ulteriori utilizzi. |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Apre un documento precedentemente caricato per la modifica usando le opzioni predefinite generando e restituendo un'istanza della classe '[`EditableDocument`](../editabledocument)', che a sua volta contiene metodi per produrre markup HTML e le risorse associate. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Apre un documento precedentemente caricato per la modifica usando le opzioni specifiche del formato, generando e restituendo un'istanza della classe '[`EditableDocument`](../editabledocument)', che a sua volta contiene metodi per produrre markup HTML e le risorse associate. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Restituisce i metadati sul documento, che è stato caricato in questa istanza di 'Editor' |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | Salva il contenuto del documento corrente nello stream di output specificato. |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../editabledocument)', nel documento risultante del formato determinato dall'estensione del nome file e ne salva il contenuto nel file al percorso specificato. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | Converte il documento originale dopo la modifica (ad esempio, [`FormFieldManager`](./formfieldmanager)), nel documento risultante del formato specificato e ne salva il contenuto nello stream fornito. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../editabledocument)', nel documento risultante del formato specificato e ne salva il contenuto nello stream specificato. |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../editabledocument)', nel documento risultante del formato specificato e ne salva il contenuto nel file al percorso specificato. |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Evento che si verifica quando questa istanza di Editor viene eliminata con tutte le sue risorse interne |

### Osservazioni

La classe Editor dovrebbe essere considerata come punto di ingresso e oggetto radice di GroupDocs.Editor. Tutte le operazioni vengono eseguite utilizzando questa classe. L'uso tipico della classe Editor per eseguire un'intera pipeline di modifica del documento è il seguente:

1. Carica un documento nell'istanza di Editor tramite il suo costruttore.
2. Facoltativamente, rileva il tipo di documento usando il metodo [`GetDocumentInfo`](./getdocumentinfo).
3. Apri un documento per la modifica chiamando il metodo [`Edit`](./edit) e ottenendo un'istanza della classe [`EditableDocument`](../editabledocument) da esso.
4. Modifica il contenuto del documento lato client usando qualsiasi editor HTML WYSIWYG.
5. Crea una nuova istanza di [`EditableDocument`](../editabledocument) dal contenuto del documento modificato.
6. Salva un documento modificato in un formato di output chiamando il metodo [`Save`](./save).
7. Eliminazione di un'istanza della classe Editor tramite l'operatore 'using' o manualmente.

### Vedi anche

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
