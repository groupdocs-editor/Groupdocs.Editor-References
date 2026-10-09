---
title: "EmailSaveOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti email elettronici"
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.editor.options/emailsaveoptions/
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
parametro (#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput)
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
parametro (#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput)


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
Valore: enum con flag che controlla le parti del messaggio di posta da elaborare. Il valore predefinito è MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Consente di controllare quali parti del messaggio di posta devono essere consegnate al documento email di output, che sarà generato e salvato con il metodo [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Valore: enum con flag che controlla le parti del messaggio di posta da elaborare. Il valore predefinito è MailMessageOutput.All


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

