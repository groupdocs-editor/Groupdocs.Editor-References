---
title: "TextualFormats"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Omvat alle tekstgebaseerde formaten, inclusief markup XML HTML en andere."
type: docs
weight: 16
url: /nl/java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Omvat alle tekstuele (tekst‑gebaseerde) formaten, inclusief markup (XML, HTML) en andere.
Bevat de volgende formaten:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Html](#Html) | HyperText Markup Language-document (HTML) is de extensie voor webpagina's die zijn gemaakt voor weergave in browsers. |
|
|  | [Xml](#Xml) | eXtensible Markup Language-document (XML) dat vergelijkbaar is met HTML maar verschilt in het gebruik van tags voor het definiëren van objecten. |
|
|  | [Txt](#Txt) | Plain Text Document (TXT) vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. |
|
|  | [Md](#Md) | Markdown is een lichtgewicht opmaaktaal voor het maken van opgemaakte tekst met een platte-tekst editor. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) is een open standaard bestandsformaat voor het delen van gegevens dat menselijk leesbare tekst gebruikt om gegevens op te slaan en te verzenden. |
|
|  | [Mhtml](#Mhtml) | MIME-encapsulatie van samengestelde HTML-documenten is een webpagina-archiefformaat dat wordt gebruikt om, in één computerbestand, de HTML-code en de bijbehorende bronnen te combineren. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help is een door Microsoft gepatenteerd online hulpbinaire formaat, bestaande uit een verzameling HTML-pagina's, een index en andere navigatietools. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAll()](#getAll--) | Haalt een doorzoekbare collectie op van alle [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Haalt een instantie op van het opgegeven type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) dat de opgegeven bestandsextensie heeft. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object. |
|
### Html {#Html}
```
public static final TextualFormats Html
```


HyperText Markup Language-document (HTML) is de extensie voor webpagina's die zijn gemaakt voor weergave in browsers.
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


eXtensible Markup Language-document (XML) dat vergelijkbaar is met HTML maar verschilt in het gebruik van tags voor het definiëren van objecten.
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Plain Text Document (TXT) vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels.
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown is een lichtgewicht opmaaktaal voor het maken van opgemaakte tekst met een platte-tekst editor.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) is een open standaard bestandsformaat voor het delen van gegevens dat menselijk leesbare tekst gebruikt om gegevens op te slaan en te verzenden.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


MIME-encapsulatie van samengestelde HTML-documenten is een webpagina-archiefformaat dat wordt gebruikt om, in één computerbestand, de HTML-code en de bijbehorende bronnen te combineren.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help is een door Microsoft gepatenteerd online hulpbinaire formaat, bestaande uit een verzameling HTML-pagina's, een index en andere navigatietools.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Haalt een doorzoekbare collectie op van alle [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
Waarde: Een  IEnumerable{TextualFormats}  die alle instanties van [TextualFormats](../../com.groupdocs.editor.formats/textualformats) bevat.


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Haalt een instantie op van het opgegeven type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) dat de opgegeven bestandsextensie heeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie van het documentformaat. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie om te converteren. Als de extensie meerdere punten bevat, wordt het deel na het laatste punt gebruikt. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

