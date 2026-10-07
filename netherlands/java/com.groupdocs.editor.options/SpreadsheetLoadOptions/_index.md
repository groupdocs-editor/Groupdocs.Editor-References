---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Bevat opties voor het laden van binaire Spreadsheet‑Cells Excel‑compatibele documenten zoals XLSX, ODS enz."
type: docs
weight: 36
url: /nl/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Bevat opties voor het laden van binaire Spreadsheet (Cells, Excel‑compatibel)
documenten zoals XLS(X), ODS enz. in de Editor‑klasse

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Standaard parameterloze constructor - alle parameters hebben standaardwaarden |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor |
het openen van het Spreadsheet‑document, indien het gecodeerd is.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor |
het openen van het Spreadsheet‑document, indien het gecodeerd is.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Schakelt geheugenoptimalisatiemechanismen in tijdens de verwerking van het invoerdocument, |
wat de prestaties in sommige speciale gevallen kan verminderen, maar aan de andere kant
handmatig geheugenverbruik verminderen.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Schakelt geheugenoptimalisatiemechanismen in tijdens de verwerking van het invoerdocument, |
wat de prestaties in sommige speciale gevallen kan verminderen, maar aan de andere kant
handmatig geheugenverbruik verminderen.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Standaard parameterloze constructor - alle parameters hebben standaardwaarden


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor
het openen van het Spreadsheet-document, indien gecodeerd. Stel in op NULL of leeg
string om het wachtwoord niet te gebruiken (standaardwaarde).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor
het openen van het Spreadsheet-document, indien gecodeerd. Stel in op NULL of leeg
string om het wachtwoord niet te gebruiken (standaardwaarde).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Schakelt geheugenoptimalisatiemechanismen in tijdens de verwerking van het invoerdocument,
wat de prestaties in sommige speciale gevallen kan verminderen, maar aan de andere kant
handmatig geheugenverbruik verminderen. Handig bij het verwerken van enorme documenten en
bij een OutOfMemoryException. Standaard is false (geheugenoptimalisatie is
uitgeschakeld voor betere prestaties).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Schakelt geheugenoptimalisatiemechanismen in tijdens de verwerking van het invoerdocument,
wat de prestaties in sommige speciale gevallen kan verminderen, maar aan de andere kant
handmatig geheugenverbruik verminderen. Handig bij het verwerken van enorme documenten en
bij een OutOfMemoryException. Standaard is false (geheugenoptimalisatie is
uitgeschakeld voor betere prestaties).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

