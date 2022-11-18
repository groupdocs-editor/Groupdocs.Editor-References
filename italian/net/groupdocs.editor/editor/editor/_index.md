---
title: Editor
second_title: GroupDocs.Editor per Riferimento API .NET
description: Inizializza la nuova istanza dellEditor con il documento di input specificato come flusso
type: docs
weight: 10
url: /it/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

Inizializza la nuova istanza dell'Editor con il documento di input specificato (come flusso)

```csharp
public Editor(Func<Stream> document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Delegato, che dovrebbe restituire un flusso con il contenuto del documento. Non dovrebbe essere NULL. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Editor: [Formati di documenti supportati da GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Editor per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Guarda anche

* class [Editor](../../editor)
* spazio dei nomi [GroupDocs.Editor](../../editor)
* assemblea [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

Inizializza la nuova istanza dell'Editor con il documento di input specificato (come flusso) con le relative opzioni di caricamento

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Delegato, che dovrebbe restituire un flusso con il contenuto del documento. Non dovrebbe essere NULL. |
| loadOptions | Func`1 | Delegato, che dovrebbe restituire un'opzione di caricamento del documento. Può essere NULL e può restituire null - in tal caso il tipo di documento verrà rilevato automaticamente e verranno applicate le opzioni di caricamento predefinite per quel tipo. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Editor: [Formati di documenti supportati da GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Editor per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Ulteriori informazioni su come aprire e modificare documenti e documenti protetti da password da archivi diversi: [Carica e modifica i documenti utilizzando GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Guarda anche

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* spazio dei nomi [GroupDocs.Editor](../../editor)
* assemblea [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

Inizializza la nuova istanza dell'Editor con il documento di input specificato (come percorso file completo)

```csharp
public Editor(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso completo del file. Non dovrebbe essere NULL. Dovrebbe essere valido e il file dovrebbe esistere. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Editor: [Formati di documenti supportati da GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Editor per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Guarda anche

* class [Editor](../../editor)
* spazio dei nomi [GroupDocs.Editor](../../editor)
* assemblea [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

Inizializza la nuova istanza dell'Editor con il documento di input specificato (come percorso file completo) con le relative opzioni di caricamento

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso completo del file. Non dovrebbe essere NULL. Dovrebbe essere valido e il file dovrebbe esistere. |
| loadOptions | Func`1 | Delegato, che dovrebbe restituire un'opzione di caricamento del documento. Può essere NULL e può restituire null - in tal caso il tipo di documento verrà rilevato automaticamente e verranno applicate le opzioni di caricamento predefinite per quel tipo. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Editor: [Formati di documenti supportati da GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Editor per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Ulteriori informazioni su come aprire e modificare documenti e documenti protetti da password da archivi diversi: [Carica e modifica i documenti utilizzando GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Guarda anche

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* spazio dei nomi [GroupDocs.Editor](../../editor)
* assemblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
