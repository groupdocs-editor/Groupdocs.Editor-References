---
title: "PdfLoadOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Contiene opzioni per il caricamento di documenti PDF nella classe Editor"
type: docs
weight: 30
url: /it/java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Contiene opzioni per il caricamento di documenti PDF nella classe Editor

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Consente di specificare, modificare e ottenere la password, che sarà utilizzata per aprire un documento PDF, se è codificato. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Consente di specificare, modificare e ottenere la password, che sarà utilizzata per aprire un documento PDF, se è codificato. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Consente di specificare, modificare e ottenere la password, che sarà utilizzata per aprire un documento PDF, se è codificato.
Impostare a NULL o a stringa vuota per non utilizzare la password (valore predefinito).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Consente di specificare, modificare e ottenere la password, che sarà utilizzata per aprire un documento PDF, se è codificato.
Impostare a NULL o a stringa vuota per non utilizzare la password (valore predefinito).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

