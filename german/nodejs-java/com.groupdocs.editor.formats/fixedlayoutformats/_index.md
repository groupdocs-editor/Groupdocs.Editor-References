---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Kapselt alle Fixed-Layout‑Formate, auch bekannt als Fixed‑Page‑Formate, die PDF und XPS umfassen; rasterbasierte Bilder sind nicht enthalten."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Kapselt alle Fixed‑Layout‑Formate (auch bekannt als "fixed-page"), die PDF und XPS umfassen (Rasterbilder sind nicht enthalten).

<br />

*** ** * ** ***

Verschiedene Dokumentanzeige‑ oder Veröffentlichungsanwendungen ermöglichen es Benutzern, Dokumente bestimmter Formate zu öffnen (Adobe Acrobat, XPS Viewer) und manchmal zu bearbeiten (Adobe InDesign). Diese Anwendungen erzeugen typischerweise sogenannte „fixed-page“-Formatdokumente. Ein solches Dokumentformat beschreibt genau, wo der Inhalt eines Dokuments auf jeder Seite platziert wird. Intern enthält das PDF‑ oder XPS‑Format eine Beschreibung jeder Seite sowie Zeichenanweisungen, die das Layout des Inhalts auf der Seite festlegen. Dies ist ähnlich wie bei Bildformaten, die beschreiben, wo der Inhalt entweder in Raster‑ oder Vektorform angezeigt wird.

<br />


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) ist ein Dokumenttyp, der in den 1990er‑Jahren von Adobe erstellt wurde. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAll()](#getAll--) | Gibt eine aufzählbare Sammlung aller [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) zurück. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ruft eine Instanz des angegebenen Typs [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) ab, die die angegebene Dateierweiterung besitzt. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)-Objekt. |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format (PDF) ist ein Dokumenttyp, der in den 1990er‑Jahren von Adobe erstellt wurde. Der Zweck dieses Dateiformats bestand darin, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Gibt eine aufzählbare Sammlung aller [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) zurück.
Wert: Ein IEnumerable{FixedLayoutFormats}, das alle Instanzen von [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) enthält.


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Ruft eine Instanz des angegebenen Typs [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) ab, die die angegebene Dateierweiterung besitzt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung des Dokumentformats. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die zu konvertierende Dateierweiterung. Wenn die Erweiterung mehrere Punkte enthält, wird der Teil nach dem letzten Punkt verwendet. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

