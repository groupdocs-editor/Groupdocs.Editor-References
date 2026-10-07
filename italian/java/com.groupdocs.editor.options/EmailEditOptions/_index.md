---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Consente di specificare opzioni personalizzate per la modifica dei documenti nei diversi formati di posta elettronica"
type: docs
weight: 14
url: /it/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Consente di specificare opzioni personalizzate per la modifica di documenti nei diversi formati di posta elettronica (email)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Inizializza una nuova istanza della classe [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), dove tutte le opzioni sono impostate ai valori predefiniti |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Inizializza una nuova istanza della classe [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) con |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parametro
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Consente di controllare quali parti del messaggio di posta devono essere consegnate all'output [EditableDocument](../../com.groupdocs.editor/editabledocument) e poi all'HTML generato |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Consente di controllare quali parti del messaggio di posta devono essere consegnate all'output [EditableDocument](../../com.groupdocs.editor/editabledocument) e poi all'HTML generato |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Inizializza una nuova istanza della classe [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), dove tutte le opzioni sono impostate ai valori predefiniti


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Inizializza una nuova istanza della classe [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) con
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parametro


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | mailMessageOutput | int | L'output del messaggio di posta, che può anche essere specificato tramite la proprietà |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Consente di controllare quali parti del messaggio di posta devono essere consegnate all'output [EditableDocument](../../com.groupdocs.editor/editabledocument) e poi all'HTML generato
Valore: enum con flag che controlla le parti del messaggio di posta, che devono essere elaborate. Il valore predefinito è MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Consente di controllare quali parti del messaggio di posta devono essere consegnate all'output [EditableDocument](../../com.groupdocs.editor/editabledocument) e poi all'HTML generato
Valore: enum con flag che controlla le parti del messaggio di posta, che devono essere elaborate. Il valore predefinito è MailMessageOutput.All


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

