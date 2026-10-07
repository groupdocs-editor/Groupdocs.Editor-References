---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Opties voor het laden van tekstgebaseerde Spreadsheet-documenten CSV Tab-gebaseerd enz. die een scheidingsteken (delimiter) gebruiken"
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Opties voor het laden van tekstgebaseerde Spreadsheet-documenten (CSV, Tab-gebaseerd enz.),
die een scheidingsteken (delimiter) gebruiken


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Maakt een instantie van de optiesklasse voor gescheiden tekst met verplichte |
scheidingsteken (delimiter)
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Staat toe een tekenreeks scheidingsteken (delimiter) op te geven voor tekstgebaseerde |
Spreadsheet-documenten
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Staat toe een tekenreeks scheidingsteken (delimiter) op te geven voor tekstgebaseerde |
Spreadsheet-documenten
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Haalt op of stelt een waarde in die aangeeft of de tekenreeks in tekstgebaseerde |
document wordt geconverteerd naar datumgegevens.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Haalt op of stelt een waarde in die aangeeft of de tekenreeks in tekstgebaseerde |
document wordt geconverteerd naar datumgegevens.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Haalt op of stelt een waarde in die aangeeft of de tekenreeks in tekstgebaseerde |
document wordt geconverteerd naar numerieke gegevens.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Haalt op of stelt een waarde in die aangeeft of de tekenreeks in tekstgebaseerde |
document wordt geconverteerd naar numerieke gegevens.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Definieert of opeenvolgende delimiters als één moeten worden behandeld. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Definieert of opeenvolgende delimiters als één moeten worden behandeld. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Schakelt geheugenoptimalisatiemechanismen in tijdens de verwerking van het invoerdocument, |
wat de prestaties in sommige speciale gevallen kan verminderen, maar aan de andere kant
handmatig geheugenverbruik verminderen.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Schakelt geheugenoptimalisatiemechanismen in tijdens de verwerking van het invoerdocument, |
wat de prestaties in sommige speciale gevallen kan verminderen, maar aan de andere kant
handmatig geheugenverbruik verminderen.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Maakt een instantie van de optiesklasse voor gescheiden tekst met verplichte
scheidingsteken (delimiter)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | scheidingsteken | java.lang.String | Verplichte scheidingsteken (delimiter), die niet NULL of leeg mag zijn |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Staat toe een tekenreeks scheidingsteken (delimiter) op te geven voor tekstgebaseerde
Spreadsheet-documenten


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Staat toe een tekenreeks scheidingsteken (delimiter) op te geven voor tekstgebaseerde
Spreadsheet-documenten


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Haalt op of stelt een waarde in die aangeeft of de tekenreeks in tekstgebaseerde
document wordt geconverteerd naar datumgegevens. Standaard is false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of de tekenreeks in tekstgebaseerde
document wordt geconverteerd naar datumgegevens. Standaard is false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Haalt op of stelt een waarde in die aangeeft of de tekenreeks in tekstgebaseerde
document wordt geconverteerd naar numerieke gegevens. Standaard is false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of de tekenreeks in tekstgebaseerde
document wordt geconverteerd naar numerieke gegevens. Standaard is false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Definieert of opeenvolgende delimiters als één moeten worden behandeld. Door
standaard is false.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Definieert of opeenvolgende delimiters als één moeten worden behandeld. Door
standaard is false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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

