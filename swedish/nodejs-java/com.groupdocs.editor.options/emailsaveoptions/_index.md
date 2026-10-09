---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara e-postdokument"
type: docs
weight: 15
url: /sv/nodejs-java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Tillåter att ange anpassade alternativ för att generera och spara e‑post (email) dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Initierar en ny instans av klassen [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), där alla alternativ är satta till sina standardvärden |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Initierar en ny instans av klassen [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) med |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parameter
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Tillåter att styra vilka delar av e‑postmeddelandet som ska levereras till utdata‑e‑postdokumentet, som kommer att genereras och sparas med metoden [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-). |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Tillåter att styra vilka delar av e‑postmeddelandet som ska levereras till utdata‑e‑postdokumentet, som kommer att genereras och sparas med metoden [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-). |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Initierar en ny instans av klassen [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), där alla alternativ är satta till sina standardvärden


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Initierar en ny instans av klassen [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) med
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parameter


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | mailMessageOutput | int | E‑postmeddelandets utdata, som också kan specificeras via egenskapen |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Tillåter att styra vilka delar av e‑postmeddelandet som ska levereras till utdata‑e‑postdokumentet, som kommer att genereras och sparas med metoden [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-).
Värde: Flaggad enum som styr vilka delar av e‑postmeddelandet som ska behandlas. Standardvärdet är MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Tillåter att styra vilka delar av e‑postmeddelandet som ska levereras till utdata‑e‑postdokumentet, som kommer att genereras och sparas med metoden [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-).
Värde: Flaggad enum som styr vilka delar av e‑postmeddelandet som ska behandlas. Standardvärdet är MailMessageOutput.All


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

