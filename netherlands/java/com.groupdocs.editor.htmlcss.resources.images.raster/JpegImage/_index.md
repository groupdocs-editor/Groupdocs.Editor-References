---
title: "JpegImage"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één afbeelding voor in JPEG Joint Photographic Experts Group-formaat met zijn metadata en extra methoden"
type: docs
weight: 13
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Stelt één afbeelding voor in JPEG (Joint Photographic Experts Group)-formaat met
zijn metadata en extra methoden

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Maakt een nieuw JpegImage‑object aan vanuit de inhoud, weergegeven als |
base64-gecodeerde string, en met opgegeven naam
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Maakt een nieuw JpegImage‑object aan vanuit de inhoud, weergegeven als byte‑stream, |
en met opgegeven naam
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stream een geldige JPEG-afbeelding is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64‑gecodeerde string een geldige JPEG-afbeelding is |
|
|  | [getType()](#getType--) | Retourneert ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Maakt een nieuw JpegImage‑object aan vanuit de inhoud, weergegeven als
base64-gecodeerde string, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de JPEG-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-gecodeerde string. Mag niet null, leeg of alleen witruimte zijn. Als het geen JPEG-inhoud is, wordt een uitzondering gegooid. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Maakt een nieuw JpegImage‑object aan vanuit de inhoud, weergegeven als byte‑stream,
en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de JPEG-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stream een geldige JPEG-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stroom die vermoedelijk een JPEG-afbeelding bevat |
|

**Returns:**
boolean - True als de opgegeven stroom een geldige JPEG-afbeelding bevat, anders false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64‑gecodeerde string een geldige JPEG-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van de vermoedelijke JPEG-afbeelding in de vorm van een base64-gecodeerde string |
|

**Returns:**
boolean - True als de opgegeven string een geldige JPEG-afbeelding bevat, anders false

### getType() {#getType--}
```
public ImageType getType()
```


Retourneert ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
