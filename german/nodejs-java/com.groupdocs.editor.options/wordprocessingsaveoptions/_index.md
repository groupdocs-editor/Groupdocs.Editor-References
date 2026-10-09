---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von WordProcessing‑konformen Dokumenten, nachdem sie bearbeitet wurden."
type: docs
weight: 48
url: /de/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern
WordProcessing‑konforme Dokumente, nachdem sie bearbeitet wurden


*** ** * ** ***

WordProcessingSaveOptions wird in Situationen angewendet, in denen eine Instanz der Klasse EditableDocument vorhanden ist, die den Inhalt eines bearbeiteten Dokuments enthält, und dieser Inhalt in ein neues Dokument im WordProcessing‑Format gespeichert werden muss.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Dieser parameterlose Konstruktor erstellt eine neue Instanz von WordProcessingSaveOptions mit dem DOCX‑Ausgabeformat (kann anschließend über |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) Eigenschaft)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Erstellt eine neue Instanz von WordProcessingSaveOptions mit dem angegebenen |
obligatorischen WordProcessing‑Ausgabeformat, während alle anderen Parameter
Standard
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung, die zum Speichern verwendet wird |
Dokument.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung, die zum Speichern verwendet wird |
Dokument.
|
|  | [getPassword()](#getPassword--) | Ermöglicht das Festlegen, Ändern, Abrufen oder Entfernen eines Passworts, das |
verwendet, um das erzeugte WordProcessing-Dokument zu codieren.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ermöglicht das Festlegen, Ändern, Abrufen oder Entfernen eines Passworts, das |
verwendet, um das erzeugte WordProcessing-Dokument zu codieren.
|
|  | [getOutputFormat()](#getOutputFormat--) | Ermöglicht das Festlegen eines WordProcessing-Formats, das zum Speichern verwendet wird |
das Dokument
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Ermöglicht das Festlegen eines WordProcessing-Formats, das zum Speichern verwendet wird |
das Dokument
|
|  | [getLocale()](#getLocale--) | Ermöglicht das Überschreiben der Standard-Lokalisierung (Sprache) für das WordProcessing |
Dokument, das während seiner Erstellung angewendet wird.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Ermöglicht das Überschreiben der Standard-Lokalisierung (Sprache) für das WordProcessing |
Dokument, das während seiner Erstellung angewendet wird.
|
|  | [getLocaleBi()](#getLocaleBi--) | Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument |
für den RTL (Right-to-Left)-Text, der während seiner
Erstellung.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument |
für den RTL (Right-to-Left)-Text, der während seiner
Erstellung.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument |
für den ostasiatischen Text, der während seiner Erstellung angewendet wird.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument |
für den ostasiatischen Text, der während seiner Erstellung angewendet wird.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus |
HTML, was die Leistung mindert, als Preis für die Verringerung des Speicherverbrauchs.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus |
HTML, was die Leistung mindert, als Preis für die Verringerung des Speicherverbrauchs.
|
|  | [getProtection()](#getProtection--) | Ermöglicht das Steuern und Anwenden der Dokumentenschutzoptionen für das |
WordProcessing-Dokument eines beliebigen Formats, das Dokument
schutz unterstützt.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Ermöglicht das Steuern und Anwenden der Dokumentenschutzoptionen für das |
WordProcessing-Dokument eines beliebigen Formats, das Dokument
schutz unterstützt.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Verantwortlich für das Einbetten von Schriftartressourcen in das Ausgabe-WordProcessing |
Dokument.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Verantwortlich für das Einbetten von Schriftartressourcen in das Ausgabe-WordProcessing |
Dokument.
|
|  | [deepClone()](#deepClone--) | Erstellt und gibt eine vollständige Kopie dieser Instanz von |
WordProcessingSaveOptions-Klasse
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Dieser parameterlose Konstruktor erstellt eine neue Instanz von WordProcessingSaveOptions mit dem DOCX‑Ausgabeformat (kann anschließend über
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) Eigenschaft)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Erstellt eine neue Instanz von WordProcessingSaveOptions mit dem angegebenen
obligatorischen WordProcessing‑Ausgabeformat, während alle anderen Parameter
Standard


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Erforderliches Ausgabeformat, in dem das WordProcessing-Dokument gespeichert werden soll |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung, die zum Speichern verwendet wird
Dokument. Wenn das Originaldokument im Seitennummerierungsmodus geöffnet und bearbeitet wurde
Modus, sollte diese Option ebenfalls aktiviert werden. Standardmäßig ist sie deaktiviert.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung, die zum Speichern verwendet wird
Dokument. Wenn das Originaldokument im Seitennummerierungsmodus geöffnet und bearbeitet wurde
Modus, sollte diese Option ebenfalls aktiviert werden. Standardmäßig ist sie deaktiviert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermöglicht das Festlegen, Ändern, Abrufen oder Entfernen eines Passworts, das
verwendet, um das erzeugte WordProcessing-Dokument zu codieren. Geben Sie NULL oder
eine leere Zeichenkette zum Entfernen (Bereinigen) des Passworts an.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ermöglicht das Festlegen, Ändern, Abrufen oder Entfernen eines Passworts, das
verwendet, um das erzeugte WordProcessing-Dokument zu codieren. Geben Sie NULL oder
eine leere Zeichenkette zum Entfernen (Bereinigen) des Passworts an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Ermöglicht das Festlegen eines WordProcessing-Formats, das zum Speichern verwendet wird
das Dokument


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Ermöglicht das Festlegen eines WordProcessing-Formats, das zum Speichern verwendet wird
das Dokument


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Ermöglicht das Überschreiben der Standard-Lokalisierung (Sprache) für das WordProcessing
Dokument, das während seiner Erstellung angewendet wird. Wenn es nicht
angegeben (Standardwert), MS Word (oder ein anderes Programm) wird erkennen (oder
auswählen) die Dokumentsprache gemäß seiner eigenen Einstellungen oder anderen
Faktoren.


*** ** * ** ***

Diese Option wendet die angegebene Sprache zwangsweise auf den gesamten Text im Dokument an. Verwenden Sie sie nicht, wenn das Dokument verschiedene Textteile enthält, die in unterschiedlichen Sprachen geschrieben sind.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Ermöglicht das Überschreiben der Standard-Lokalisierung (Sprache) für das WordProcessing
Dokument, das während seiner Erstellung angewendet wird. Wenn es nicht
angegeben (Standardwert), MS Word (oder ein anderes Programm) wird erkennen (oder
auswählen) die Dokumentsprache gemäß seiner eigenen Einstellungen oder anderen
Faktoren.

*** ** * ** ***


Diese Option wendet die angegebene Sprache zwangsweise auf den gesamten Text in
dem Dokument an. Verwenden Sie sie nicht, wenn das Dokument verschiedene Teile von
Text, der in unterschiedlichen Sprachen geschrieben ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument
für den RTL (Right-to-Left)-Text, der während seiner
Erstellung. Wenn nicht angegeben (Standardwert), MS Word (oder ein anderes
Programm) wird die RTL-Sprache des Dokuments erkennen (oder auswählen) gemäß seiner
eigenen Einstellungen oder anderen Faktoren.

*** ** * ** ***


Diese Option wendet die angegebene Sprache zwangsweise auf den gesamten RTL-Text an
im Dokument an. Verwenden Sie sie nicht, wenn das Dokument verschiedene Teile von
Text, der in unterschiedlichen Sprachen geschrieben ist.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument
für den RTL (Right-to-Left)-Text, der während seiner
Erstellung. Wenn nicht angegeben (Standardwert), MS Word (oder ein anderes
Programm) wird die RTL-Sprache des Dokuments erkennen (oder auswählen) gemäß seiner
eigenen Einstellungen oder anderen Faktoren.

*** ** * ** ***


Diese Option wendet die angegebene Sprache zwangsweise auf den gesamten RTL-Text an
im Dokument an. Verwenden Sie sie nicht, wenn das Dokument verschiedene Teile von
Text, der in unterschiedlichen Sprachen geschrieben ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument
für den ostasiatischen Text, der während seiner Erstellung angewendet wird. Wenn
nicht angegeben ist (Standardwert), MS Word (oder ein anderes Programm) wird erkennen
(oder auswählen) die ostasiatische Sprache des Dokuments gemäß seiner eigenen Einstellungen
oder anderen Faktoren.

*** ** * ** ***


Diese Option wendet die angegebene Sprache zwangsweise auf den gesamten
ostasiatischen Text im Dokument an. Verwenden Sie sie nicht, wenn das Dokument enthält
verschiedene Textteile, die in unterschiedlichen
Sprachen.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument
für den ostasiatischen Text, der während seiner Erstellung angewendet wird. Wenn
nicht angegeben ist (Standardwert), MS Word (oder ein anderes Programm) wird erkennen
(oder auswählen) die ostasiatische Sprache des Dokuments gemäß seiner eigenen Einstellungen
oder anderen Faktoren.

*** ** * ** ***


Diese Option wendet die angegebene Sprache zwangsweise auf den gesamten
ostasiatischen Text im Dokument an. Verwenden Sie sie nicht, wenn das Dokument enthält
verschiedene Textteile, die in unterschiedlichen
Sprachen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus
HTML, was die Leistung mindert, als Preis für die Verringerung des Speicherverbrauchs.
Das Aktivieren dieser Option kann den Speicherverbrauch erheblich reduzieren
während der Erstellung großer Dokumente, jedoch auf Kosten einer langsameren Speicherzeit.
Standard ist false (Speicheroptimierung ist deaktiviert, um bessere
Leistung).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus
HTML, was die Leistung mindert, als Preis für die Verringerung des Speicherverbrauchs.
Das Aktivieren dieser Option kann den Speicherverbrauch erheblich reduzieren
während der Erstellung großer Dokumente, jedoch auf Kosten einer langsameren Speicherzeit.
Standard ist false (Speicheroptimierung ist deaktiviert, um bessere
Leistung).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Ermöglicht das Steuern und Anwenden der Dokumentenschutzoptionen für das
WordProcessing-Dokument eines beliebigen Formats, das Dokument
Schutz. Standard ist NULL - Dokumentenschutz wird nicht verwendet.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Ermöglicht das Steuern und Anwenden der Dokumentenschutzoptionen für das
WordProcessing-Dokument eines beliebigen Formats, das Dokument
Schutz. Standard ist NULL - Dokumentenschutz wird nicht verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Verantwortlich für das Einbetten von Schriftartressourcen in das Ausgabe-WordProcessing
Dokument. Standard bettet keine Schriftarten ein (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Verantwortlich für das Einbetten von Schriftartressourcen in das Ausgabe-WordProcessing
Dokument. Standard bettet keine Schriftarten ein (NotEmbed).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Erstellt und gibt eine vollständige Kopie dieser Instanz von
WordProcessingSaveOptions-Klasse


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

