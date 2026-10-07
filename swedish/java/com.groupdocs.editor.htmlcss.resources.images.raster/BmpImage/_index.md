---
title: "BmpImage"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar en bild i BMP BitMap Picture-format med dess metadata och ytterligare metoder"
type: docs
weight: 10
url: /sv/java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

Representerar en bild i BMP (BitMap Picture)-format med dess metadata och
ytterligare metoder

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | Skapar en ny BmpImage-instans från innehåll, representerat som base64‑kodad |
sträng, och med angivet namn
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | Skapar en ny BmpImage-instans från innehåll, representerad som byte‑ström, |
och med angivet namn
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är en giltig BMP-bild |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64‑kodade strängen är en giltig BMP-bild |
|
|  | [getType()](#getType--) | Returnerar ImageType.Bmp |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


Skapar en ny BmpImage-instans från innehåll, representerat som base64‑kodad
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på BMP-bilden. Får inte vara null, tomt eller bara blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64‑kodad sträng. Får inte vara null, tomt eller bara blanksteg. Om det inte är BMP‑innehåll kommer ett undantag att kastas. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


Skapar en ny BmpImage-instans från innehåll, representerad som byte‑ström,
och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på BMP-bilden. Får inte vara null, tomt eller bara blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Ska vara läsbar och sökbar. Om detta objekt frigörs, frigörs även denna ström. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är en giltig BMP-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑ström som sannolikt innehåller en BMP-bild |
|

**Returns:**
boolean - Sant om den angivna strömmen innehåller en giltig BMP-bild, annars falskt

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64‑kodade strängen är en giltig BMP-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehållet i den sannolikt BMP-bilden i form av en base64‑kodad sträng |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller en giltig BMP-bild, annars falskt

### getType() {#getType--}
```
public ImageType getType()
```


Returnerar ImageType.Bmp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
