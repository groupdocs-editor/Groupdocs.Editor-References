---
title: "FormatFamilies"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente les différentes familles de formats disponibles dans le système."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Représente les différentes familles de formats disponibles dans le système.

## Champs

| Champ | Description |
| --- | --- |
|  | [EBook](#EBook) | Représente la famille de formats eBook. |
|
|  | [Email](#Email) | Représente la famille de formats Email. |
|
|  | [FixedLayout](#FixedLayout) | Représente la famille de formats Fixed Layout. |
|
|  | [Presentation](#Presentation) | Représente la famille de formats Presentation. |
|
|  | [Spreadsheet](#Spreadsheet) | Représente la famille de formats Spreadsheet. |
|
|  | [Textual](#Textual) | Représente la famille de formats Textual. |
|
|  | [WordProcessing](#WordProcessing) | Représente la famille de formats Word Processing. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


Représente la famille de formats eBook.
En savoir plus sur le format Mobi
[here](../https://docs.fileformat.com/ebook/mobi/)
,
à propos du format AZW3
[here](../https://docs.fileformat.com/ebook/azw3/)
,
et à propos du format ePub
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Représente la famille de formats Email.
En savoir plus sur le format des e‑mails
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Représente la famille de formats Fixed Layout.
Diverses applications de visualisation ou de publication de documents permettent aux utilisateurs d’ouvrir (Adobe Acrobat, XPS Viewer), et parfois de modifier (Adobe InDesign) des documents de formats spécifiques.
Ces applications produisent généralement des documents au format “fixed-page”.
Un tel format de document décrit précisément où le contenu d’un document est placé sur chaque page.
En interne, le format PDF ou XPS contient une description de chaque page, ainsi que des instructions de dessin, spécifiant la disposition du contenu sur la page.
C’est similaire aux formats d’image, décrivant où le contenu est affiché soit sous forme raster, soit sous forme vectorielle.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Représente la famille de formats Presentation.
En savoir plus sur les formats de présentation
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Représente la famille de formats Spreadsheet.
Tous les formats de feuille de calcul binaires, XML et textuels (à l’exclusion de tous les formats textuels basés sur des délimiteurs avec séparateur comme CSV, TSV, délimité par point‑virgule, etc.), dans lesquels le classeur peut être enregistré.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Représente la famille de formats Textual.
Encapsule tous les formats textuels (basés sur du texte), y compris le balisage (XML, HTML) et d'autres.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Représente la famille de formats Word Processing.
En savoir plus sur les formats de traitement de texte
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

Les codes MIME sont récupérés à partir des ressources indiquées : https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



