---
title: "PresentationLoadOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per il caricamento di documenti di tutti i formati di Presentazione supportati, come PPTX, PPTM, PPSX, ecc."
type: docs
weight: 33
url: /it/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Consente di specificare opzioni personalizzate per il caricamento di documenti di tutti i formati supportati
Formati di presentazione come PPT(X), PPTM, PPS(X), ecc.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Consente di specificare, modificare e ottenere la password, che sarà utilizzata per |
apertura del documento Presentation, se è codificato.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Consente di specificare, modificare e ottenere la password, che sarà utilizzata per |
apertura del documento Presentation, se è codificato.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Consente di specificare, modificare e ottenere la password, che sarà utilizzata per
apertura del documento Presentation, se è codificato. Impostare a NULL o vuoto
stringa per rimuovere la password.


*** ** * ** ***

Per impostazione predefinita questa proprietà ha valore NULL \u2014 la password non è impostata. Se il documento Presentation di input è protetto da password, la password è obbligatoria e verrà generata un'eccezione se la password non è specificata o è non valida. Se il documento Presentation di input NON è protetto da password, ma la password è impostata, verrà ignorata.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Consente di specificare, modificare e ottenere la password, che sarà utilizzata per
apertura del documento Presentation, se è codificato. Impostare a NULL o vuoto
stringa per rimuovere la password.


*** ** * ** ***

Per impostazione predefinita questa proprietà ha valore NULL \u2014 la password non è impostata. Se il documento Presentation di input è protetto da password, la password è obbligatoria e verrà generata un'eccezione se la password non è specificata o è non valida. Se il documento Presentation di input NON è protetto da password, ma la password è impostata, verrà ignorata.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

