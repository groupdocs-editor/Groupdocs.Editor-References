---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von einfachen Text-​TXT-​Dokumenten"
type: docs
weight: 41
url: /de/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von einfachem Text (TXT)
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
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Gibt an, ob bi-​directionale Markierungen vor jedem BiDi-​Durchlauf hinzugefügt werden sollen, wenn |
Exportieren im einfachen Textformat.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Gibt an, ob bi-​directionale Markierungen vor jedem BiDi-​Durchlauf hinzugefügt werden sollen, wenn |
Exportieren im einfachen Textformat
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Gibt an, ob das Programm versuchen soll, das Layout von Tabellen beizubehalten |
beim Speichern im einfachen Textformat.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Gibt an, ob das Programm versuchen soll, das Layout von Tabellen beizubehalten |
beim Speichern im einfachen Textformat.
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


Gibt an, ob bi-​directionale Markierungen vor jedem BiDi-​Durchlauf hinzugefügt werden sollen, wenn
Exportieren im einfachen Textformat. Standard ist 'false' \u2014 keine BiDi-​Markierungen hinzufügen.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Gibt an, ob bi-​directionale Markierungen vor jedem BiDi-​Durchlauf hinzugefügt werden sollen, wenn
Exportieren im einfachen Textformat


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Gibt an, ob das Programm versuchen soll, das Layout von Tabellen beizubehalten
beim Speichern im einfachen Textformat. Der Standardwert ist false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Gibt an, ob das Programm versuchen soll, das Layout von Tabellen beizubehalten
beim Speichern im einfachen Textformat. Der Standardwert ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

