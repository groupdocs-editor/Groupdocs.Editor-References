---
title: "TextEditOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Festlegen benutzerdefinierter Optionen zum Laden von einfachen Text‑TXT‑Dokumenten"
type: docs
weight: 39
url: /de/nodejs-java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Laden von plain text (TXT) Dokumenten

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Zeichencodierung des Textdokuments, die für dessen |
Öffnen
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Zeichencodierung des Textdokuments, die für dessen |
Öffnen
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Ermöglicht die Angabe, wie nummerierte Listenelemente erkannt werden, wenn das Dokument |
aus einem einfachen Textformat importiert wird.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Ermöglicht die Angabe, wie nummerierte Listenelemente erkannt werden, wenn das Dokument |
aus einem einfachen Textformat importiert wird.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Liest oder setzt die bevorzugte Option für die Behandlung von führenden Leerzeichen. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Liest oder setzt die bevorzugte Option für die Behandlung von führenden Leerzeichen. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Liest oder setzt die bevorzugte Option für die Behandlung von nachfolgenden Leerzeichen. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Liest oder setzt die bevorzugte Option für die Behandlung von nachfolgenden Leerzeichen. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [getDirection()](#getDirection--) | Ermöglicht die Angabe der Fließrichtung des Textes im Eingabe‑Plain‑Text |
Dokument.
|
|  | [setDirection(int value)](#setDirection-int-) | Ermöglicht die Angabe der Fließrichtung des Textes im Eingabe‑Plain‑Text |
Dokument.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Zeichencodierung des Textdokuments, die für dessen
Öffnen


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Zeichencodierung des Textdokuments, die für dessen
Öffnen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Ermöglicht die Angabe, wie nummerierte Listenelemente erkannt werden, wenn das Dokument
aus dem Plain‑Text‑Format importiert. Der Standardwert ist true.


*** ** * ** ***

Wenn diese Option auf false gesetzt ist, erkennt der Listen‑Erkennungsalgorithmus Listenkapitel, wenn Listennummern entweder mit einem Punkt, einer rechten Klammer oder Aufzählungssymbolen (wie \"\\u2022\", \"\*\", \"-\" oder \"o\") enden. Wenn diese Option auf true gesetzt ist, werden Leerzeichen ebenfalls als Trennzeichen für Listennummern verwendet: Der Listen‑Erkennungsalgorithmus für arabische Nummerierung (1., 1.1.2.) verwendet sowohl Leerzeichen als auch Punkt‑(\".\")‑Symbole.

<br />



**Returns:**
boolesch
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Ermöglicht die Angabe, wie nummerierte Listenelemente erkannt werden, wenn das Dokument
aus dem Plain‑Text‑Format importiert. Der Standardwert ist true.


*** ** * ** ***

Wenn diese Option auf false gesetzt ist, erkennt der Listen‑Erkennungsalgorithmus Listenkapitel, wenn Listennummern entweder mit einem Punkt, einer rechten Klammer oder Aufzählungssymbolen (wie \"\\u2022\", \"\*\", \"-\" oder \"o\") enden. Wenn diese Option auf true gesetzt ist, werden Leerzeichen ebenfalls als Trennzeichen für Listennummern verwendet: Der Listen‑Erkennungsalgorithmus für arabische Nummerierung (1., 1.1.2.) verwendet sowohl Leerzeichen als auch Punkt‑(\".\")‑Symbole.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Liest oder setzt die bevorzugte Option für die Behandlung von führenden Leerzeichen. Standardmäßig
wandelt führende Leerzeichen in den linken Einzug um.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Liest oder setzt die bevorzugte Option für die Behandlung von führenden Leerzeichen. Standardmäßig
wandelt führende Leerzeichen in den linken Einzug um.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Liest oder setzt die bevorzugte Option für die Behandlung von nachgestellten Leerzeichen. Standardmäßig
schneidet alle nachgestellten Leerzeichen ab.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Liest oder setzt die bevorzugte Option für die Behandlung von nachgestellten Leerzeichen. Standardmäßig
schneidet alle nachgestellten Leerzeichen ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. Durch
Standard ist deaktiviert (false).


**Returns:**
boolesch
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung im resultierenden HTML-Dokument. Durch
Standard ist deaktiviert (false).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Ermöglicht die Angabe der Fließrichtung des Textes im Eingabe‑Plain‑Text
Dokument. Standardmäßig ist es von links nach rechts.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Ermöglicht die Angabe der Fließrichtung des Textes im Eingabe‑Plain‑Text
Dokument. Standardmäßig ist es von links nach rechts.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

