---
title: "EBookFormats"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Omvat alle e‑book‑formaten."
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Omvat alle eBook-formaten. Bevat de volgende bestandstypen:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Meer informatie over het Mobi-formaat [hier](../https://docs.fileformat.com/ebook/mobi/), en over het ePub-formaat [hier](../https://docs.fileformat.com/ebook/epub/).

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI is de naam die aan het formaat is gegeven dat ontwikkeld is voor de MobiPocket Reader. |
|
|  | [Epub](#Epub) | Electronic Publication (IDPF ePub) is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten. |
|
|  | [Azw3](#Azw3) | AZW3, ook bekend als Kindle Format 8 (KF8), is de aangepaste versie van het AZW e‑book digitale bestandsformaat ontwikkeld voor Amazon Kindle‑apparaten. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAll()](#getAll--) | Haalt een doorzoekbare collectie op van alle [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Haalt een instantie op van het opgegeven type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) dat de opgegeven bestandsextensie heeft. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converteert een tekenreeks die een bestandsextensie voorstelt naar een [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object. |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI is de naam die aan het formaat is gegeven dat ontwikkeld is voor de MobiPocket Reader. Ook wel PRC, AZW genoemd.
Het wordt momenteel door Amazon gebruikt met een iets ander DRM‑schema en heet AZW.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Electronic Publication (IDPF ePub) is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, ook bekend als Kindle Format 8 (KF8), is de aangepaste versie van het AZW e‑book digitale bestandsformaat ontwikkeld voor Amazon Kindle‑apparaten.
Het formaat is een verbetering ten opzichte van oudere AZW‑bestanden.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Haalt een doorzoekbare collectie op van alle [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
Waarde: Een  IEnumerable{EBookFormats}  die alle instanties van [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) bevat.


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Haalt een instantie op van het opgegeven type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) dat de opgegeven bestandsextensie heeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie van het documentformaat. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Converteert een tekenreeks die een bestandsextensie voorstelt naar een [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie om te converteren. Als de extensie meerdere punten bevat, wordt het deel na het laatste punt gebruikt. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

