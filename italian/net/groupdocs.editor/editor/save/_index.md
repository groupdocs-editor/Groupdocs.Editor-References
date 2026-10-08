---
title: "Save"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Converte il documento modificato specificato rappresentato come istanza di EditableDocumentgroupdocs.editor/editabledocument nel documento risultante del formato specificato e salva il suo contenuto nello stream specificato"
type: docs
weight: 80
url: /it/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../../editabledocument)', nel documento risultante del formato specificato e salva il suo contenuto nello stream specificato

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputDocument | EditableDocument | Versione del documento di input, che è stato modificato nell'editor HTML WYSIWYG e viene memorizzata come istanza della classe '[`EditableDocument`](../../editabledocument)', che dovrebbe essere convertita nel documento di output di un formato specifico. Non deve essere null o eliminato. |
| outputDocument | Stream | Stream di output, nel quale il contenuto del documento risultante sarà registrato. Non deve essere null, eliminato, deve supportare la scrittura. |
| saveOptions | ISaveOptions | Opzioni di salvataggio del documento, che definiscono il formato del documento risultante, nonché le opzioni di salvataggio generali e specifiche per formato. Non deve essere null. |

### Osservazioni

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Vedi anche

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../../editabledocument)', nel documento risultante del formato specificato e salva il suo contenuto in un file nel percorso file specificato

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputDocument | EditableDocument | Versione del documento di input, che è stato modificato nell'editor HTML WYSIWYG e viene memorizzata come istanza della classe '[`EditableDocument`](../../editabledocument)', che dovrebbe essere convertita nel documento di output di un formato specifico. Non deve essere null o eliminato. |
| filePath | String | Percorso al file, nel quale il documento di output sarà salvato. Se esiste un file con lo stesso nome, verrà completamente sovrascritto. La stringa del percorso non deve essere null, vuota o contenere solo spazi bianchi. |
| saveOptions | ISaveOptions | Opzioni di salvataggio del documento, che definiscono il formato del documento risultante, nonché le opzioni di salvataggio generali e specifiche per formato. Non deve essere null. |

### Osservazioni

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Vedi anche

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Converte il documento modificato specificato, rappresentato come istanza di '[`EditableDocument`](../../editabledocument)', nel documento risultante con formato determinato dall'estensione del nome file e ne salva il contenuto nel file al percorso specificato.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputDocument | EditableDocument | Versione del documento di input, che è stato modificato nell'editor HTML WYSIWYG e viene memorizzata come istanza della classe '[`EditableDocument`](../../editabledocument)', che dovrebbe essere convertita nel documento di output di un formato specifico. Non deve essere null o eliminato. |
| filePath | String | Percorso del file in cui verrà salvato il documento di output. Se esiste già un file con lo stesso nome, verrà sovrascritto completamente. La stringa del percorso non deve essere nulla, vuota o contenere solo spazi. Poiché le opzioni di salvataggio predefinite e il formato di output sono determinati da questo nome file, deve avere un'estensione valida. |

### Vedi anche

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Converte il documento originale dopo la modifica (ad esempio, [`FormFieldManager`](../formfieldmanager)), nel documento risultante nel formato specificato e ne salva il contenuto nello stream fornito.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputDocument | Stream | Lo stream su cui verrà salvato il documento di output. Questo stream deve essere scrivibile e posizionato all'inizio del contenuto del documento. Non deve essere nullo. |
| saveOptions | WordProcessingSaveOptions | Opzioni di salvataggio del documento che definiscono il formato del documento risultante, nonché le opzioni di salvataggio generali e specifiche per formato. Non deve essere nullo. |

### Valore restituito

Lo stream contenente il contenuto del documento salvato.

### Osservazioni

Se *outputDocument* o *saveOptions* sono null, verrà generata un'ArgumentNullException. Se il documento da salvare è mancante, verrà generata un'ArgumentNullException.

Generata quando *outputDocument* o *saveOptions* sono null, o quando il documento da salvare è mancante.**Scopri di più:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Vedi anche

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Salva il contenuto del documento corrente nello stream di output specificato.

```csharp
public Stream Save(Stream outputDocument)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputDocument | Stream | Lo stream su cui verrà salvato il contenuto del documento. Non può essere null. |

### Valore restituito

Lo stream con il contenuto del documento salvato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *outputDocument* è null o se il contenuto del documento è mancante. |

### Osservazioni

Questo metodo copia il contenuto dalla rappresentazione interna del documento allo stream di output fornito. La posizione originale dello stream viene preservata dopo l'operazione di salvataggio.

### Vedi anche

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
