---
title: "Editor"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Inizializza una nuova istanza della classe Editorgroupdocs.editor/editor e crea un nuovo documento vuoto basato sul formato specificato."
type: docs
weight: 10
url: /it/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Inizializza una nuova istanza della classe [`Editor`](../../editor) e crea un nuovo documento vuoto basato sul formato specificato.

```csharp
public Editor(DocumentFormatBase format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formato | DocumentFormatBase | Rappresenta il formato file del documento che verrà creato. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Esempi

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Utilizza l'istanza dell'editor per modificare e salvare i documenti
}
```

### Vedi anche

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Inizializza una nuova istanza di Editor con il documento di input specificato (come stream).

```csharp
public Editor(Stream document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | Stream | Stream che contiene il contenuto del documento. Non dovrebbe essere null. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Esempi

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Utilizza l'istanza dell'editor per modificare e salvare i documenti
    }
}
```

### Vedi anche

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Inizializza una nuova istanza di Editor con il documento di input specificato (come stream) e le relative opzioni di caricamento.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | Stream | Stream che contiene il contenuto del documento. Non dovrebbe essere null. |
| loadOptions | ILoadOptions | Opzioni di caricamento del documento. Possono essere null. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando lo stream del documento è nullo. |
| ArgumentException | Generato quando lo stream del documento non è valido. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Esempi

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Utilizza l'istanza dell'editor per modificare e salvare i documenti
    }
}
```

### Vedi anche

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Inizializza una nuova istanza di Editor con il documento di input specificato (come percorso completo del file) e le relative opzioni di caricamento.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso completo al file. Non dovrebbe essere nullo, vuoto o contenere solo spazi. Dovrebbe essere valido e il file dovrebbe esistere. |
| loadOptions | ILoadOptions | Opzioni di caricamento del documento. Possono essere null. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando il percorso del file non è valido. |
| FileNotFoundException | Generato quando il file non esiste. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Esempi

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Utilizza l'istanza dell'editor per modificare e salvare i documenti
}
```

### Vedi anche

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Inizializza una nuova istanza di Editor con il documento di input specificato (come percorso completo del file) e le impostazioni di Editor

```csharp
public Editor(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso completo al file. Non dovrebbe essere NULL. Dovrebbe essere valido e il file dovrebbe esistere. |

### Vedi anche

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
