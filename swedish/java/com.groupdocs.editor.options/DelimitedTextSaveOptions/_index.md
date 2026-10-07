---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Innehåller alternativ för att generera och spara textbaserade kalkylbladsdokument CSV, tab‑baserade etc. som använder ett avgränsartecken"
type: docs
weight: 11
url: /sv/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Innehåller alternativ för att generera och spara textbaserade kalkylbladsdokument
(CSV, tab‑baserade etc.), som använder ett avgränsartecken (separator)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Denna parameterlösa konstruktor skapar en ny instans av DelimitedTextSaveOptions med ett semikolon (;) som standardavgränsare (kan sedan ändras via |
Separator
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) property)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Skapar en instans av alternativklassen för avgränsad text med obligatorisk |
separator (avgränsare)
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Tillåter att ange en strängseparator (avgränsare) för textbaserade |
Kalkylbladsdokument
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Tillåter att ange en strängseparator (avgränsare) för textbaserade |
Kalkylbladsdokument
|
|  | [getEncoding()](#getEncoding--) | Tillåter att ange en kodning för det textbaserade kalkylbladsdokumentet. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Tillåter att ange en kodning för det textbaserade kalkylbladsdokumentet. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Anger om inledande tomma rader och kolumner ska trimmas som |
vad MS Excel gör
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Anger om inledande tomma rader och kolumner ska trimmas som |
vad MS Excel gör
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Anger om separatorer ska skrivas ut för tom rad. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Anger om separatorer ska skrivas ut för tom rad. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Denna parameterlösa konstruktor skapar en ny instans av DelimitedTextSaveOptions med ett semikolon (;) som standardavgränsare (kan sedan ändras via
Separator
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) property)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Skapar en instans av alternativklassen för avgränsad text med obligatorisk
separator (avgränsare)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | separator | java.lang.String | Strängseparator (avgränsare) för textbaserade kalkylbladsdokument |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Tillåter att ange en strängseparator (avgränsare) för textbaserade
Kalkylbladsdokument


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Tillåter att ange en strängseparator (avgränsare) för textbaserade
Kalkylbladsdokument


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Tillåter att ange en kodning för det textbaserade kalkylbladsdokumentet. Genom
standard (och om den inte specificeras) är UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Tillåter att ange en kodning för det textbaserade kalkylbladsdokumentet. Genom
standard (och om den inte specificeras) är UTF8.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Anger om inledande tomma rader och kolumner ska trimmas som
vad MS Excel gör


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Anger om inledande tomma rader och kolumner ska trimmas som
vad MS Excel gör


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Anger om separatorer ska skrivas ut för tom rad. Standard
värdet är falskt vilket betyder att innehållet för tom rad blir tomt.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Anger om separatorer ska skrivas ut för tom rad. Standard
värdet är falskt vilket betyder att innehållet för tom rad blir tomt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

