---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von E‑Mail‑Dokumenten"
type: docs
weight: 15
url: /de/java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von elektronischen Mail‑ (email) Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Initialisiert eine neue Instanz der [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions)-Klasse, wobei alle Optionen auf ihre Standardwerte gesetzt werden |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Initialisiert eine neue Instanz der [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions)-Klasse mit |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) Parameter
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Ermöglicht die Steuerung, welche Teile der E‑Mail‑Nachricht in das Ausgabedokument übernommen werden sollen, das mit der Methode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) erzeugt und gespeichert wird |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Ermöglicht die Steuerung, welche Teile der E‑Mail‑Nachricht in das Ausgabedokument übernommen werden sollen, das mit der Methode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) erzeugt und gespeichert wird |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Initialisiert eine neue Instanz der [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions)-Klasse, wobei alle Optionen auf ihre Standardwerte gesetzt werden


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Initialisiert eine neue Instanz der [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions)-Klasse mit
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) Parameter


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | mailMessageOutput | int | Der MailMessageOutput, der auch über die Eigenschaft angegeben werden kann |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Ermöglicht die Steuerung, welche Teile der E‑Mail‑Nachricht in das Ausgabedokument übernommen werden sollen, das mit der Methode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) erzeugt und gespeichert wird
Wert: Flag‑Enum, das die Teile der Mailnachricht steuert, die verarbeitet werden sollen. Standardwert ist MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Ermöglicht die Steuerung, welche Teile der E‑Mail‑Nachricht in das Ausgabedokument übernommen werden sollen, das mit der Methode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) erzeugt und gespeichert wird
Wert: Flag‑Enum, das die Teile der Mailnachricht steuert, die verarbeitet werden sollen. Standardwert ist MailMessageOutput.All


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

