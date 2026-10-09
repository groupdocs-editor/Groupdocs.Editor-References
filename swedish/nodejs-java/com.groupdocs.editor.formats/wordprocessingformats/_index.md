---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innesluter alla ordbehandlingsformat."
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

Innesluter alla WordProcessing-format. Inkluderar följande filtyper:
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
Läs mer om Word Processing-format [här](../https://wiki.fileformat.com/word-processing).

MIME-koder hämtas från de angivna resurserna:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Doc](#Doc) | MS Word 97-2007 binära filformat (DOC) representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. |
|
|  | [Docx](#Docx) | Office Open XML WordProcessingML makrofri dokument (DOCX) är ett välkänt format för Microsoft Word-dokument. |
|
|  | [Dot](#Dot) | MS Word 97-2007-mall (DOT) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer. |
|
|  | [Docm](#Docm) | Office Open XML WordProcessingML makroaktiverade dokument (DOCM)-filer är Microsoft Word 2007 eller senare genererade dokument med möjlighet att köra makron. |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML makrofri mall (DOTX) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer. |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML makroaktiverad mall (DOTM) representerar mallfiler skapade med Microsoft Word 2007 eller senare. |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML lagras i en platt XML-fil istället för ett ZIP-paket. |
|
|  | [Rtf](#Rtf) | Rich Text Format (RTF) representerar en metod för kodning av formaterad text och grafik för användning i applikationer. |
|
|  | [Odt](#Odt) | Open Document Format Textdokument (ODT)-filer är en typ av dokument skapade med ordbehandlingsprogram som är baserade på OpenDocument Textfilformat. |
|
|  | [Ott](#Ott) | Open Document Format Textdokumentmall (OTT) representerar mall-dokument som genereras av program i enlighet med OASIS OpenDocument-standardformatet. |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML-format — WordProcessingML eller WordML (.XML). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAll()](#getAll--) | Hämtar en enumererbar samling av alla [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Hämtar en instans av den angivna typen [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) som har den angivna filändelsen. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konverterar en sträng som representerar en filändelse till ett [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)-objekt. |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


MS Word 97-2007 binära filformat (DOC) representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Office Open XML WordProcessingML makrofri dokument (DOCX) är ett välkänt format för Microsoft Word-dokument.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS Word 97-2007-mall (DOT) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Office Open XML WordProcessingML makroaktiverade dokument (DOCM)-filer är Microsoft Word 2007 eller senare genererade dokument med möjlighet att köra makron.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML makrofri mall (DOTX) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML makroaktiverad mall (DOTM) representerar mallfiler skapade med Microsoft Word 2007 eller senare.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML lagras i en platt XML-fil istället för ett ZIP-paket.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format (RTF) representerar en metod för kodning av formaterad text och grafik för användning i applikationer.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Open Document Format Textdokument (ODT)-filer är en typ av dokument skapade med ordbehandlingsprogram som är baserade på OpenDocument Textfilformat.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format Textdokumentmall (OTT) representerar mall-dokument som genereras av program i enlighet med OASIS OpenDocument-standardformatet.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML-format — WordProcessingML eller WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


Hämtar en enumererbar samling av alla [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).
Värde: En  IEnumerable{WordProcessingFormats}  som innehåller alla instanser av [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


Hämtar en instans av den angivna typen [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) som har den angivna filändelsen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen för dokumentformatet. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


Konverterar en sträng som representerar en filändelse till ett [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)-objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

