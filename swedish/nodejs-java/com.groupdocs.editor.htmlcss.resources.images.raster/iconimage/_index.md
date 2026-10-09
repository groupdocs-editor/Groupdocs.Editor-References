---
title: "IconImage"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar en bild i ICON-format med dess metadata och ytterligare metoder"
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Representerar en bild i ICON-format med dess metadata och ytterligare metoder

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Skapar en ny IconImage-instans från innehåll, representerat som |
base64-kodad sträng, och med angivet namn
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Skapar en ny IconImage-instans från innehåll, representerat som byte‑ström, |
och med angivet namn
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är en giltig ICON-bild |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64‑kodade strängen är en giltig ICON-bild |
|
|  | [getType()](#getType--) | Returnerar ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Returnerar antalet bilder som finns i denna ICON-fil |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Skapar en ny IconImage-instans från innehåll, representerat som
base64-kodad sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på ICON-bilden. Får inte vara null, tom eller bestå av endast blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64‑kodad sträng. Får inte vara null, tom eller bestå av endast blanksteg. Om det inte är ICON‑innehåll kastas ett undantag. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Skapar en ny IconImage-instans från innehåll, representerat som byte‑ström,
och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på ICON-bilden. Får inte vara null, tom eller bestå av endast blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte stream. Läsning börjar från originalposition. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även detta stream. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är en giltig ICON-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte stream, som förmodligen innehåller en ICON‑bild |
|

**Returns:**
boolean - Sant om den angivna strömmen innehåller en giltig ICON‑bild, annars falskt

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64‑kodade strängen är en giltig ICON-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehållet i den förmodade ICON‑bilden i form av en base64‑kodad sträng |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller en giltig ICON‑bild, annars falskt

### getType() {#getType--}
```
public ImageType getType()
```


Returnerar ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Returnerar antalet bilder som finns i denna ICON-fil


**Returns:**
int
