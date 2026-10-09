---
title: "TextualFormats"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innesluter alla textbaserade format inklusive markup XML HTML och andra."
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Innesluter alla textbaserade (text‑baserade) format, inklusive markup (XML, HTML) och andra.
Inkluderar följande format:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Html](#Html) | HyperText Markup Language-dokument (HTML) är filändelsen för webbsidor skapade för visning i webbläsare. |
|
|  | [Xml](#Xml) | eXtensible Markup Language-dokument (XML) som liknar HTML men skiljer sig åt genom att använda taggar för att definiera objekt. |
|
|  | [Txt](#Txt) | Plain Text Document (TXT) representerar ett textdokument som innehåller vanlig text i form av rader. |
|
|  | [Md](#Md) | Markdown är ett lättviktigt markup-språk för att skapa formaterad text med en vanlig textredigerare. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) är ett öppet standardfilformat för datadelning som använder människoläsbar text för att lagra och överföra data. |
|
|  | [Mhtml](#Mhtml) | MIME-inkapsling av aggregerade HTML-dokument är ett webbsidesarkivformat som används för att kombinera, i en enda datorfil, HTML-koden och dess medföljande resurser. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help är ett Microsoft-proprietärt binärt format för onlinehjälp, bestående av en samling HTML-sidor, ett index och andra navigationsverktyg. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAll()](#getAll--) | Hämtar en uppräkningsbar samling av alla [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Hämtar en instans av den specificerade typen [TextualFormats](../../com.groupdocs.editor.formats/textualformats) som har den specificerade filändelsen. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konverterar en sträng som representerar en filändelse till ett [TextualFormats](../../com.groupdocs.editor.formats/textualformats)-objekt. |
|
### Html {#Html}
```
public static final TextualFormats Html
```


HyperText Markup Language-dokument (HTML) är filändelsen för webbsidor skapade för visning i webbläsare.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


eXtensible Markup Language-dokument (XML) som liknar HTML men skiljer sig åt genom att använda taggar för att definiera objekt.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Plain Text Document (TXT) representerar ett textdokument som innehåller vanlig text i form av rader.
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown är ett lättviktigt markup-språk för att skapa formaterad text med en vanlig textredigerare.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) är ett öppet standardfilformat för datadelning som använder människoläsbar text för att lagra och överföra data.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


MIME-inkapsling av aggregerade HTML-dokument är ett webbsidesarkivformat som används för att kombinera, i en enda datorfil, HTML-koden och dess medföljande resurser.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help är ett Microsoft-proprietärt binärt format för onlinehjälp, bestående av en samling HTML-sidor, ett index och andra navigationsverktyg.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Hämtar en uppräkningsbar samling av alla [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
Värde: En  IEnumerable{TextualFormats}  som innehåller alla instanser av [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Hämtar en instans av den specificerade typen [TextualFormats](../../com.groupdocs.editor.formats/textualformats) som har den specificerade filändelsen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen för dokumentformatet. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Konverterar en sträng som representerar en filändelse till ett [TextualFormats](../../com.groupdocs.editor.formats/textualformats)-objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

