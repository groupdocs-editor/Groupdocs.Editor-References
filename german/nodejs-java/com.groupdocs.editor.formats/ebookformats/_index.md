---
title: "EBookFormats"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Kapselt alle eBook‑Formate."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Kapselt alle eBook-Formate. Enthält die folgenden Dateitypen:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Erfahren Sie mehr über das Mobi-Format [hier](../https://docs.fileformat.com/ebook/mobi/), und über das ePub-Format [hier](../https://docs.fileformat.com/ebook/epub/).

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI ist der Name des für den MobiPocket Reader entwickelten Formats. |
|
|  | [Epub](#Epub) | Das Electronic Publication (IDPF ePub)-Format ist ein eBook-Dateiformat, das ein standardisiertes digitales Publikationsformat für Verlage und Verbraucher bereitstellt. |
|
|  | [Azw3](#Azw3) | AZW3, auch bekannt als Kindle Format 8 (KF8), ist die modifizierte Version des AZW eBook-Digitaldateiformats, das für Amazon Kindle-Geräte entwickelt wurde. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAll()](#getAll--) | Gibt eine aufzählbare Sammlung aller [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) zurück. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ruft eine Instanz des angegebenen Typs [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) ab, die die angegebene Dateierweiterung besitzt. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [EBookFormats](../../com.groupdocs.editor.formats/ebookformats)-Objekt. |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI ist der Name des für den MobiPocket Reader entwickelten Formats. Auch als PRC, AZW bezeichnet.
Es wird derzeit von Amazon mit einem leicht abweichenden DRM-Schema verwendet und heißt AZW.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Das Electronic Publication (IDPF ePub)-Format ist ein eBook-Dateiformat, das ein standardisiertes digitales Publikationsformat für Verlage und Verbraucher bereitstellt.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, auch bekannt als Kindle Format 8 (KF8), ist die modifizierte Version des AZW eBook-Digitaldateiformats, das für Amazon Kindle-Geräte entwickelt wurde.
Das Format ist eine Verbesserung gegenüber älteren AZW-Dateien.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Gibt eine aufzählbare Sammlung aller [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) zurück.
Wert: Ein IEnumerable{EBookFormats}, das alle Instanzen von [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) enthält.


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Ruft eine Instanz des angegebenen Typs [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) ab, die die angegebene Dateierweiterung besitzt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung des Dokumentformats. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [EBookFormats](../../com.groupdocs.editor.formats/ebookformats)-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die zu konvertierende Dateierweiterung. Wenn die Erweiterung mehrere Punkte enthält, wird der Teil nach dem letzten Punkt verwendet. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

