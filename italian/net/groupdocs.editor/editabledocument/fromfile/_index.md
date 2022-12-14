---
title: FromFile
second_title: GroupDocs.Editor per Riferimento API .NET
description: Factory statica che crea unistanza di EditableDocument da un file HTML specificato da un percorso al file .html stesso e una cartella con risorse collegate
type: docs
weight: 10
url: /it/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

Factory statica, che crea un'istanza di EditableDocument da un file HTML, specificato da un percorso al file *.html stesso e una cartella con risorse collegate

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlFilePath | String | Stringa, che contiene un percorso completo del file HTML. Non può essere nullo, deve essere un percorso file valido e il file stesso deve esistere. |
| resourceFolderPath | String | Percorso facoltativo della cartella con le risorse HTML. Se NULL, non valido o tale cartella non esiste, l'Editor proverà a trovare questa cartella da solo, analizzando il markup HTML |

### Valore di ritorno

Nuova istanza non nulla di EditableDocument

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Il percorso del file HTML e/o il percorso della cartella delle risorse non è valido |
| FileNotFoundException | Impossibile trovare il file HTML specificato |

### Guarda anche

* class [EditableDocument](../../editabledocument)
* spazio dei nomi [GroupDocs.Editor](../../editabledocument)
* assemblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
