---
title: "EBookFormats"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Inkapslar alla eBook-format."
type: docs
weight: 10
url: /sv/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Innesluter alla eBook-format. Inkluderar följande filtyper:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Läs mer om Mobi-formatet [här](../https://docs.fileformat.com/ebook/mobi/), och om ePub-formatet [här](../https://docs.fileformat.com/ebook/epub/).

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI är namnet på formatet som utvecklades för MobiPocket Reader. |
|
|  | [Epub](#Epub) | Electronic Publication (IDPF ePub)-formatet är ett e-bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat för förlag och konsumenter. |
|
|  | [Azw3](#Azw3) | AZW3, även känt som Kindle Format 8 (KF8), är den modifierade versionen av AZW e‑bokfilformatet som utvecklades för Amazon Kindle‑enheter. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAll()](#getAll--) | Hämtar en enumererbar samling av alla [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Hämtar en instans av den angivna typen [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) som har den angivna filändelsen. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konverterar en sträng som representerar en filändelse till ett [EBookFormats](../../com.groupdocs.editor.formats/ebookformats)-objekt. |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI är namnet på formatet som utvecklades för MobiPocket Reader. Även kallat PRC, AZW.
Det används för närvarande av Amazon med ett något annorlunda DRM‑schema och kallas AZW.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Electronic Publication (IDPF ePub)-formatet är ett e-bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat för förlag och konsumenter.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, även känt som Kindle Format 8 (KF8), är den modifierade versionen av AZW e‑bokfilformatet som utvecklades för Amazon Kindle‑enheter.
Formatet är en förbättring av äldre AZW-filer.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Hämtar en enumererbar samling av alla [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
Värde: En  IEnumerable{EBookFormats}  som innehåller alla instanser av [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Hämtar en instans av den angivna typen [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) som har den angivna filändelsen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen för dokumentformatet. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Konverterar en sträng som representerar en filändelse till ett [EBookFormats](../../com.groupdocs.editor.formats/ebookformats)-objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

