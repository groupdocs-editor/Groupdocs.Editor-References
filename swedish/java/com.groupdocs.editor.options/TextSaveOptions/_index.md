---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara enkla TXT‑textdokument"
type: docs
weight: 41
url: /sv/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Tillåter att ange anpassade alternativ för att generera och spara enkel text (TXT)
dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Teckenkodning för textdokumentet, som kommer att tillämpas för dess |
sparande
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Teckenkodning för textdokumentet, som kommer att tillämpas för dess |
sparande
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Anger om bi‑direktionella markeringar ska läggas till före varje BiDi‑sekvens när |
exporteras i enkelt textformat.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Anger om bi‑direktionella markeringar ska läggas till före varje BiDi‑sekvens när |
exporteras i enkelt textformat
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Anger om programmet ska försöka bevara tabellernas layout |
vid sparande i enkelt textformat.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Anger om programmet ska försöka bevara tabellernas layout |
vid sparande i enkelt textformat.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Teckenkodning för textdokumentet, som kommer att tillämpas för dess
sparande


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Teckenkodning för textdokumentet, som kommer att tillämpas för dess
sparande


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Anger om bi‑direktionella markeringar ska läggas till före varje BiDi‑sekvens när
exporteras i enkelt textformat. Standard är 'false' \\u2014 lägg inte till BiDi‑markeringar.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Anger om bi‑direktionella markeringar ska läggas till före varje BiDi‑sekvens när
exporteras i enkelt textformat


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Anger om programmet ska försöka bevara tabellernas layout
vid sparande i enkelt textformat. Standardvärdet är false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Anger om programmet ska försöka bevara tabellernas layout
vid sparande i enkelt textformat. Standardvärdet är false.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

