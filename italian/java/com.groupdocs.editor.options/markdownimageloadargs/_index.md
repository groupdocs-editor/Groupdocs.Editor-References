---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Fornisce i dati per l'evento MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs."
type: docs
weight: 22
url: /it/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Fornisce i dati per il

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

evento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Ottiene o imposta il nome file (come appare nel documento Markdown) che sarà |
processato.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Ottiene o imposta il nome file (come appare nel documento Markdown) che sarà |
processato.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Ottieni un valore che indica se questa immagine ha un collegamento URI assoluto. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Ottieni un valore che indica se questa immagine ha un collegamento URI assoluto. |
|
|  | [setData(byte[] data)](#setData-byte---) | Imposta i dati forniti dall'utente della risorsa che vengono usati se |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Ottiene o imposta il nome file (come appare nel documento Markdown) che sarà
processato.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Ottiene o imposta il nome file (come appare nel documento Markdown) che sarà
processato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Ottieni un valore che indica se questa immagine ha un collegamento URI assoluto.
Valore:  true  se questa immagine ha un collegamento URI assoluto; altrimenti,  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Ottieni un valore che indica se questa immagine ha un collegamento URI assoluto.
Valore:  true  se questa immagine ha un collegamento URI assoluto; altrimenti,  false .


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Imposta i dati forniti dall'utente della risorsa che vengono usati se

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] |  |

