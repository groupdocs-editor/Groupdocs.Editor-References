---
title: "FormatFamilies"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar de olika formatfamiljerna som finns tillgängliga i systemet."
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Representerar de olika formatfamiljerna som finns tillgängliga i systemet.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [EBook](#EBook) | Representerar eBook‑formatfamiljen. |
|
|  | [Email](#Email) | Representerar Email‑formatfamiljen. |
|
|  | [FixedLayout](#FixedLayout) | Representerar Fixed Layout‑formatfamiljen. |
|
|  | [Presentation](#Presentation) | Representerar Presentation‑formatfamiljen. |
|
|  | [Spreadsheet](#Spreadsheet) | Representerar Spreadsheet‑formatfamiljen. |
|
|  | [Textual](#Textual) | Representerar Textual‑formatfamiljen. |
|
|  | [WordProcessing](#WordProcessing) | Representerar Word Processing‑formatfamiljen. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


Representerar eBook‑formatfamiljen.
Läs mer om Mobi‑formatet
[here](../https://docs.fileformat.com/ebook/mobi/)
,
om AZW3‑formatet
[here](../https://docs.fileformat.com/ebook/azw3/)
,
och om ePub-format
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Representerar Email‑formatfamiljen.
Läs mer om e-postformat
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Representerar Fixed Layout‑formatfamiljen.
Olika dokumentvisnings- eller publiceringsprogram låter användare öppna (Adobe Acrobat, XPS Viewer) och ibland redigera (Adobe InDesign) dokument i specifika format.
Dessa program producerar vanligtvis så kallade \u201cfixed-page\u201d formatdokument.
Ett sådant dokumentformat beskriver exakt var ett dokuments\u2019 innehåll placeras på varje sida.
Internt innehåller PDF- eller XPS-formatet en beskrivning av varje sida samt ritinstruktioner som specificerar layouten för innehållet på sidan.
Detta liknar bildformat, som beskriver var innehållet visas antingen i raster- eller vektorform.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Representerar Presentation‑formatfamiljen.
Läs mer om presentationsformat
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Representerar Spreadsheet‑formatfamiljen.
Alla binära, XML- och textbaserade kalkylbladsformat (exklusive alla textbaserade format med avgränsare som CSV, TSV, semikolon‑avgränsade etc.) som arbetsboken kan sparas i.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Representerar Textual‑formatfamiljen.
Innesluter alla textbaserade (text‑baserade) format, inklusive markup (XML, HTML) och andra.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Representerar Word Processing‑formatfamiljen.
Läs mer om ordbehandlingsformat
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

MIME‑koder hämtas från de angivna resurserna: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



