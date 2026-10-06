---
title: "TextualFormats"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Kapselt alle textbasierten Formate, einschließlich Markup XML HTML und anderer."
type: docs
weight: 16
url: /de/java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Kapselt alle textuellen (textbasierten) Formate, einschließlich Markup (XML, HTML) und anderer.
Enthält die folgenden Formate:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Html](#Html) | HyperText Markup Language-Dokument (HTML) ist die Erweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. |
|
|  | [Xml](#Xml) | eXtensible Markup Language-Dokument (XML), das HTML ähnlich ist, sich jedoch durch die Verwendung von Tags zur Definition von Objekten unterscheidet. |
|
|  | [Txt](#Txt) | Plain Text Document (TXT) stellt ein Textdokument dar, das reinen Text in Form von Zeilen enthält. |
|
|  | [Md](#Md) | Markdown ist eine leichtgewichtige Auszeichnungssprache zum Erstellen von formatiertem Text mit einem Klartext-Editor. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) ist ein offener Standard-Dateiformat zum Austausch von Daten, das menschenlesbaren Text verwendet, um Daten zu speichern und zu übertragen. |
|
|  | [Mhtml](#Mhtml) | MIME-Kapselung aggregierter HTML-Dokumente ist ein Webseitensicherungsformat, das verwendet wird, um in einer einzigen Datei den HTML-Code und zugehörige Ressourcen zu kombinieren. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help ist ein proprietäres Online-Hilfebinärformat von Microsoft, das aus einer Sammlung von HTML-Seiten, einem Index und weiteren Navigationswerkzeugen besteht. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAll()](#getAll--) | Liefert eine aufzählbare Sammlung aller [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ruft eine Instanz des angegebenen Typs [TextualFormats](../../com.groupdocs.editor.formats/textualformats) ab, die die angegebene Dateierweiterung besitzt. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [TextualFormats](../../com.groupdocs.editor.formats/textualformats)-Objekt. |
|
### Html {#Html}
```
public static final TextualFormats Html
```


HyperText Markup Language-Dokument (HTML) ist die Erweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


eXtensible Markup Language-Dokument (XML), das HTML ähnlich ist, sich jedoch durch die Verwendung von Tags zur Definition von Objekten unterscheidet.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Plain Text Document (TXT) stellt ein Textdokument dar, das reinen Text in Form von Zeilen enthält.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown ist eine leichtgewichtige Auszeichnungssprache zum Erstellen von formatiertem Text mit einem Klartext-Editor.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) ist ein offener Standard-Dateiformat zum Austausch von Daten, das menschenlesbaren Text verwendet, um Daten zu speichern und zu übertragen.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


MIME-Kapselung aggregierter HTML-Dokumente ist ein Webseitensicherungsformat, das verwendet wird, um in einer einzigen Datei den HTML-Code und zugehörige Ressourcen zu kombinieren.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help ist ein proprietäres Online-Hilfebinärformat von Microsoft, das aus einer Sammlung von HTML-Seiten, einem Index und weiteren Navigationswerkzeugen besteht.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Liefert eine aufzählbare Sammlung aller [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
Wert: Ein IEnumerable{TextualFormats}, das alle Instanzen von [TextualFormats](../../com.groupdocs.editor.formats/textualformats) enthält.


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Ruft eine Instanz des angegebenen Typs [TextualFormats](../../com.groupdocs.editor.formats/textualformats) ab, die die angegebene Dateierweiterung besitzt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung des Dokumentformats. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [TextualFormats](../../com.groupdocs.editor.formats/textualformats)-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung zum Konvertieren. Wenn die Erweiterung mehrere Punkte enthält, wird der Teil nach dem letzten Punkt verwendet. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

