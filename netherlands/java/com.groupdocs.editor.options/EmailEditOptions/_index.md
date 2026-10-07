---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe om aangepaste opties op te geven voor het bewerken van documenten in de verschillende e‑mailformaten"
type: docs
weight: 14
url: /nl/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Staat toe aangepaste opties op te geven voor het bewerken van documenten in de verschillende elektronische mail (email) formaten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Initialiseert een nieuw exemplaar van de [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) klasse, waarbij alle opties zijn ingesteld op hun standaardwaarden |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Initialiseert een nieuw exemplaar van de [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) klasse met |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parameter
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Staat toe om te bepalen welke delen van het e‑mailbericht moeten worden geleverd aan de output [EditableDocument](../../com.groupdocs.editor/editabledocument) en vervolgens aan de gegenereerde HTML |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Staat toe om te bepalen welke delen van het e‑mailbericht moeten worden geleverd aan de output [EditableDocument](../../com.groupdocs.editor/editabledocument) en vervolgens aan de gegenereerde HTML |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Initialiseert een nieuw exemplaar van de [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) klasse, waarbij alle opties zijn ingesteld op hun standaardwaarden


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Initialiseert een nieuw exemplaar van de [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) klasse met
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


Staat toe om te bepalen welke delen van het e‑mailbericht moeten worden geleverd aan de output [EditableDocument](../../com.groupdocs.editor/editabledocument) en vervolgens aan de gegenereerde HTML
Waarde: Gemarkeerde enum die de delen van het mailbericht regelt die moeten worden verwerkt. Standaardwaarde is MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Staat toe om te bepalen welke delen van het e‑mailbericht moeten worden geleverd aan de output [EditableDocument](../../com.groupdocs.editor/editabledocument) en vervolgens aan de gegenereerde HTML
Waarde: Gemarkeerde enum die de delen van het mailbericht regelt die moeten worden verwerkt. Standaardwaarde is MailMessageOutput.All


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

