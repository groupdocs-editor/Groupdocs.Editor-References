---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Consente di specificare opzioni personalizzate per generare e salvare documenti di posta elettronica"
type: docs
weight: 15
url: /it/java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti di posta elettronica (email)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Inizializza una nuova istanza della classe [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), dove tutte le opzioni sono impostate ai valori predefiniti |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Inizializza una nuova istanza della classe [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) con |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parametro
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Consente di controllare quali parti del messaggio di posta devono essere consegnate al documento email di output, che sarà generato e salvato con il metodo [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Consente di controllare quali parti del messaggio di posta devono essere consegnate al documento email di output, che sarà generato e salvato con il metodo [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Inizializza una nuova istanza della classe [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), dove tutte le opzioni sono impostate ai valori predefiniti


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Inizializza una nuova istanza della classe [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) con
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


Consente di controllare quali parti del messaggio di posta devono essere consegnate al documento email di output, che sarà generato e salvato con il metodo [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Valore: enum con flag che controlla le parti del messaggio di posta, che devono essere elaborate. Il valore predefinito è MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Consente di controllare quali parti del messaggio di posta devono essere consegnate al documento email di output, che sarà generato e salvato con il metodo [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Valore: enum con flag che controlla le parti del messaggio di posta, che devono essere elaborate. Il valore predefinito è MailMessageOutput.All


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

