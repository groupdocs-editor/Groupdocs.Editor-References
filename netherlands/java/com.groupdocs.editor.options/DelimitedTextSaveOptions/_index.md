---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Bevat opties voor het genereren en opslaan van tekstgebaseerde spreadsheet‑documenten zoals CSV, tab‑gebaseerd enz., die een scheidingsteken gebruiken."
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Bevat opties voor het genereren en opslaan van tekstgebaseerde Spreadsheet-documenten
(CSV, Tab-gebaseerd etc.), die een scheidingsteken (delimiter) gebruiken


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Deze parameterloze constructor maakt een nieuw exemplaar van DelimitedTextSaveOptions met een puntkomma (;) als standaard scheidingsteken (kan vervolgens worden aangepast via |
Scheidingsteken
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) eigenschap)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Maakt een instantie van de optiesklasse voor gescheiden tekst met verplichte |
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
|  | [getEncoding()](#getEncoding--) | Staat toe een codering in te stellen voor het tekstgebaseerde Spreadsheet-document. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Staat toe een codering in te stellen voor het tekstgebaseerde Spreadsheet-document. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Geeft aan of leidende lege rijen en kolommen moeten worden bijgesneden zoals |
wat MS Excel doet
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Geeft aan of leidende lege rijen en kolommen moeten worden bijgesneden zoals |
wat MS Excel doet
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Geeft aan of scheidingstekens moeten worden uitgegeven voor lege rijen. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Geeft aan of scheidingstekens moeten worden uitgegeven voor lege rijen. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Deze parameterloze constructor maakt een nieuw exemplaar van DelimitedTextSaveOptions met een puntkomma (;) als standaard scheidingsteken (kan vervolgens worden aangepast via
Scheidingsteken
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) eigenschap)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Maakt een instantie van de optiesklasse voor gescheiden tekst met verplichte
scheidingsteken (delimiter)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | scheidingsteken | java.lang.String | String scheidingsteken (delimiter) voor tekstgebaseerde Spreadsheet-documenten |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Staat toe een tekenreeks scheidingsteken (delimiter) op te geven voor tekstgebaseerde
Spreadsheet-documenten


**Returns:**
java.lang.String -
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

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Staat toe een codering in te stellen voor het tekstgebaseerde Spreadsheet-document. Door
standaard (en indien niet gespecificeerd) is UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Staat toe een codering in te stellen voor het tekstgebaseerde Spreadsheet-document. Door
standaard (en indien niet gespecificeerd) is UTF8.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Geeft aan of leidende lege rijen en kolommen moeten worden bijgesneden zoals
wat MS Excel doet


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Geeft aan of leidende lege rijen en kolommen moeten worden bijgesneden zoals
wat MS Excel doet


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Geeft aan of scheidingstekens moeten worden uitgegeven voor lege rijen. Standaard
waarde is false, wat betekent dat de inhoud voor lege rijen leeg zal zijn.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Geeft aan of scheidingstekens moeten worden uitgegeven voor lege rijen. Standaard
waarde is false, wat betekent dat de inhoud voor lege rijen leeg zal zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

