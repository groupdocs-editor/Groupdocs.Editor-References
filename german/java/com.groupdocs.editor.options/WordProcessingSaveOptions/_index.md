---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von WordProcessing-konformen Dokumenten, nachdem sie bearbeitet wurden"
type: docs
weight: 48
url: /de/java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern
WordProcessing-konforme Dokumente, nachdem sie bearbeitet wurden


*** ** * ** ***

WordProcessingSaveOptions wird in Situationen angewendet, in denen eine Instanz der Klasse EditableDocument vorhanden ist, die bearbeitete Dokumentinhalte enthält, und diese Inhalte in ein neues Dokument im WordProcessing-Format gespeichert werden müssen.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Dieser parameterlose Konstruktor erstellt eine neue Instanz von WordProcessingSaveOptions mit dem DOCX-Ausgabeformat (kann anschließend über |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) Eigenschaft)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Erstellt eine neue Instanz von WordProcessingSaveOptions mit angegebenem |
obligatorischem WordProcessing-Ausgabeformat, während alle anderen Parameter
Standard
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung, die beim Speichern des |
Dokuments.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung, die beim Speichern des |
Dokuments.
|
|  | [getPassword()](#getPassword--) | Ermöglicht das Angeben, Ändern, Abrufen oder Entfernen eines Passworts, das |
verwendet wird, um das erzeugte WordProcessing-Dokument zu verschlüsseln.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ermöglicht das Angeben, Ändern, Abrufen oder Entfernen eines Passworts, das |
verwendet wird, um das erzeugte WordProcessing-Dokument zu verschlüsseln.
|
|  | [getOutputFormat()](#getOutputFormat--) | Ermöglicht das Angeben eines WordProcessing-Formats, das zum Speichern verwendet wird |
des Dokuments
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Ermöglicht das Angeben eines WordProcessing-Formats, das zum Speichern verwendet wird |
des Dokuments
|
|  | [getLocale()](#getLocale--) | Ermöglicht das Überschreiben der Standard-Lokalisierung (Sprache) für das WordProcessing |
Dokument, das während seiner Erstellung angewendet wird.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Ermöglicht das Überschreiben der Standard-Lokalisierung (Sprache) für das WordProcessing |
Dokument, das während seiner Erstellung angewendet wird.
|
|  | [getLocaleBi()](#getLocaleBi--) | Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument |
für RTL (right-to-left)-Text, der während seiner
Erstellung angewendet wird.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument |
für RTL (right-to-left)-Text, der während seiner
Erstellung angewendet wird.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument |
für ostasiatischen Text, der während seiner Erstellung angewendet wird.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument |
für ostasiatischen Text, der während seiner Erstellung angewendet wird.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterzeugung aus |
HTML, was die Leistung verringert, als Preis für die Reduzierung des Speicherverbrauchs.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterzeugung aus |
HTML, was die Leistung verringert, als Preis für die Reduzierung des Speicherverbrauchs.
|
|  | [getProtection()](#getProtection--) | Ermöglicht die Steuerung und Anwendung der Dokumentenschutzoptionen für das |
WordProcessing-Dokument eines beliebigen Formats, das Dokumente unterstützt
Schutz.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Ermöglicht die Steuerung und Anwendung der Dokumentenschutzoptionen für das |
WordProcessing-Dokument eines beliebigen Formats, das Dokumente unterstützt
Schutz.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Verantwortlich für das Einbetten von Schriftartressourcen in das ausgegebene WordProcessing |
Dokuments.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Verantwortlich für das Einbetten von Schriftartressourcen in das ausgegebene WordProcessing |
Dokuments.
|
|  | [deepClone()](#deepClone--) | Erstellt und gibt eine vollständige Kopie dieser Instanz von |
WordProcessingSaveOptions-Klasse
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Dieser parameterlose Konstruktor erstellt eine neue Instanz von WordProcessingSaveOptions mit dem DOCX-Ausgabeformat (kann anschließend über
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) Eigenschaft)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Erstellt eine neue Instanz von WordProcessingSaveOptions mit angegebenem
obligatorischem WordProcessing-Ausgabeformat, während alle anderen Parameter
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


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung, die beim Speichern des
Dokument. Wenn das Originaldokument im Paginierungsmodus geöffnet und bearbeitet wurde
Modus, sollte diese Option ebenfalls aktiviert werden. Standardmäßig ist sie deaktiviert.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung, die beim Speichern des
Dokument. Wenn das Originaldokument im Paginierungsmodus geöffnet und bearbeitet wurde
Modus, sollte diese Option ebenfalls aktiviert werden. Standardmäßig ist sie deaktiviert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermöglicht das Angeben, Ändern, Abrufen oder Entfernen eines Passworts, das
Wird verwendet, um das erzeugte WordProcessing-Dokument zu codieren. Geben Sie NULL oder
eine leere Zeichenkette an, um das Passwort zu entfernen (zu bereinigen).


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ermöglicht das Angeben, Ändern, Abrufen oder Entfernen eines Passworts, das
Wird verwendet, um das erzeugte WordProcessing-Dokument zu codieren. Geben Sie NULL oder
eine leere Zeichenkette an, um das Passwort zu entfernen (zu bereinigen).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Ermöglicht das Angeben eines WordProcessing-Formats, das zum Speichern verwendet wird
des Dokuments


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Ermöglicht das Angeben eines WordProcessing-Formats, das zum Speichern verwendet wird
des Dokuments


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
angegeben ist (Standardwert), wird MS Word (oder ein anderes Programm) erkennen (oder
auswählen) die Dokumentlocale gemäß seiner eigenen Einstellungen oder anderen
Faktoren.


*** ** * ** ***

Diese Option wendet die angegebene Locale zwangsweise auf den gesamten Text im Dokument an. Verwenden Sie sie nicht, wenn das Dokument verschiedene Textteile enthält, die in unterschiedlichen Sprachen verfasst sind.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Ermöglicht das Überschreiben der Standard-Lokalisierung (Sprache) für das WordProcessing
Dokument, das während seiner Erstellung angewendet wird. Wenn es nicht
angegeben ist (Standardwert), wird MS Word (oder ein anderes Programm) erkennen (oder
auswählen) die Dokumentlocale gemäß seiner eigenen Einstellungen oder anderen
Faktoren.

*** ** * ** ***


Diese Option wendet die angegebene Locale zwangsweise auf den gesamten Text in
dem Dokument an. Verwenden Sie sie nicht, wenn das Dokument verschiedene Teile von
Text enthält, die in verschiedenen Sprachen geschrieben sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument
für RTL (right-to-left)-Text, der während seiner
Erstellung. Wenn es nicht angegeben ist (Standardwert), wird MS Word (oder ein anderes
Programm) die RTL-Locale des Dokuments gemäß seiner
eigenen Einstellungen oder anderen Faktoren.

*** ** * ** ***


Diese Option wendet die angegebene Locale zwangsweise auf den gesamten RTL-Text an
im Dokument. Verwenden Sie es nicht, wenn das Dokument verschiedene Teile von
Text enthält, die in verschiedenen Sprachen geschrieben sind.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument
für RTL (right-to-left)-Text, der während seiner
Erstellung. Wenn es nicht angegeben ist (Standardwert), wird MS Word (oder ein anderes
Programm) die RTL-Locale des Dokuments gemäß seiner
eigenen Einstellungen oder anderen Faktoren.

*** ** * ** ***


Diese Option wendet die angegebene Locale zwangsweise auf den gesamten RTL-Text an
im Dokument. Verwenden Sie es nicht, wenn das Dokument verschiedene Teile von
Text enthält, die in verschiedenen Sprachen geschrieben sind.


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
ist nicht angegeben (Standardwert), erkennt MS Word (oder ein anderes Programm)
(oder wählt) das ostasiatische Gebietsschema des Dokuments gemäß seiner eigenen Einstellungen
oder andere Faktoren.

*** ** * ** ***


Diese Option wendet das angegebene Gebietsschema zwangsweise auf das gesamte
ostasiatischen Text im Dokument. Verwenden Sie es nicht, wenn das Dokument enthält
verschiedene Teile von Text, die in unterschiedlichen
Sprachen.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Ermöglicht das Überschreiben der Lokalisierung (Sprache) für das WordProcessing-Dokument
für den ostasiatischen Text, der während seiner Erstellung angewendet wird. Wenn
ist nicht angegeben (Standardwert), erkennt MS Word (oder ein anderes Programm)
(oder wählt) das ostasiatische Gebietsschema des Dokuments gemäß seiner eigenen Einstellungen
oder andere Faktoren.

*** ** * ** ***


Diese Option wendet das angegebene Gebietsschema zwangsweise auf das gesamte
ostasiatischen Text im Dokument. Verwenden Sie es nicht, wenn das Dokument enthält
verschiedene Teile von Text, die in unterschiedlichen
Sprachen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterzeugung aus
HTML, was die Leistung verringert, als Preis für die Reduzierung des Speicherverbrauchs.
Das Setzen dieser Option auf true kann den Speicherverbrauch erheblich reduzieren
während große Dokumente erzeugt werden, auf Kosten einer langsameren Speicherzeit.
Standard ist false (Speicheroptimierung ist deaktiviert, um bessere
Leistung).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterzeugung aus
HTML, was die Leistung verringert, als Preis für die Reduzierung des Speicherverbrauchs.
Das Setzen dieser Option auf true kann den Speicherverbrauch erheblich reduzieren
während große Dokumente erzeugt werden, auf Kosten einer langsameren Speicherzeit.
Standard ist false (Speicheroptimierung ist deaktiviert, um bessere
Leistung).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Ermöglicht die Steuerung und Anwendung der Dokumentenschutzoptionen für das
WordProcessing-Dokument eines beliebigen Formats, das Dokumente unterstützt
Schutz. Standard ist NULL – der Dokumentenschutz wird nicht verwendet.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Ermöglicht die Steuerung und Anwendung der Dokumentenschutzoptionen für das
WordProcessing-Dokument eines beliebigen Formats, das Dokumente unterstützt
Schutz. Standard ist NULL – der Dokumentenschutz wird nicht verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Verantwortlich für das Einbetten von Schriftartressourcen in das ausgegebene WordProcessing
Dokument. Standardmäßig werden keine Schriftarten eingebettet (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Verantwortlich für das Einbetten von Schriftartressourcen in das ausgegebene WordProcessing
Dokument. Standardmäßig werden keine Schriftarten eingebettet (NotEmbed).


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

