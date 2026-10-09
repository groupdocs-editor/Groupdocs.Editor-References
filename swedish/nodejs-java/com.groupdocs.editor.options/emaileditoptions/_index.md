---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att ange anpassade alternativ för redigering av dokument i olika e-postformat"
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Tillåter att ange anpassade alternativ för att redigera dokument i de olika e‑post (email) formaten

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Initierar en ny instans av klassen [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), där alla alternativ är satta till sina standardvärden. |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Initierar en ny instans av klassen [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) med |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parameter
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Tillåter att kontrollera vilka delar av e‑postmeddelandet som ska levereras till utdata [EditableDocument](../../com.groupdocs.editor/editabledocument) och sedan till den genererade HTML‑koden. |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Tillåter att kontrollera vilka delar av e‑postmeddelandet som ska levereras till utdata [EditableDocument](../../com.groupdocs.editor/editabledocument) och sedan till den genererade HTML‑koden. |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Initierar en ny instans av klassen [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), där alla alternativ är satta till sina standardvärden.


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Initierar en ny instans av klassen [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) med
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


Tillåter att kontrollera vilka delar av e‑postmeddelandet som ska levereras till utdata [EditableDocument](../../com.groupdocs.editor/editabledocument) och sedan till den genererade HTML‑koden.
Värde: Flaggad enum som styr vilka delar av e‑postmeddelandet som ska behandlas. Standardvärdet är MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Tillåter att kontrollera vilka delar av e‑postmeddelandet som ska levereras till utdata [EditableDocument](../../com.groupdocs.editor/editabledocument) och sedan till den genererade HTML‑koden.
Värde: Flaggad enum som styr vilka delar av e‑postmeddelandet som ska behandlas. Standardvärdet är MailMessageOutput.All


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

