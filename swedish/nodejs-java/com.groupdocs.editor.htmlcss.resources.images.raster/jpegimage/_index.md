---
title: "JpegImage"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar en bild i JPEG Joint Photographic Experts Group-format med dess metadata och ytterligare metoder"
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Representerar en bild i JPEG (Joint Photographic Experts Group)-format med
dess metadata och ytterligare metoder

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Skapar en ny JpegImage-instans från innehåll, representerad som |
base64-kodad sträng, och med angivet namn
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Skapar en ny JpegImage-instans från innehåll, representerad som byte stream, |
och med angivet namn
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är en giltig JPEG-bild |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64-kodade strängen är en giltig JPEG-bild |
|
|  | [getType()](#getType--) | Returnerar ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Skapar en ny JpegImage-instans från innehåll, representerad som
base64-kodad sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på JPEG-bilden. Får inte vara null, tom eller blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64-kodad sträng. Får inte vara null, tom eller blanksteg. Om det inte är JPEG-innehåll kommer ett undantag att kastas. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Skapar en ny JpegImage-instans från innehåll, representerad som byte stream,
och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på JPEG-bilden. Får inte vara null, tom eller blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte stream. Läsning börjar från originalposition. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även detta stream. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är en giltig JPEG-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte stream, som sannolikt innehåller en JPEG-bild |
|

**Returns:**
boolean - Sant om den angivna strömmen innehåller en giltig JPEG-bild, falskt annars

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64-kodade strängen är en giltig JPEG-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehåll av den sannolikt JPEG-bilden i form av en base64-kodad sträng |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller en giltig JPEG-bild, falskt annars

### getType() {#getType--}
```
public ImageType getType()
```


Returnerar ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
