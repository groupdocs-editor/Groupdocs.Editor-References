---
title: "FormatFamilies"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta le diverse famiglie di formati disponibili nel sistema."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Rappresenta le diverse famiglie di formati disponibili nel sistema.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [EBook](#EBook) | Rappresenta la famiglia di formati eBook. |
|
|  | [Email](#Email) | Rappresenta la famiglia di formati Email. |
|
|  | [FixedLayout](#FixedLayout) | Rappresenta la famiglia di formati Fixed Layout. |
|
|  | [Presentation](#Presentation) | Rappresenta la famiglia di formati Presentation. |
|
|  | [Spreadsheet](#Spreadsheet) | Rappresenta la famiglia di formati Spreadsheet. |
|
|  | [Textual](#Textual) | Rappresenta la famiglia di formati Textual. |
|
|  | [WordProcessing](#WordProcessing) | Rappresenta la famiglia di formati Word Processing. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


Rappresenta la famiglia di formati eBook.
Scopri di più sul formato Mobi
[here](../https://docs.fileformat.com/ebook/mobi/)
,
sul formato AZW3
[here](../https://docs.fileformat.com/ebook/azw3/)
,
e sul formato ePub
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Rappresenta la famiglia di formati Email.
Scopri di più sul formato delle email
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Rappresenta la famiglia di formati Fixed Layout.
Vari applicativi di visualizzazione o pubblicazione di documenti consentono agli utenti di aprire (Adobe Acrobat, XPS Viewer) e talvolta modificare (Adobe InDesign) documenti di formati specifici.
Queste applicazioni tipicamente producono documenti in formato “fixed-page”.
Un tale formato di documento descrive con precisione dove il contenuto di un documento è posizionato su ogni pagina.
Internamente, il formato PDF o XPS contiene una descrizione di ogni pagina, nonché istruzioni di disegno, che specificano la disposizione del contenuto sulla pagina.
Ciò è simile ai formati immagine, descrivendo dove il contenuto è mostrato sia in forma raster che vettoriale.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Rappresenta la famiglia di formati Presentation.
Scopri di più sui formati di presentazione
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Rappresenta la famiglia di formati Spreadsheet.
Tutti i formati di foglio di calcolo binari, XML e testuali (escludendo tutti i formati testuali basati su delimitatori con separatori come CSV, TSV, delimitati da punto e virgola, ecc.), in cui è possibile salvare la cartella di lavoro.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Rappresenta la famiglia di formati Textual.
Incapsula tutti i formati testuali (basati su testo), inclusi markup (XML, HTML) e altri.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Rappresenta la famiglia di formati Word Processing.
Scopri di più sui formati di elaborazione testi
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

I codici MIME sono prelevati dalle risorse fornite: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



