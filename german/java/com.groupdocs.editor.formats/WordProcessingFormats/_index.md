---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Kapselt alle Textverarbeitungsformate."
type: docs
weight: 17
url: /de/java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

Kapselt alle WordProcessing-Formate. Enthält die folgenden Dateitypen:
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
Erfahren Sie mehr über Word‑Processing‑Formate [hier](../https://wiki.fileformat.com/word-processing).

MIME-Codes werden aus den angegebenen Ressourcen entnommen:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Doc](#Doc) | Das MS‑Word‑97‑2007‑Binärdateiformat (DOC) stellt Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärformat erzeugt werden. |
|
|  | [Docx](#Docx) | Das Office Open XML WordProcessingML Makrofrei‑Dokument (DOCX) ist ein bekanntes Format für Microsoft‑Word‑Dokumente. |
|
|  | [Dot](#Dot) | MS‑Word‑97‑2007‑Vorlage (DOT) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vordefinierte Einstellungen für die Erstellung weiterer DOC‑ oder DOCX‑Dateien zu besitzen. |
|
|  | [Docm](#Docm) | Office Open XML WordProcessingML Makro‑aktiviertes Dokument (DOCM)‑Dateien sind von Microsoft Word 2007 oder höher erzeugte Dokumente mit der Möglichkeit, Makros auszuführen. |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML Makrofrei‑Vorlage (DOTX) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vordefinierte Einstellungen für die Erstellung weiterer DOCX‑Dateien zu besitzen. |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML Makro‑aktivierte Vorlage (DOTM) stellt Vorlagendateien dar, die mit Microsoft Word 2007 oder höher erstellt wurden. |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML wird in einer flachen XML‑Datei anstelle eines ZIP‑Pakets gespeichert. |
|
|  | [Rtf](#Rtf) | Rich Text Format (RTF) stellt eine Methode zur Kodierung von formatiertem Text und Grafiken für die Verwendung in Anwendungen dar. |
|
|  | [Odt](#Odt) | Open Document Format Textdokumente (ODT) sind Dokumente, die mit Textverarbeitungsprogrammen erstellt werden und auf dem OpenDocument‑Textdateiformat basieren. |
|
|  | [Ott](#Ott) | Open Document Format Textdokumentvorlagen (OTT) stellen Vorlagendokumente dar, die von Anwendungen gemäß dem OASIS‑OpenDocument‑Standardformat erzeugt werden. |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML‑Format — WordProcessingML oder WordML (.XML). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAll()](#getAll--) | Gibt eine aufzählbare Sammlung aller [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) zurück. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ruft eine Instanz des angegebenen Typs [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) ab, die die angegebene Dateierweiterung besitzt. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konvertiert eine Zeichenkette, die eine Dateierweiterung darstellt, in ein [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)‑Objekt. |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


Das MS‑Word‑97‑2007‑Binärdateiformat (DOC) stellt Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärformat erzeugt werden.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Das Office Open XML WordProcessingML Makrofrei‑Dokument (DOCX) ist ein bekanntes Format für Microsoft‑Word‑Dokumente.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS‑Word‑97‑2007‑Vorlage (DOT) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vordefinierte Einstellungen für die Erstellung weiterer DOC‑ oder DOCX‑Dateien zu besitzen.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Office Open XML WordProcessingML Makro‑aktiviertes Dokument (DOCM)‑Dateien sind von Microsoft Word 2007 oder höher erzeugte Dokumente mit der Möglichkeit, Makros auszuführen.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML Makrofrei‑Vorlage (DOTX) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vordefinierte Einstellungen für die Erstellung weiterer DOCX‑Dateien zu besitzen.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML Makro‑aktivierte Vorlage (DOTM) stellt Vorlagendateien dar, die mit Microsoft Word 2007 oder höher erstellt wurden.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML wird in einer flachen XML‑Datei anstelle eines ZIP‑Pakets gespeichert.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format (RTF) stellt eine Methode zur Kodierung von formatiertem Text und Grafiken für die Verwendung in Anwendungen dar.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Open Document Format Textdokumente (ODT) sind Dokumente, die mit Textverarbeitungsprogrammen erstellt werden und auf dem OpenDocument‑Textdateiformat basieren.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format Textdokumentvorlagen (OTT) stellen Vorlagendokumente dar, die von Anwendungen gemäß dem OASIS‑OpenDocument‑Standardformat erzeugt werden.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML‑Format — WordProcessingML oder WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


Gibt eine aufzählbare Sammlung aller [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) zurück.
Wert: Ein IEnumerable{WordProcessingFormats}, das alle Instanzen von [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) enthält.


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


Ruft eine Instanz des angegebenen Typs [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) ab, die die angegebene Dateierweiterung besitzt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung des Dokumentformats. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


Konvertiert eine Zeichenkette, die eine Dateierweiterung darstellt, in ein [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)‑Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung zum Konvertieren. Wenn die Erweiterung mehrere Punkte enthält, wird der Teil nach dem letzten Punkt verwendet. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

