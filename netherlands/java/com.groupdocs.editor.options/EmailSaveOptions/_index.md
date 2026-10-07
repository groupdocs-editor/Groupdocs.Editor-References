---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe om aangepaste opties op te geven voor het genereren en opslaan van elektronische e‑maildocumenten"
type: docs
weight: 15
url: /nl/java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Staat toe aangepaste opties op te geven voor het genereren en opslaan van elektronische mail (email) documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Initialiseert een nieuw exemplaar van de [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) klasse, waarbij alle opties zijn ingesteld op hun standaardwaarden |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Initialiseert een nieuw exemplaar van de [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) klasse met |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parameter
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Staat toe om te bepalen welke delen van het e‑mailbericht moeten worden geleverd aan het uitvoer‑e‑maildocument, dat zal worden gegenereerd en opgeslagen met de [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) methode |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Staat toe om te bepalen welke delen van het e‑mailbericht moeten worden geleverd aan het uitvoer‑e‑maildocument, dat zal worden gegenereerd en opgeslagen met de [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) methode |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Initialiseert een nieuw exemplaar van de [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) klasse, waarbij alle opties zijn ingesteld op hun standaardwaarden


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Initialiseert een nieuw exemplaar van de [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) klasse met
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parameter


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | mailMessageOutput | int | De mailberichtoutput, die ook kan worden opgegeven via de eigenschap |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Staat toe om te bepalen welke delen van het e‑mailbericht moeten worden geleverd aan het uitvoer‑e‑maildocument, dat zal worden gegenereerd en opgeslagen met de [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) methode
Waarde: Gemarkeerde enum die de delen van het mailbericht regelt die moeten worden verwerkt. Standaardwaarde is MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Staat toe om te bepalen welke delen van het e‑mailbericht moeten worden geleverd aan het uitvoer‑e‑maildocument, dat zal worden gegenereerd en opgeslagen met de [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) methode
Waarde: Gemarkeerde enum die de delen van het mailbericht regelt die moeten worden verwerkt. Standaardwaarde is MailMessageOutput.All


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

