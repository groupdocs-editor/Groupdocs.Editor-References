---
title: "PngImage"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar en bild i PNG Portable Network Graphics-format med dess metadata och ytterligare metoder"
type: docs
weight: 14
url: /sv/java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Representerar en bild i PNG (Portable Network Graphics)-format med dess
metadata och ytterligare metoder

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Skapar en ny PngImage-instans från innehåll, representerat som base64‑kodad |
sträng, och med angivet namn
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Skapar en ny PngImage-instans från innehåll, representerat som byte‑ström, |
och med angivet namn
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är en giltig PNG‑bild |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64‑kodade strängen är en giltig PNG‑bild |
|
|  | [getType()](#getType--) | Returnerar ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Skapar en ny PngImage-instans från innehåll, representerat som base64‑kodad
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på PNG‑bilden. Får inte vara null, tom eller bestå av blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64‑kodad sträng. Får inte vara null, tom eller bestå av blanksteg. Om det inte är ett PNG‑innehåll kastas ett undantag. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Skapar en ny PngImage-instans från innehåll, representerat som byte‑ström,
och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på PNG‑bilden. Får inte vara null, tom eller bestå av blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Ska vara läsbar och sökbar. Om detta objekt frigörs, frigörs även denna ström. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är en giltig PNG‑bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑ström som sannolikt innehåller en PNG‑bild |
|

**Returns:**
boolean - Sant om den angivna strömmen innehåller en giltig PNG‑bild, annars falskt

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64‑kodade strängen är en giltig PNG‑bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehållet i den sannolikt PNG‑bilden i form av en base64‑kodad sträng |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller en giltig PNG‑bild, annars falskt

### getType() {#getType--}
```
public ImageType getType()
```


Returnerar ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
