---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Festlegen benutzerdefinierter Optionen zum Erzeugen und Speichern des Dokuments in allen unterstützten E‑Book‑Formaten ePub, MOBI und AZW3."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern des Dokuments in allen unterstützbaren E‑Book‑Formaten: ePub, MOBI und AZW3.

<br />

*** ** * ** ***

Unterstützte E‑Book‑Formate:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Elektronische Publikation)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle‑Format 8t)

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Dieser parameterlose Konstruktor erstellt eine neue Instanz von EbookSaveOptions mit dem ePub-Ausgabeformat (kann anschließend über |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) Eigenschaft)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Erstellt eine neue Instanz von [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) mit dem angegebenen obligatorischen E‑Book‑Ausgabeformat, während alle anderen Parameter standardmäßig sind. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Gibt die maximale Ebene von Überschriften an, bei der die E‑Book‑Datei aufgeteilt wird. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Gibt die maximale Ebene von Überschriften an, bei der die E‑Book‑Datei aufgeteilt wird. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Gibt an, ob integrierte und benutzerdefinierte Dokumenteigenschaften in die resultierende Datei exportiert werden sollen. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Gibt an, ob integrierte und benutzerdefinierte Dokumenteigenschaften in die resultierende Datei exportiert werden sollen. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Gibt das Format der resultierenden E‑Book‑Datei an: IDPF ePub, MOBI oder AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Gibt das Format der resultierenden E‑Book‑Datei an: IDPF ePub, MOBI oder AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Dieser parameterlose Konstruktor erstellt eine neue Instanz von EbookSaveOptions mit dem ePub-Ausgabeformat (kann anschließend über
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) Eigenschaft)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Erstellt eine neue Instanz von [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) mit dem angegebenen obligatorischen E‑Book‑Ausgabeformat, während alle anderen Parameter standardmäßig sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | obligatorisches Ausgabeformat, in dem das e-Book gespeichert werden soll |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Gibt die maximale Überschriftenebene an, bei der die e-Book-Datei aufgeteilt werden soll. Standardwert ist
2
.
Setzt man es auf
0
deaktiviert das Aufteilen, sodass der gesamte Inhalt des e-Books in ein einzelnes Paket in der resultierenden Datei integriert wird.

<br />

*** ** * ** ***

Wenn diese Eigenschaft auf einen Wert von 1 bis 9 gesetzt wird, wird das Dokument an Absätzen aufgeteilt, die formatiert sind mit

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc.-Stilen bis zur angegebenen Überschriftenebene.

Standardmäßig werden nur
**Heading 1**
und
**Heading 2**
Absätze führen dazu, dass das Dokument aufgeteilt wird.
Setzt man diese Eigenschaft auf Null (oder kleiner als Null), wird das Dokument überhaupt nicht an Überschriftsabsätzen aufgeteilt.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Gibt die maximale Überschriftenebene an, bei der die e-Book-Datei aufgeteilt werden soll. Standardwert ist
2
.
Setzt man es auf
0
deaktiviert das Aufteilen, sodass der gesamte Inhalt des e-Books in ein einzelnes Paket in der resultierenden Datei integriert wird.

<br />

*** ** * ** ***

Wenn diese Eigenschaft auf einen Wert von 1 bis 9 gesetzt wird, wird das Dokument an Absätzen aufgeteilt, die formatiert sind mit

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc.-Stilen bis zur angegebenen Überschriftenebene.

Standardmäßig werden nur
**Heading 1**
und
**Heading 2**
Absätze führen dazu, dass das Dokument aufgeteilt wird.
Setzt man diese Eigenschaft auf Null (oder kleiner als Null), wird das Dokument überhaupt nicht an Überschriftsabsätzen aufgeteilt.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Gibt an, ob integrierte und benutzerdefinierte Dokumenteigenschaften in die resultierende Datei exportiert werden sollen.
Standardwert ist
false
.


**Returns:**
boolesch
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Gibt an, ob integrierte und benutzerdefinierte Dokumenteigenschaften in die resultierende Datei exportiert werden sollen.
Standardwert ist
false
.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Gibt das Format der resultierenden E‑Book‑Datei an: IDPF ePub, MOBI oder AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Gibt das Format der resultierenden E‑Book‑Datei an: IDPF ePub, MOBI oder AZW3.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

