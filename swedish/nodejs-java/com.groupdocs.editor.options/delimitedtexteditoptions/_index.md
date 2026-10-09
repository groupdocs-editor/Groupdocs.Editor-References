---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Alternativ för att läsa in textbaserade kalkylbladsdokument (CSV, tabbaserade etc.) som använder en separator/avgränsare"
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Alternativ för att läsa in textbaserade kalkylbladsdokument (CSV, tabbaserade etc.),
som använder en separator (avgränsare)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Skapar en instans av alternativklassen för avgränsad text med obligatorisk |
separator (avgränsare)
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Tillåter att ange en strängseparator (avgränsare) för textbaserad |
Kalkylbladsdokument
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Tillåter att ange en strängseparator (avgränsare) för textbaserad |
Kalkylbladsdokument
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Hämtar eller anger ett värde som indikerar om strängen i textbaserade |
dokumentet konverteras till datumdata.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Hämtar eller anger ett värde som indikerar om strängen i textbaserade |
dokumentet konverteras till datumdata.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Hämtar eller anger ett värde som indikerar om strängen i textbaserade |
dokumentet konverteras till numerisk data.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Hämtar eller anger ett värde som indikerar om strängen i textbaserade |
dokumentet konverteras till numerisk data.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Definierar om på varandra följande avgränsare ska behandlas som en. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Definierar om på varandra följande avgränsare ska behandlas som en. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument, |
vilket kan försämra prestanda i vissa speciella fall, men å andra
sidan minskar minnesanvändningen.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument, |
vilket kan försämra prestanda i vissa speciella fall, men å andra
sidan minskar minnesanvändningen.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Skapar en instans av alternativklassen för avgränsad text med obligatorisk
separator (avgränsare)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | avgränsare | java.lang.String | Obligatorisk separator (avgränsare) som inte kan vara NULL eller tom |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Tillåter att ange en strängseparator (avgränsare) för textbaserad
Kalkylbladsdokument


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Tillåter att ange en strängseparator (avgränsare) för textbaserad
Kalkylbladsdokument


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Hämtar eller anger ett värde som indikerar om strängen i textbaserade
dokumentet konverteras till datumdata. Standard är falskt.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Hämtar eller anger ett värde som indikerar om strängen i textbaserade
dokumentet konverteras till datumdata. Standard är falskt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Hämtar eller anger ett värde som indikerar om strängen i textbaserade
dokumentet konverteras till numerisk data. Standard är falskt.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Hämtar eller anger ett värde som indikerar om strängen i textbaserade
dokumentet konverteras till numerisk data. Standard är falskt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Definierar om på varandra följande avgränsare ska behandlas som en. Genom
standard är falskt.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Definierar om på varandra följande avgränsare ska behandlas som en. Genom
standard är falskt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument,
vilket kan försämra prestanda i vissa speciella fall, men å andra
sidan minskar minnesanvändningen. Användbart vid bearbetning av stora dokument och
vid ett OutOfMemoryException. Standard är falskt (minnesoptimering är
inaktiverad för att uppnå bättre prestanda).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument,
vilket kan försämra prestanda i vissa speciella fall, men å andra
sidan minskar minnesanvändningen. Användbart vid bearbetning av stora dokument och
vid ett OutOfMemoryException. Standard är falskt (minnesoptimering är
inaktiverad för att uppnå bättre prestanda).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

