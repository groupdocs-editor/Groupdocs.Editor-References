---
title: Save
second_title: GroupDocs.Editor per Riferimento API .NET
description: Converte il documento modificato specificato rappresentato come istanza di EditableDocumentgroupdocs.editor/editabledocument  nel documento risultante del formato specificato e ne salva il contenuto nello stream specificato
type: docs
weight: 70
url: /it/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save}

Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../../editabledocument) , nel documento risultante del formato specificato e ne salva il contenuto nello stream specificato

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputDocument | EditableDocument | Versione del documento di input, che è stata modificata nell'editor HTML WYSIWYG ed è memorizzata come istanza di '[`EditableDocument`](../../editabledocument)class, che dovrebbe essere convertito in un documento di output di un formato specifico. Non deve essere nullo o eliminato. |
| outputDocument | Stream | Flusso di output, in cui verrà registrato il contenuto del documento risultante. Non deve essere nullo, disposto, deve supportare la scrittura. |
| saveOptions | ISaveOptions | Opzioni di salvataggio del documento, che definiscono il formato del documento risultante, e anche opzioni di salvataggio generali e specifiche del formato. Non deve essere nullo. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sul salvataggio del documento dopo la modifica utilizzando GroupDocs.Editor: [Come salvare il documento modificato utilizzando GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Guarda anche

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* spazio dei nomi [GroupDocs.Editor](../../editor)
* assemblea [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_1}

Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../../editabledocument) , nel documento risultante del formato specificato e ne salva il contenuto nel file specificato percorso

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputDocument | EditableDocument | Versione del documento di input, che è stata modificata nell'editor HTML WYSIWYG ed è memorizzata come istanza di '[`EditableDocument`](../../editabledocument)class, che dovrebbe essere convertito in un documento di output di un formato specifico. Non deve essere nullo o eliminato. |
| filePath | String | Percorso del file in cui verrà salvato il documento di output. Esiste un file con lo stesso nome, sarà completamente riscritto. La stringa con percorso non deve essere nulla, vuota o contenere solo spazi bianchi. |
| saveOptions | ISaveOptions | Opzioni di salvataggio del documento, che definiscono il formato del documento risultante, e anche opzioni di salvataggio generali e specifiche del formato. Non deve essere nullo. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sul salvataggio del documento dopo la modifica utilizzando GroupDocs.Editor: [Come salvare il documento modificato utilizzando GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Guarda anche

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* spazio dei nomi [GroupDocs.Editor](../../editor)
* assemblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->