---
title: "WordProcessingLoadOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Contiene opzioni per il caricamento di documenti WordProcessing compatibili con Word, come DOCX, RTF, ODT, ecc."
type: docs
weight: 45
url: /it/nodejs-java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

Contiene opzioni per il caricamento di documenti WordProcessing (compatibili con Word) come
DOC(X), RTF, ODT, ecc. nella classe Editor

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Consente di specificare, modificare e ottenere la password, che sarà utilizzata per |
aprire il documento WordProcessing, se è codificato.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Consente di specificare, modificare e ottenere la password, che sarà utilizzata per |
aprire il documento WordProcessing, se è codificato.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Consente di specificare, modificare e ottenere la password, che sarà utilizzata per
apertura del documento WordProcessing, se è codificato. Impostare su NULL o vuoto
stringa per non utilizzare la password (valore predefinito).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Consente di specificare, modificare e ottenere la password, che sarà utilizzata per
apertura del documento WordProcessing, se è codificato. Impostare su NULL o vuoto
stringa per non utilizzare la password (valore predefinito).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

