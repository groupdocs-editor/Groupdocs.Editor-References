---
title: Editor
second_title: GroupDocs.Editor per Riferimento API .NET
description: Classe principale che incapsula i metodi di conversione. La classe Editor fornisce metodi per caricare modificare e salvare documenti di tutti i formati supportati. È usa e getta quindi usa una direttiva using o elimina le sue risorse manualmente tramite la chiamata al metodo Dispose . Il caricamento del documento viene eseguito tramite i costruttori. Modifica del documento  tramite il metodo Modifica e salvataggio nel documento risultante dopo la modifica  tramite il metodo Salva.
type: docs
weight: 20
url: /it/net/groupdocs.editor/editor/
---
## Editor class

Classe principale, che incapsula i metodi di conversione. La classe Editor fornisce metodi per caricare, modificare e salvare documenti di tutti i formati supportati. È usa e getta, quindi usa una direttiva 'using' o elimina le sue risorse manualmente tramite la chiamata al metodo 'Dispose ()'. Il caricamento del documento viene eseguito tramite i costruttori. Modifica del documento - tramite il metodo "Modifica" e salvataggio nel documento risultante dopo la modifica - tramite il metodo "Salva".

```csharp
public sealed class Editor : IAuxDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Editor](editor#constructor)(Func&lt;Stream&gt;) | Inizializza la nuova istanza dell'Editor con il documento di input specificato (come flusso) |
| [Editor](editor#constructor_2)(string) | Inizializza la nuova istanza dell'Editor con il documento di input specificato (come percorso file completo) |
| [Editor](editor#constructor_1)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Inizializza la nuova istanza dell'Editor con il documento di input specificato (come flusso) con le relative opzioni di caricamento |
| [Editor](editor#constructor_3)(string, Func&lt;ILoadOptions&gt;) | Inizializza la nuova istanza dell'Editor con il documento di input specificato (come percorso file completo) con le relative opzioni di caricamento |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Indica se questa istanza dell'Editor è già stata eliminata e non può più essere utilizzata (true) oppure non è stata ancora eliminata ed è quindi attiva (false) |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Elimina questa istanza di Editor, in modo che rilasci tutte le risorse interne e diventi non disponibile per un ulteriore utilizzo |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Apre un documento caricato in precedenza per la modifica utilizzando le opzioni predefinite generando e restituendo un'istanza di '[`EditableDocument`](../editabledocument) class, che, a sua volta, contiene metodi per produrre markup HTML e risorse associate. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Apre un documento caricato in precedenza per la modifica utilizzando le opzioni specifiche del formato specificate generando e restituendo un'istanza di '[`EditableDocument`](../editabledocument) class, che, a sua volta, contiene metodi per produrre markup HTML e risorse associate. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Restituisce i metadati relativi al documento, che è stato caricato in questa istanza "Editor" |
| [Save](../../groupdocs.editor/editor/save#save)(EditableDocument, Stream, ISaveOptions) | Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../editabledocument) , nel documento risultante del formato specificato e ne salva il contenuto nello stream specificato |
| [Save](../../groupdocs.editor/editor/save#save_1)(EditableDocument, string, ISaveOptions) | Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../editabledocument) , nel documento risultante del formato specificato e ne salva il contenuto nel file specificato percorso |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Evento, che si verifica quando questa istanza dell'Editor viene eliminata con tutte le sue risorse interne |

### Osservazioni

La classe Editor deve essere considerata un punto di ingresso e l'oggetto radice di GroupDocs.Editor. Tutte le operazioni vengono eseguite utilizzando questa classe. L'utilizzo tipico della classe Editor per l'esecuzione di una pipeline completa di modifica dei documenti è il successivo:

1. Carica un documento nell'istanza Editor tramite il suo costruttore.
2. Facoltativamente, rilevare un tipo di documento utilizzando a[`GetDocumentInfo`](./getdocumentinfo) metodo.
3. Apri un documento per la modifica chiamando an[`Edit`](./edit)metodo e ottenere un'istanza di[`EditableDocument`](../editabledocument) classe da esso.
4. Modifica del contenuto di un documento sul lato client utilizzando qualsiasi editor HTML WYSIWYG.
5. Creazione di una nuova istanza di[`EditableDocument`](../editabledocument) dal contenuto del documento modificato.
6. Salvataggio di un documento modificato in un formato di output chiamando a[`Save`](./save) metodo.
7. Smaltimento di un'istanza della classe Editor tramite l'operatore "using" o manualmente.

### Guarda anche

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* spazio dei nomi [GroupDocs.Editor](../../groupdocs.editor)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
