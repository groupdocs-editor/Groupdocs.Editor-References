---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von Klartext-TXT-Dokumenten"
type: docs
weight: 41
url: /de/nodejs-java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von Klartext (TXT)
Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Zeichencodierung des Textdokuments, die für dessen |
Speichern
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Zeichencodierung des Textdokuments, die für dessen |
Speichern
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Gibt an, ob bidirektionale Markierungen vor jedem BiDi-Durchlauf hinzugefügt werden sollen, wenn |
Exportieren im Klartextformat.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Gibt an, ob bidirektionale Markierungen vor jedem BiDi-Durchlauf hinzugefügt werden sollen, wenn |
Exportieren im Klartextformat
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Gibt an, ob das Programm versuchen soll, das Layout von Tabellen beizubehalten |
beim Speichern im Nur-Text-Format.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Gibt an, ob das Programm versuchen soll, das Layout von Tabellen beizubehalten |
beim Speichern im Nur-Text-Format.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Zeichencodierung des Textdokuments, die für dessen
Speichern


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Zeichencodierung des Textdokuments, die für dessen
Speichern


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Gibt an, ob bidirektionale Markierungen vor jedem BiDi-Durchlauf hinzugefügt werden sollen, wenn
Exportieren im Nur-Text-Format. Standard ist 'false' \\u2014 keine BiDi-Markierungen hinzufügen.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Gibt an, ob bidirektionale Markierungen vor jedem BiDi-Durchlauf hinzugefügt werden sollen, wenn
Exportieren im Klartextformat


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Gibt an, ob das Programm versuchen soll, das Layout von Tabellen beizubehalten
beim Speichern im Nur-Text-Format. Der Standardwert ist false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Gibt an, ob das Programm versuchen soll, das Layout von Tabellen beizubehalten
beim Speichern im Nur-Text-Format. Der Standardwert ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

