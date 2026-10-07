---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Bevat opties voor het laden van WordProcessing-compatibele documenten zoals DOCX, RTF, ODT enz."
type: docs
weight: 45
url: /nl/java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

Bevat opties voor het laden van WordProcessing (Word-compatibele) documenten zoals
DOC(X), RTF, ODT enz. in de Editor-klasse

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor |
het openen van een WordProcessing-document, indien het gecodeerd is.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor |
het openen van een WordProcessing-document, indien het gecodeerd is.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor
het openen van een WordProcessing-document, indien het gecodeerd is. Instellen op NULL of leeg
string om het wachtwoord niet te gebruiken (standaardwaarde).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor
het openen van een WordProcessing-document, indien het gecodeerd is. Instellen op NULL of leeg
string om het wachtwoord niet te gebruiken (standaardwaarde).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

