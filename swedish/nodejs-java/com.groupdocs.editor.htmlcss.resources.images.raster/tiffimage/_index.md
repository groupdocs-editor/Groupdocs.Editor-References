---
title: "TiffImage"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar en bild i TIFF Tagged Image File Format-format med dess metadata och ytterligare metoder"
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

Representerar en bild i TIFF (Tagged Image File Format)-format med dess
metadata och ytterligare metoder


*** ** * ** ***

Se https://en.wikipedia.org/wiki/TIFF för detaljer. I mycket sällsynta fall förekommer TIFF i WordProcessing-dokument.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | Skapar en ny TiffImage-instans från innehåll, representerat som |
base64-kodad sträng, och med angivet namn
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | Skapar en ny GifImage‑instans från innehåll, representerat som byte‑ström, |
och med angivet namn
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är en giltig TIFF-bild |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64-kodade strängen är en giltig TIFF-bild |
|
|  | [getType()](#getType--) | Returnerar ImageType.Tiff |
|
|  | [getFramesCount()](#getFramesCount--) | Returnerar antalet ramar (bilder) i denna TIFF-bild. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


Skapar en ny TiffImage-instans från innehåll, representerat som
base64-kodad sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på TIFF-bilden. Får inte vara null, tom eller bestå av bara blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64-kodad sträng. Får inte vara null, tom eller bestå av bara blanksteg. Om det inte är TIFF-innehåll kommer ett undantag att kastas. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


Skapar en ny GifImage‑instans från innehåll, representerat som byte‑ström,
och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på GIF‑bilden. Får inte vara null, tom eller bestå av blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte stream. Läsning börjar från originalposition. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även detta stream. |
|

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är en giltig TIFF-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte-ström som förmodligen innehåller en TIFF-bild |
|

**Returns:**
boolean - True om den angivna strömmen innehåller en giltig TIFF-bild, annars false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64-kodade strängen är en giltig TIFF-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehållet i den förmodade TIFF-bilden i form av en base64-kodad sträng |
|

**Returns:**
boolean - True om den angivna strängen innehåller en giltig TIFF-bild, annars false

### getType() {#getType--}
```
public ImageType getType()
```


Returnerar ImageType.Tiff


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Returnerar antalet ramar (bilder) i denna TIFF-bild. Får inte vara
mindre än 1.


**Returns:**
int -
