---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten in den verschiedenen E‑Mail‑Formaten"
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten in den verschiedenen elektronischen Mail (email)-Formaten

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Initialisiert eine neue Instanz der Klasse [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), wobei alle Optionen auf ihre Standardwerte gesetzt sind. |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Initialisiert eine neue Instanz der Klasse [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) mit |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) Parameter
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Ermöglicht die Steuerung, welche Teile der E‑Mail‑Nachricht an das Ausgabedokument [EditableDocument](../../com.groupdocs.editor/editabledocument) und anschließend an das erzeugte HTML übergeben werden sollen. |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Ermöglicht die Steuerung, welche Teile der E‑Mail‑Nachricht an das Ausgabedokument [EditableDocument](../../com.groupdocs.editor/editabledocument) und anschließend an das erzeugte HTML übergeben werden sollen. |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Initialisiert eine neue Instanz der Klasse [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), wobei alle Optionen auf ihre Standardwerte gesetzt sind.


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Initialisiert eine neue Instanz der Klasse [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) mit
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) Parameter


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | mailMessageOutput | int | Der Mailnachrichten‑Ausgang, der ebenfalls über die Eigenschaft angegeben werden kann. |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Ermöglicht die Steuerung, welche Teile der E‑Mail‑Nachricht an das Ausgabedokument [EditableDocument](../../com.groupdocs.editor/editabledocument) und anschließend an das erzeugte HTML übergeben werden sollen.
Wert: Flag‑Enum, das die Teile der Mailnachricht steuert, die verarbeitet werden sollen. Standardwert ist MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Ermöglicht die Steuerung, welche Teile der E‑Mail‑Nachricht an das Ausgabedokument [EditableDocument](../../com.groupdocs.editor/editabledocument) und anschließend an das erzeugte HTML übergeben werden sollen.
Wert: Flag‑Enum, das die Teile der Mailnachricht steuert, die verarbeitet werden sollen. Standardwert ist MailMessageOutput.All


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

