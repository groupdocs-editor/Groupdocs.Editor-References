---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het genereren en opslaan van platte‑tekst TXT‑documenten"
type: docs
weight: 41
url: /nl/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Staat toe aangepaste opties op te geven voor het genereren en opslaan van platte‑tekst (TXT)
documenten

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Tekencodering van het tekstdocument, die zal worden toegepast op zijn |
opslaan
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Tekencodering van het tekstdocument, die zal worden toegepast op zijn |
opslaan
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Specificeert of bi‑directionele markeringen vóór elke BiDi‑run moeten worden toegevoegd wanneer |
exporteren in platte‑tekstformaat.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Specificeert of bi‑directionele markeringen vóór elke BiDi‑run moeten worden toegevoegd wanneer |
exporteren in platte‑tekstformaat
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Specificeert of het programma moet proberen de lay-out van tabellen te behouden |
bij het opslaan in het platte‑tekstformaat.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Specificeert of het programma moet proberen de lay-out van tabellen te behouden |
bij het opslaan in het platte‑tekstformaat.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Tekencodering van het tekstdocument, die zal worden toegepast op zijn
opslaan


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Tekencodering van het tekstdocument, die zal worden toegepast op zijn
opslaan


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Specificeert of bi‑directionele markeringen vóór elke BiDi‑run moeten worden toegevoegd wanneer
exporteren in platte‑tekstformaat. Standaard is 'false' \\u2014 geen BiDi‑markeringen toevoegen.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Specificeert of bi‑directionele markeringen vóór elke BiDi‑run moeten worden toegevoegd wanneer
exporteren in platte‑tekstformaat


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Specificeert of het programma moet proberen de lay-out van tabellen te behouden
bij het opslaan in het platte‑tekstformaat. De standaardwaarde is false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Specificeert of het programma moet proberen de lay-out van tabellen te behouden
bij het opslaan in het platte‑tekstformaat. De standaardwaarde is false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

