---
title: "FormatFamilies"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt die verschiedenen im System verfügbaren Formatfamilien dar."
type: docs
weight: 13
url: /de/java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Stellt die verschiedenen im System verfügbaren Formatfamilien dar.

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [EBook](#EBook) | Stellt die eBook-Formatfamilie dar. |
|
|  | [Email](#Email) | Stellt die E‑Mail-Formatfamilie dar. |
|
|  | [FixedLayout](#FixedLayout) | Stellt die Fixed‑Layout-Formatfamilie dar. |
|
|  | [Presentation](#Presentation) | Stellt die Präsentations-Formatfamilie dar. |
|
|  | [Spreadsheet](#Spreadsheet) | Stellt die Tabellenkalkulations-Formatfamilie dar. |
|
|  | [Textual](#Textual) | Stellt die Textformatfamilie dar. |
|
|  | [WordProcessing](#WordProcessing) | Stellt die Textverarbeitungs-Formatfamilie dar. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


Stellt die eBook-Formatfamilie dar.
Erfahren Sie mehr über das Mobi-Format
[here](../https://docs.fileformat.com/ebook/mobi/)
,
über das AZW3-Format
[here](../https://docs.fileformat.com/ebook/azw3/)
,
und über das ePub-Format
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Stellt die E‑Mail-Formatfamilie dar.
Erfahren Sie mehr über das E‑Mail-Format
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Stellt die Fixed‑Layout-Formatfamilie dar.
Verschiedene Dokumentanzeige‑ oder Veröffentlichungsanwendungen ermöglichen es Benutzern, Dokumente bestimmter Formate zu öffnen (Adobe Acrobat, XPS Viewer) und manchmal zu bearbeiten (Adobe InDesign).
Diese Anwendungen erzeugen typischerweise sogenannte „fixed-page“-Formatdokumente.
Ein solches Dokumentformat beschreibt genau, wo der Inhalt eines Dokuments auf jeder Seite platziert wird.
Intern enthält das PDF‑ oder XPS‑Format eine Beschreibung jeder Seite sowie Zeichenanweisungen, die das Layout des Inhalts auf der Seite festlegen.
Dies ist ähnlich zu Bildformaten, die beschreiben, wo der Inhalt entweder in Raster‑ oder Vektorform angezeigt wird.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Stellt die Präsentations-Formatfamilie dar.
Erfahren Sie mehr über Präsentationsformate
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Stellt die Tabellenkalkulations-Formatfamilie dar.
Alle binären, XML- und textbasierten Tabellenkalkulationsformate (ausgenommen alle textbasierten, durch Trennzeichen definierten Formate wie CSV, TSV, semikolongetrennt usw.), in denen die Arbeitsmappe gespeichert werden kann.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Stellt die Textformatfamilie dar.
Kapselt alle textuellen (textbasierten) Formate, einschließlich Markup (XML, HTML) und anderer.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Stellt die Textverarbeitungs-Formatfamilie dar.
Erfahren Sie mehr über Textverarbeitungsformate
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

MIME-Codes werden aus den angegebenen Quellen entnommen: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



