---
title: "GifImage"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar en bild i GIF Graphics Interchange Format-format med dess metadata och ytterligare metoder"
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Representerar en bild i GIF (Graphics Interchange Format)-format med dess
metadata och ytterligare metoder

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Skapar en ny GifImage‑instans från innehåll, representerat som base64‑kodad |
sträng, och med angivet namn
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Skapar en ny GifImage‑instans från innehåll, representerat som byte‑ström, |
och med angivet namn
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är en giltig GIF‑bild |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64‑kodade strängen är en giltig GIF‑bild |
|
|  | [getType()](#getType--) | Returnerar ImageType.Gif |
|
|  | [getVersion()](#getVersion--) | Returnerar intern version av denna GIF‑bild (versionen extraheras från |
header)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


Skapar en ny GifImage‑instans från innehåll, representerat som base64‑kodad
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på GIF‑bilden. Får inte vara null, tom eller bestå av blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64‑kodad sträng. Får inte vara null, tom eller bestå av blanksteg. Om det inte är GIF‑innehåll kastas ett undantag. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
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

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är en giltig GIF‑bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte stream, som förmodligen innehåller en GIF‑bild |
|

**Returns:**
boolean - Sant om den angivna strömmen innehåller en giltig GIF‑bild, annars falskt

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64‑kodade strängen är en giltig GIF‑bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehållet i den förmodade GIF‑bilden i form av en base64‑kodad sträng |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller en giltig GIF‑bild, annars falskt

### getType() {#getType--}
```
public ImageType getType()
```


Returnerar ImageType.Gif


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Returnerar intern version av denna GIF‑bild (versionen extraheras från
header)


**Returns:**
java.lang.String
